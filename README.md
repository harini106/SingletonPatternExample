# Singleton Pattern Example

## Overview

This project demonstrates the **Singleton Design Pattern** in Java.

The Singleton Pattern ensures that only one instance of a class is created and provides a global access point to that instance. In this example, a `Logger` class is implemented as a Singleton to provide consistent logging throughout the application.

---

## Project Structure

```
SingletonPatternExample/
│── Logger.java
│── SingletonTest.java
└── README.md
```

---

## Files

### Logger.java

- Implements the Singleton Design Pattern.
- Uses a private constructor to prevent object creation from outside the class.
- Provides a public static `getInstance()` method to return the single object.
- Contains a `log()` method to print log messages.

### SingletonTest.java

- Tests the Singleton implementation.
- Creates two Logger references using `getInstance()`.
- Verifies that both references point to the same object.

---

## Code Features

- Singleton Design Pattern
- Private Constructor
- Static Instance
- Global Access Method
- Object Reference Comparison

---

## How to Compile

Open Command Prompt in the project folder and run:

```bash
javac Logger.java SingletonTest.java
```

---

## How to Run

```bash
java SingletonTest
```

---

## Expected Output

```
Logger Object Created
Log: Application Started
Log: User Logged In
Only one Logger instance is created.
```

---

## Concepts Used

- Classes and Objects
- Constructors
- Static Variables
- Static Methods
- Access Modifiers
- Singleton Design Pattern

---

## Author

**Harini**

This project was created as part of Java Design Patterns practice.
