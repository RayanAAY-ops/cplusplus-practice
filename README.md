# cplusplus-practice
One month practice of C++ using chatgpt roadmap then switch to Rust

Why Start with C++?

    C++ gives you a strong grasp of low-level programming concepts, like memory management, pointers, and object-oriented design. These are foundational for understanding Rust's design choices.
    By working with C++, you’ll experience the challenges Rust aims to solve, like manual memory management, undefined behavior, and concurrency issues.
    C++ is widely used in legacy systems, so understanding it adds career versatility.
    
Here’s a **one-month roadmap** to get started with C++ and build a solid foundation:

---

### **Week 1: Core Basics**
#### Goals:
- Understand syntax and basic constructs.
- Write simple programs.

#### Topics:
- Set up your environment: Install GCC, Visual Studio, or CLion.
- **Syntax & Basics**: Variables, data types, input/output (`cin`, `cout`), comments.
- **Control Flow**: `if`, `else`, loops (`for`, `while`, `do-while`).
- **Functions**: Declaring, defining, and calling functions.
- **Basic I/O**: File input/output (`fstream`).
- **Arrays & Strings**: Declaring, using, iterating.
- **Pointers**: Basics, dereferencing, and pointer arithmetic.
- **Dynamic Memory Allocation**: `new`, `delete`, and `nullptr`.
- **References**: Why and when to use them.
- **Structs**: Create and manipulate simple user-defined types.

#### Practice:
- Write a program to calculate factorial.
- Build a simple calculator using `switch`.
- Implement a program to reverse an array.
- Write a program using pointers to swap two variables.

---

### **Week 2: Core C++ Features
#### Goals:
- Master C++-specific features and ecosystem.
- Dive into memory management and language nuances.

#### Topics:
**Pointers and References**: Advanced manipulation, pointer arithmetic, double pointers, and smart pointers (std::unique_ptr, std::shared_ptr).
**Memory Management**: Manual allocation with new/delete, stack vs heap, and RAII (Resource Acquisition Is Initialization).
**Namespaces**: Usage of namespace to avoid name collisions (std and custom namespaces).
C**onst Correctness**: const for variables, pointers, references, and functions.
**Function Overloading & Default Arguments**.
#### Practice:
- Create a program that uses dynamic memory allocation for a 2D matrix.
- Implement a simple reference-counting smart pointer (if you feel ambitious).
---

### **Week 3: Object-Oriented Programming (OOP)**
#### Goals:
- Understand and apply OOP principles.
- Create simple object-oriented programs.

#### Topics:
- **Classes & Objects**: Define and use classes.
- **Access Specifiers**: Public, private, protected.
- **Constructors & Destructors**: Initialization and cleanup.
- **Inheritance**: Single and multilevel inheritance.
- **Polymorphism**: Function overloading, overriding, and virtual functions.
- **Classes and Objects**: Deep dive into constructors, destructors, copy constructors, and assignment operators.
- **Inheritance**: Single, multiple, virtual inheritance, and resolving ambiguities.
- **Polymorphism**: Abstract classes, pure virtual functions, and dynamic dispatch using vtables.
- **Operator Overloading**: Implementing operators like +, [], <<, etc.
- **Encapsulation and Access Control**: Public, private, protected.

#### Practice:
- Design a `Car` class with properties and methods (e.g., `speedUp`, `applyBrakes`).
- Implement a simple inheritance example (`Vehicle` -> `Car` -> `ElectricCar`).
- Implement a class for a Vector with overloaded operators (+, *, []).
- Build a small class hierarchy (Shape -> Circle, Rectangle) with virtual methods like area().
---

### **Week 4: Advanced Topics & Project**
#### Goals:
- Learn advanced features and apply everything to a project.

#### Topics:
- Templates: Function and class templates, template specialization, and variadic templates.
- STL (Standard Template Library):
    - Containers: vector, list, map, unordered_map, set, deque.
    - Iterators and ranges.
    - Algorithms: sort, find, binary_search, transform.

Modern C++ (C++11 and beyond):
    - Lambda expressions.
    - auto, decltype, and constexpr.
    - Move semantics (std::move) and rvalue references.
    - std::thread and basic concurrency

####Topics:

  Design Patterns: Singleton, Factory, Observer.
  File Handling: Binary and text files, serialization/deserialization.
  Error Handling: Exception hierarchy and custom exceptions.
  Profiling and Debugging: Use tools like gdb, valgrind, and perf for memory and performance analysis.

Project Ideas:

  Real-Time Chat Application (Console-Based):
      Use std::thread for sending/receiving messages concurrently.
      File logging for chat history.
  Data Processor:
      Read data from a file, process it (e.g., aggregate stats), and save the results.
      Use STL containers and algorithms extensively.

---

### Tools & Resources:
- **Books**: "C++ Primer" by Stanley B. Lippman or "Programming: Principles and Practice Using C++" by Bjarne Stroustrup /"Modern C++" on Udemy by Rainer Grimm / Effective Modern C++ by Scott Meyers.


- **Courses**: 
  - FreeCodeCamp's C++ YouTube tutorials.
  - Codecademy or Udemy beginner courses.
- **Practice**: LeetCode (C++ tag), HackerRank, or Codeforces for C++ challenges.
- Tools & Resources:
