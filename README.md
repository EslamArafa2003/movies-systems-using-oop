## 📌 Project Title

Media Management System (OOP + Tkinter)

---

## 📌 Project Description

This project is a desktop application for managing media like movies and series.  
The system is built using Object-Oriented Programming (OOP) and Python.

The user can add, view, search, update, and delete media records using a simple interface.

The main goal of this project is to apply OOP concepts in a real-world application.  
This project simulates a real media management system used in real applications.

---

## 📌 Features

- Add new movies or series  
- View all media  
- Search by title  
- Update existing records  
- Delete records  

---

## 📌 OOP Concepts Used

### 🔹 Encapsulation
Data is protected using private variables like `_title` and `__media_list`.  
Access is done using getter methods.

### 🔹 Abstraction
The abstract class `Media` defines a common structure for all media types.  
It includes an abstract method `display()`.

### 🔹 Inheritance
`Movie` and `Series` classes inherit from the `Media` class.  
This helps reuse common code.

### 🔹 Polymorphism
The `display()` method works differently in `Movie` and `Series`.  
Each class has its own implementation.

---

## 📌 Classes Overview

### 🔸 Media (Abstract Class)
- Base class for all media types  
- Contains common attributes (title, genre, year, rating)  

### 🔸 Movie
- Inherits from Media  
- Adds duration  

### 🔸 Series
- Inherits from Media  
- Adds number of seasons  

### 🔸 MovieManager
- Manages all media objects  

Functions:
- `add()`  
- `search()`  
- `update()`  
- `delete()`  

---
### 📌 Technologies Used
Python
Object-Oriented Programming (OOP)
Tkinter (GUI)

## 🚀 How to Run

1. Install Python  
2. Run the main file

## 🎥 Demo Video

Click the image below to watch the demo:

[![Watch the Demo](https://img.icons8.com/ios-filled/500/play-button-circled.png)](https://drive.google.com/file/d/1-r9ouYbyiu6huirFUfDBLWp5BsfM5jqB/view)

