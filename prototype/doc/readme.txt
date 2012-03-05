========================================================================================================================================================================
Prototype Pattern 

- in the Prototype Pattern we create one standard object for each class, and clone that object to create new instances.
- in this example we have an abstract BookPrototype class, with two specific or concrete subclasses, PHPBookPrototype and SQLBookPrototype. 
- to create a object using either PHPBookPrototype or SQLBookPrototype we call the clone method.
========================================================================================================================================================================= 