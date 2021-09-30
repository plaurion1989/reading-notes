# Inheritance & Interfaces
## Inheritance
### **What Is Inheritance?**
Different objects have certain things in common. Object Oriented Programming lets classes inherit those comon states and behaviors from other classes, making the parent **SUPERCLASS**

Every Superclass has the potential for an unlimited number of subclasses in Java.  We use the ***extends*** keyword to define the supperclass our subclass will be inheriting state and behaviors from.  That allows our subclass access to the superclass fields and methods while also allowing our subclass to have the ability to be unique.

~ OBJECT:
Object has no superclass, while every class is implicitly a subclass of Object.  That is because Object is the most generic class of all in the Java Platform Hierarchy.

##### **What can i do in a Subclass?**
- Inherited fields can be used directly
- Declare new fields not in Superclass
- Inherited methods can be used directly
- Write new *instance* methods with the same signature as the superclass (overriding the superclass method)
- Writhe new static methods in a subclass that has the same signature as the one in the superclass (hiding the superclass method)
- Declare new methods not apart of the superclass

## Interfaces
### **What Is Interface?**

The most common type of interfaces are small group of related methods with empty bodies.  Interfaces form a contract that is enforced at build time by the compiler. 

All class methods implementing an interface should appear in your source code in order for the class to compile.  Compilation will fail if the methods are missing at build time.

Using the ***implement*** keyword on a class will allow you to use the interface, though you will likely need to re-name the class you are running your interface on using the keyword.

[Back to Main Page](../README.md)