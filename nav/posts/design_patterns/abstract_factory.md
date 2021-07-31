Abstract Factory Design Pattern

Abstract factory method is a part of `creational design pattern` that provides an interface to create `related` or `dependent` objects without specifying their actual classes.

The main idea is to abstract the object  creation  process depending on business logic.

There is a parent class or so to speak `Interface` which is an abstract class, enforcing to impliment a common method in all its child classes which might have different implimentation based on the nature of class.

These classes are then provided as options to factory class to create objects at runtime.

![71600957ecbf4409af18363f36301db2.png](https://raw.githubusercontent.com/foo290/open-code/gh-pages/_resources/449f0f5c641340e2b18efbd91da852f0.png)

