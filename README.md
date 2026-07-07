# cpp-oop-mr
Collection of Object Oriented Programming principles in C++. Includes example files of each pillar (Abstraction, Inheritance, Polymorphism, Encapsulation) and sample programs, all in C++

## What is Object Oriented Programming?
Object Oriented Programming (OOP) is a software design paradigm that organizes code around "objects" rather than logic. Developers frequently contrast OOP with Functional Programming (FP) or Procedural Programming (PP). 

An object is a self-contained unit that groups related data (attributes) and behaviors (methods) together. This type of design paradigm is regularly used to make code more modular, scalable and reusable.

## The 4 Pillars of OOP
1. Encapsulation (Protect the Data): bundles data (variables) and methods (functions) into a single unit (class). This protects the object's internal state from being either directly accessed or messed with by the outside world. This is done by making variables _private_ and only allowing controlled access through _public_ methods, known as _getters_ and _setters_
2. Abstraction (Show Only What's Needed): hides the complex implementation details and only exposes the necessary and essential features or functionalities to the user. Ex: You know how to turn a TV on or off using a remote, but you don't need to know the inner workings of the electrical components. In programming, this is usually achieved using abstract classes or interfaces to create a simple, standardized blueprint.
3. Inheritance (Code Reuse): allows a new class to adopt the properties and behaviors (methods) of an existing class. The OG class known as the parent (or superclass), and the new class is the child (or subclass). This reduces code duplication and lets you create logical, hierarchical relationships between classes. Ex: a _Dog_ and _Cat_ class both inheriting from an _Animal_ parent class. 
4. Polymorphism (Many Forms): means "many forms" and allows you to call the same method on different objects, but each object will execute it in its own specific way. This is typically done through method overriding, where a child class provides a specific implementation for a method that is already defined in its parent class.




