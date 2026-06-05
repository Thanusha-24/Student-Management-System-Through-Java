# Student-Management-System-Through-Java

# TASK-2 STUDENT MANAGEMENT SYSTEM

**COMPANY:** AFLIDO TECH

**NAME:** KUNDA THANUSHA

**INTERN ID:** BS/REG/119443

**DOMAIN:** JAVA

**DURATION:** 8 WEEKS

---

# Task Overview

This repository contains my implementation for **Task 2 – Student Management System**. The objective of this task is to understand and apply Java programming concepts such as classes, objects, ArrayLists, loops, switch statements, and user input handling.

The project is a simple **Student Management System** developed using Java. It allows users to add student records, view all stored student information, and manage data through a menu-driven interface.

This task helped me gain practical experience with object-oriented programming and collection frameworks in Java.

---

# Project Description

The Student Management System performs the following operations:

* Add new student records
* Store student details using ArrayList
* View all stored students
* Menu-driven user interaction
* Exit the application safely

Each student record contains:

* Student ID
* Student Name
* Student Age

The program accepts input from the user and displays student information through the console.

---

# Concepts Used

### 1. Classes and Objects

A class named `Student` is created to represent student details such as ID, name, and age.

Objects of the Student class are created and stored in the system.

### 2. Constructor

A constructor is used to initialize student information when a new student object is created.

```java
Student(int id, String name, int age)
```

### 3. ArrayList Collection

The program uses Java's `ArrayList` class to dynamically store multiple student records.

```java
ArrayList<Student> students = new ArrayList<>();
```

### 4. User Input

The `Scanner` class is used to accept data from the user.

```java
Scanner sc = new Scanner(System.in);
```

### 5. Looping and Menu System

A `do-while` loop is used to repeatedly display the menu until the user chooses to exit.

### 6. Switch Statement

The switch statement handles different menu options and executes the corresponding functionality.

---

# Program Workflow

### Step 1: Display Menu

The program displays the following options:

1. Add Student
2. View Students
3. Exit

### Step 2: Add Student

The user enters:

* Student ID
* Student Name
* Student Age

The information is stored in the ArrayList.

### Step 3: View Students

All stored student records are displayed on the screen.

### Step 4: Exit Program

The application terminates when the user selects the Exit option.

---

# Sample Output

```text
--- Student Management System ---
1. Add Student
2. View Students
3. Exit
Enter your choice: 1

Enter Student ID: 101
Enter Student Name: John
Enter Student Age: 20

Student added successfully!
```

### Viewing Students

```text
Student List:

ID: 101 Name: John Age: 20
ID: 102 Name: Alice Age: 21
```

### Exiting Program

```text
Exiting program...
```

---

# Results & Analysis

The Student Management System successfully manages student records using Java collections.

Key observations:

* Demonstrates object-oriented programming concepts.
* Uses ArrayList for dynamic data storage.
* Provides a user-friendly menu-driven interface.
* Allows multiple student records to be stored and displayed.
* Improves understanding of constructors, loops, and switch statements.

---

# Conclusion

This task successfully demonstrates the implementation of a Student Management System using Java. Through this project, I gained practical experience with classes, objects, constructors, collections, loops, and user interaction.

The project provides a strong foundation for developing larger database-driven management systems in the future.

---

# Tech Stack

* Java
* JDK (Java Development Kit)
* VS Code / Eclipse / IntelliJ IDEA
* Java Collections Framework (ArrayList)
* Command Prompt / Terminal

---

# Files Included

### Task2_StudentManagementSystem.java

Contains the complete source code for the Student Management System.

### Output-2.jpg

Screenshot of the program execution output.

### README.md

Project documentation and explanation.

---

# Output

The program allows users to add student records, view stored student information, and manage records through a simple menu-driven interface. The output is displayed in the console and updates dynamically based on user input.
