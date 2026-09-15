# Introduction to Design Patterns with Python

This project introduces three fundamental object-oriented design patterns in Python.

The goal is to understand how to organize code so that it remains easier to maintain, extend, and modify as a project grows.

## Design Patterns Covered

### Factory — Creational Pattern

The Factory pattern centralizes object creation.

Instead of having different parts of an application directly create concrete objects, a factory handles the creation process.

In this project, a registry is used to associate a name with a class. New types can be added without modifying the existing creation logic.

### Observer — Behavioral Pattern

The Observer pattern allows an object to notify other objects when an event occurs.

The object producing the event does not need to know the concrete implementation of every listener. Observers can subscribe and react to the events they are interested in.

### Decorator — Structural Pattern

The Decorator pattern allows behavior to be added to an object by wrapping it with other objects.

This makes it possible to combine optional features without creating a large number of subclasses for every possible combination.

## Main Design Principles

### Open/Closed Principle

Software should be open for extension but closed for modification.

The project demonstrates how new functionality can be added without repeatedly modifying stable existing logic.

### Composition over Inheritance

Composition can sometimes be more flexible than inheritance, especially when several optional features need to be combined.

The Decorator pattern demonstrates this approach by allowing objects to be wrapped and extended dynamically.

## Learning Objectives

By completing this project, I will learn how to:

* Understand what design patterns are and when they are useful.
* Distinguish between creational, behavioral, and structural patterns.
* Use the Factory pattern to centralize object creation.
* Use the Observer pattern to decouple event publishers from listeners.
* Use the Decorator pattern to extend behavior through composition.
* Apply the Open/Closed Principle.
* Understand when composition can be preferable to inheritance.
* Write Python code that is easier to extend and maintain.

## Tasks

| Task | Pattern   | Description                                       |
| ---- | --------- | ------------------------------------------------- |
| 0    | Factory   | Extend a factory registry with a new vehicle type |
| 1    | Observer  | Implement an event notification system            |
| 2    | Decorator | Extend objects with composable behavior           |

## Requirements

* Python 3.10+
* PEP 8
* No external dependencies unless explicitly specified
* All Python files must start with:

```python
#!/usr/bin/env python3
```

## Repository

**Repository:** `holbertonschool-sw_design_architecture`

**Directory:** `design_patterns`

## Resources

* [Refactoring.Guru — Design Patterns](https://refactoring.guru/design-patterns)
* Holberton — Introduction to Design Patterns with Python
* Holberton — Conceptual Companion for the project

## Author

**Thomas**
