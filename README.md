<h1 align="center">JAVA OPPs</h1>

<!-- add a image from the images folder -->

![Java Logo](images/java-logo.png)

## Table of Contents

- [What is OPPs?](#what-is-opp)
- [Classes and Objects](#classes-and-objects)

---

## What is OPPs?

Object-Oriented Programming (OOP) is a programming paradigm that organizes code into objects, which are instances of classes. These objects encapsulate data (attributes) and behaviors (methods) to model real-world entities.

### Advantages of OOPs

- **Modularity**: Objects can be reused in different programs.
- **Scalability**: Objects can be scaled up to handle large and complex applications.
- **Flexibility**: Objects can be modified and extended to meet changing requirements.
- **Maintainability**: Objects can be easily maintained and updated.
- **Reusability**: Objects can be reused in different programs.
- **Security**: Objects can be secured to prevent unauthorized access.

---

## Classes and Objects

A class is a blueprint for creating objects. It defines the attributes and behaviors of objects. An object is an instance of a class.

### Classes

A class in not a real world entity, it is a blueprint or prototyope that defines the attributes and behaviors of objects.
A class in Java contains the following:

- **Attributes**: Variables that store data.
- **Constructors**: Methods that initialize objects.
- **Methods**: Functions that perform actions.

### Objects

An object is an instance of a class. It is a real world entity that has attributes and behaviors.
An object is consist of the following:

- **State**: Attributes that store data.
- **Behavior**: Methods that perform actions.
- **Identity**: Unique identifier that distinguishes objects.

### Example

Think of a Car:
properties: Color, Brand, Speed
Actions: Start, Stop, Accelerate, Brake

```java

// Class definition (Blueprint for creating objects)
public class Car {
    // Attributes
    String color;
    String brand;
    int speed;

    // Constructor
    public Car(String color, String brand, int speed) {
        this.color = color;
        this.brand = brand;
        this.speed = speed;
    }

    // Methods
    public void start() {
        System.out.println("Car started");
    }

    public void stop() {
        System.out.println("Car stopped");
    }

    public void accelerate() {
        System.out.println("Car accelerated");
    }

    public void brake() {
        System.out.println("Car braked");
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        // Create objects
        Car car1 = new Car("Red", "Toyota", 0);
        Car car2 = new Car("Blue", "Honda", 0);

        // Access attributes
        System.out.println(car1.color); // Red
        System.out.println(car2.color); // Blue

        // Access methods
        car1.start(); // Car started
        car2.stop(); // Car stopped
    }
}
```

---
