# OOPForum

1. (a)


Class: Think of a class as a blueprint or a template. It defines the common properties and behaviors that objects of that type should have. For example, a class called "Product" would define what a product is and what it can do.
    
    
Instantiation: When you create an instance of a class, you're basically using the blueprint to create a specific object. It's like building something based on the blueprint. For example, if you have a class "Product," an instantiation of that class would be a specific product with its own unique details, like a smartphone with a particular brand, model, and price.


(b)


   Inheritance: Inheritance allows classes to inherit properties and behaviors from other classes. It's like passing down traits from parent to child. In the administration program, two examples of inheritance could be:
        
        
   Employee Hierarchy: You can have a base class called "Employee" with common attributes and methods, and then create specific employee classes like "Manager," "OfficeStaff," and "SalesPersonnel" that inherit from the "Employee" class. This way, each specific employee class can have its own unique characteristics while also sharing common features.
        
        
   GUI Design: If all GUIs have a similar design with some differences, you can create a base GUI class with common elements and functionalities. Then, each specific module's GUI can inherit from this base class, allowing customization for module-specific requirements while reusing the common design.


(c)

Libraries: Libraries are pre-written code that provides useful functionalities and tools. They can make the development of programs like the administration program easier and more efficient by offering ready-made solutions. For example:
    
    
Reusability: Libraries can save time by providing existing code for common tasks like accessing databases or handling user authentication, so you don't have to write everything from scratch.
        
     
Modularity: Libraries allow you to break down your program into smaller, manageable pieces. You can use different libraries for different aspects, like product management or salary calculations, which makes your code more organized and maintainable.
        
        
Performance: Libraries often include optimized code, so using them can improve the performance of your program.
      Support and Updates: Libraries are typically maintained by a community of developers. This means you can get support from the community, benefit from bug fixes and updates, and stay up-to-date with the latest features and security patches.

2. (a)
(insert image)


(b)
Accessor methods are necessary for the SalesPerson class to provide controlled access to the instance variables of the class. They allow other parts of the program to retrieve the values of private variables like id, count, and salesHistory without directly accessing them. This helps maintain encapsulation and data integrity by preventing direct modifications to these variables from outside the class.


(c)(i)
(insert image)


(c)(ii)


A negative effect of a future change in the design of the Sales object on this suite of programs could be that the SalesPerson class might not work correctly with the new design if it depends on specific properties or methods of the Sales object. For example, if the Sales object is modified to include a new property or method that the SalesPerson class relies on, the SalesPerson class may need to be updated to accommodate the change. Failure to do so could lead to errors or unexpected behavior in the program.


(d)
(insert image)


(e)
(insert image)


(f)
(insert image)


(g)
(insert image)


(h) To allow salary calculations, changes must be made to the SalesPerson and Sales classes:


Sales class: Add a date attribute to track the date of each sale, allowing filtering of sales by month.


SalesPerson class: Add a method to calculate the salary based on the sales made during a specific month


(i)The only form of polymorphism here is overloading, as there are two different constructors in the SalesPerson class.



