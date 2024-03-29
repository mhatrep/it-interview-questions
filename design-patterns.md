What is the difference between factory and abstract factory design pattern?
What are the difference between a static class and a singleton class?
Can we create a clone of a singleton object?
How to prevent cloning of a singleton object?
What is Null Object pattern?
When to use Strategy Design Pattern in Java?
Can you write thread-safe Singleton in Java?
When to use Template method design Pattern in Java?
What is the difference between Decorator and Proxy pattern in Java?
When to use Setter and Constructor Injection in Dependency Injection pattern?
What is difference between Factory and Abstract Factory in Java
When to use Adapter pattern in Java? Have you used it before in your project?
Can you write code to implement producer consumer design pattern in Java?
What is Open closed design principle in Java?
What are SOLID principles?
 
------------------------------------
http://geekswithblogs.net/subodhnpushpak/archive/2009/09/18/the-23-gang-of-four-design-patterns-.-revisited.aspx

# Creational Patterns

## Abstract Factory:  Creates an instance of several families of classes. Provide an interface for creating families of related or dependent objects without specifying their concrete classes.
## Builder: Separates object construction from its representation. Separate the construction of a complex object from its representation so that the same construction processes can create different representations.
## Factory Method: Creates an instance of several derived classes. Define an interface for creating an object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.
## Prototype: A fully initialized instance to be copied or cloned. Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.
## Singleton: A class of which only a single instance can exist. Ensure a class only has one instance, and provide a global point of access to it.

# Structural Patterns

## Adapter: Match interfaces of different classes.Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn’t otherwise because of incompatible interfaces.
## Bridge: Separates an object’s interface from its implementation. Decouple an abstraction from its implementation so that the two can vary independently.
## Composite: A tree structure of simple and composite objects. Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.
## Decorator: Add responsibilities to objects dynamically.  Attach additional responsibilities to an object dynamically. Decorators provide a             flexible alternative to subclassing for extending functionality.
## Facade: A single class that represents an entire subsystem. Provide a unified interface to a set of interfaces in a system. Facade defines a higher-level interface that makes the subsystem easier to use.
## Flyweight: A fine-grained instance used for efficient sharing. Use sharing to support large numbers of fine-grained objects efficiently. A flyweight is a shared object that can be used in multiple contexts simultaneously. The flyweight acts as an independent object in each context — it’s indistinguishable from an instance of the object that’s not shared.
## Proxy: An object representing another object. Provide a surrogate or placeholder for another object to control access to it.

# Behavioral Patterns

## Chain of Resp. : A way of passing a request between a chain of objects. Avoid coupling the sender of a request to its receiver by giving more than one object a  chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.
## Command: Encapsulate a command request as an object. Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.
## Interpreter: A way to include language elements in a program. Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
## Iterator: Sequentially access the elements of a collection. Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
## Mediator: Defines simplified communication between classes. Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.
## Memento: Capture and restore an object's internal state. Without violating encapsulation, capture and externalize an object’s internal state so that the object can be restored to this state later.
## Observer: A way of notifying change to a number of classes. Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
## State: Alter an object's behavior when its state changes. Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.
## Strategy: Encapsulates an algorithm inside a class. Define a family of algorithms, encapsulate each one, and make them interchangeable.            Strategy lets the algorithm vary independently from clients that use it.
## Template: Defer the exact steps of an algorithm to a subclass. Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm’s structure.
## Visitor: Defines a new operation to a class without change. Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.


