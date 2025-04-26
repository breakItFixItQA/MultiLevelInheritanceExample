# MultiLevelInheritanceExample

Multi-Level Inheritance Example in Java
📋 Overview
This project demonstrates Multi-Level Inheritance in Java, where a child class (Child1) inherits from a parent class (Parent1), which itself inherits from a grandparent class (GrandParent).

It shows:

How properties and methods are passed down through multiple levels of inheritance.

How a single object (Child1) can access attributes and behaviors from its parent and grandparent classes.

📂 Project Structure
GrandParent class:

Property: lastName (String)

Method: message1() (Prints a message from the grandparent)

Parent1 class (extends GrandParent):

Property: parentJob (String)

Method: message2() (Prints a message from the parent)

Child1 class (extends Parent1):

Property: school (String)

Method: message3() (Prints a message from the child)

MultiLevelInheritanceExample class:

Contains the main() method.

Creates an instance of Child1.

Demonstrates accessing properties and methods across three levels: Child → Parent → Grandparent.

🚀 How It Works
An object of Child1 is created.

Through inheritance:

It accesses its own fields (school) and methods (message3()).

It accesses inherited fields (parentJob) and methods (message2()) from Parent1.

It also accesses inherited fields (lastName) and methods (message1()) from GrandParent.

🛠 Example Output
vbnet
Copy
Edit
Child's school is: Greenwood High School
Message from Child
Parents Job: Engineer
Message from Parent
Last Name: Johnson
Message from GrandParent
📚 Concepts Demonstrated
Inheritance (Multi-Level Inheritance)

Method Overriding (if added later)

Object-Oriented Programming (OOP) Fundamentals
