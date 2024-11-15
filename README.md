	

# Java Design Patterns

This repository contains implementations of various design patterns in Java. Design patterns are standard solutions to common problems in software design. They provide a proven method for handling various situations, making code more modular, reusable, and maintainable.

## Table of Contents

- [Creational Patterns](#creational-patterns)
  - [Abstract Factory](#abstract-factory)
  - [Builder](#builder)
  - [Factory Method](#factory-method)
  - [Singleton](#singleton)
- [Structural Patterns](#structural-patterns)
  - [Adapter](#adapter)
  - [Bridge](#bridge)
  - [Decorator](#decorator)
  - [Proxy](#proxy)
- [Behavioral Patterns](#behavioral-patterns)
  - [Command](#command)
  - [Observer](#observer)
  - [State](#state)
  - [Strategy](#strategy)
  - [Template Method](#template-method)

---

### Creational Patterns

#### Abstract Factory
Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

#### Builder
Separates the construction of a complex object from its representation, allowing the same construction process to create different representations.

#### Factory Method
Defines an interface for creating an object but lets subclasses alter the type of object that will be created.

#### Singleton
Ensures a class has only one instance and provides a global point of access to it.

---

### Structural Patterns

#### Adapter
Allows incompatible interfaces to work together by converting one interface into another that a client expects.

#### Bridge
Decouples an abstraction from its implementation, allowing both to vary independently.

#### Decorator
Attaches additional responsibilities to an object dynamically, providing a flexible alternative to subclassing for extending functionality.

#### Proxy
Provides a surrogate or placeholder for another object to control access to it.

---

### Behavioral Patterns

#### Command
Encapsulates a request as an object, thereby allowing for parameterization of clients with queues, requests, and operations.

#### Observer
Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified.

#### State
Allows an object to alter its behavior when its internal state changes, appearing as if it changed its class.

#### Strategy
Defines a family of algorithms, encapsulates each one, and makes them interchangeable, letting the algorithm vary independently from clients.

#### Template Method
Defines the skeleton of an algorithm in a method, deferring some steps to subclasses, allowing them to redefine certain steps without changing the algorithm's structure.

---

## How to Use

Each design pattern has its own directory with Java code examples and explanations. To explore a particular pattern, navigate to its folder and examine the code files to understand its structure and usage.
