
### Java Introduction:

1. **What is Java?**
      - Java is a high-level, object-oriented, platform-independent programming language.
      - It is used to build reliable, secure, and portable software applications.


      | 🔸 **Concept**                  | 🔹 **Summary / Purpose**                                     |
      |-------------------------------  |--------------------------------------------------------------|
      | **1) High-Level Language**     | Easy to read/write, uses English-like words                 |
      |                                | 📌 Makes programming human-friendly                          |
      | **2) OOPs (Object-Oriented)**  | Uses classes & objects, supports Encapsulation, etc.        |
      |                                | 📌 Helps in code reuse, organization, and security           |
      | **3) Platform Independent**    | Code runs on any OS (Windows, Linux, etc.)                  |
      |                                | 📌 *Write once, run anywhere* (done via JVM + bytecode)      |
      | **4) JVM (Java Virtual Machine)** | Runs `.class` bytecode on any system                     |
      |                                | 📌 Converts bytecode → machine code, adds portability        |
      | **5) Compiler (Java)**         | Reads full code at once, creates bytecode                   |
      |                                | 📌 Not like Python (line by line); prepares code for JVM     |

# 🔁 Java Architecture 

---![1d02dcce-99f3-4234-9556-2f73f096bf95](https://github.com/user-attachments/assets/091a929a-a95b-4eea-b16e-0f0a36af6693)

## ✅ Java Components Explained

### **1️⃣ JDK – Java Development Kit**

🔹 Think of JDK as a **toolbox for developers**  
🔹 It includes:  
 ✔ Java Compiler (to convert code to bytecode)  
 ✔ JRE (to run the code)  
 ✔ Development tools  
📌 **Use:** If you're writing or developing Java programs, you need JDK.

---

### **2️⃣ JRE – Java Runtime Environment**

🔹 JRE is like a **player** that runs Java programs  
🔹 It includes:  
 ✔ JVM (to run the bytecode)  
 ✔ Core libraries  
📌 **Use:** If you're only running Java apps (not creating them), JRE is enough.

---

### **3️⃣ JVM – Java Virtual Machine**

🔹 JVM is the **heart of Java**  
🔹 It takes bytecode (compiled Java code) and **converts it into machine code**  
🔹 Makes Java **platform-independent**  
📌 **Use:** JVM lets the same Java program run on any OS (Windows, Linux, etc.)

### IDE:
  
      An IDE, or Integrated Development Environment, is like a digital workspace where programmers write, edit, and manage their code. It provides tools such as a code editor, debugger, and compiler, all in one place, making it easier for developers to create and maintain their software.

### Package:
   
      In Java, a package is a way to organize and group related classes and interfaces. It helps in avoiding naming conflicts and enhances the overall structure of a program.

### Class:
  
      In Java, a class is a blueprint or template that defines the properties (attributes) and behaviors (methods) that objects created from the class will have.

### Variables:
 
     Variables in Java are like containers that store data. They have a type (int, double, String) and a name. Use variables to store and manipulate data.

### Data Types in Java

Data types define the kind of data a variable can hold. In Java, there are two main types:

### Syntax for Declaring Variables

```java
dataType variableName = value;
```

### Data Types in Java

| Type              | Description                  | Example               |
|-------------------|------------------------------|-----------------------|
| **Primitive**     | Basic data types              |                       |
| `int`             | Integer numbers              | `int age = 25;`       |
| `double`          | Decimal numbers              | `double price = 9.99;`|
| `char`            | Single character             | `char grade = 'A';`   |
| `boolean`         | True or false                | `boolean flag = true;`|
| **Non-Primitive** | Objects and classes          |                       |
| `String`          | Text data                   | `String name = "Hi";`  |
| `Integer`         | Wrapper class for int        | `Integer num = 10;`    |

--- 
### Variable Storage: RAM

All variable data is temporarily stored in **RAM** while the program runs.

| Feature      | RAM                                |
|--------------|-----------------------------------|
| Type         | Temporary (Volatile)               |
| Created when | Program starts running             |
| Deleted when | Program ends or system shuts down |
| Purpose      | Fast, short-term data access       |

---


### Conditional Statements:
     Conditional statements  are used to control the flow of the program based on certain conditions. These statements allow the program to make decisions and execute different blocks of code depending on whether a specified condition evaluates to true or false. The primary conditional statements in Java include:

### 1. `if` Statement:

**Definition:**
The `if` statement is used to execute a block of code only if a specified condition is true.

**Syntax:**
```java
if (condition) {
    // Code to be executed if the condition is true
}
```

### 2. `if-else` Statement:

**Definition:**
The `if-else` statement is used to execute one block of code if the condition is true and another block of code if the condition is false.

**Syntax:**
```java
if (condition) {
    // Code to be executed if the condition is true
} else {
    // Code to be executed if the condition is false
}
```

### 3. `if-else if-else` Statement:

**Definition:**
The `if-else if-else` statement allows you to check multiple conditions in sequence. It executes the first block of code whose condition is true.

**Syntax:**
```java
if (condition1) {
    // Code to be executed if condition1 is true
} else if (condition2) {
    // Code to be executed if condition2 is true
} else {
    // Code to be executed if none of the conditions is true
}
```

### Switch-case statement:

    The switch-case statement in Java is a conditional statement used to make decisions based on the value of an expression. 
 - The switch statement evaluates the expression and then compares it against various case values. When a match is found, the associated block of code is executed.

**Syntax:**

```java
switch (expression) {
    case value1:
        // Code to be executed if expression equals value1
        break;
    case value2:
        // Code to be executed if expression equals value2
        break;
    // Additional cases as needed
    default:
        // Code to be executed if none of the cases match
}
```

### If vs Switch-case: Key Differences

      | **Aspect**             | **`if` Statement**                        | **`switch` Statement**                     |
|------------------------|-------------------------------------------|-------------------------------------------|
| **Condition Type**     | Complex and multiple conditions           | Simple equal-value checks                 |
| **Number of Choices**  | Few or complex conditions                 | Many options for one variable             |
| **Data Types**         | Any type (`int`, `boolean`, etc.)         | Limited types (`int`, `char`, `String`)   |
| **Logic Flexibility**  | Supports `&&`, `||`, method calls         | Only checks if equal to constant values   |
| **Flow Control**       | No fall-through                          | Needs `break` to stop fall-through        |
| **Default Option**     | Use `else`                               | Has built-in `default` case               |


---

### Differences Between `=`, `==`, and `.equals()`

| Symbol/Method | Use For       | Compares                              | Example             |
|---------------|--------------|-------------------------------------|---------------------|
| `=`           | Assignment   | Assigns value to a variable          | `int x = 5;`        |
| `==`          | Comparison   | Checks if primitive values are equal or if objects have the same memory address | `x == y` (primitives or references) |
| `.equals()`   | String/Object| Checks if objects have the same content/data | `str1.equals(str2)` |
