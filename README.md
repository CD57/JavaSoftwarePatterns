# Java Software Patterns
Java examples of multiple software patterns.

Creational patterns concern the process of object creation. 
Structural patterns deal with the composition of classes or objects.
Behavioural patterns characterize the ways in which classes or objects interact and distribute responsibility.

# Creational Patterns
Creational class patterns defer some part of object creation to subclasses, while creational object patterns defer it to another object.

### Abstract Factory: 
Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

### Factory Method: 
Defines an interface for creating an object, but allows subclasses to decide which class to instantiate, allowing a class to defer instantiation to subclasses.

### Builder: 
Separates the construction of a complex object from its representation so that the same construction process can create different representations.

### Singleton: 
Ensures a class only has one instance and provides a global point of access to it.

### Prototype: 
Specifies the kinds of objects to create using a prototypical instance and creates new objects by copying this prototype. 

# Structural Patterns
Structural class patterns use inheritance to compose classes, while the structural object patterns describe ways to assemble objects.

### Adapter: 
Converts the interface of a class into another interface client classes expect, allowing classes to work together that couldn't otherwise because of incompatible interfaces.

### Bridge: 
Decouples an abstraction from its implementation so that the two can vary independently.

### Composite:
Composes objects into tree structures to represent part-whole hierarchies, allowing clients to treat both individual objects and compositions of objects uniformly.

### Decorator: 
Attaches additional responsibilities to an object dynamically, providing a flexible alternative to subclassing for extending functionality.

### Façade: 
Provides a unified interface to a set of interfaces in a subsystem by defining a higher-level interface that makes the subsystem easier to use.

### Proxy: 
Provides a surrogate or placeholder for another object to control access to it.


Behavioural class patterns use inheritance to describe algorithms and flow of control, whereas the behavioural object patterns describe how a group of objects cooperate to perform a task that no single object can carry out alone.
