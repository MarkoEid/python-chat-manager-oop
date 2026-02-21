# 💬 User Chat Application (OOP)

## 📖 Project Overview
This project is a Python-based messaging logic system built using **Object-Oriented Programming (OOP)**. It focuses on simulating a basic chat environment where unique users can send messages, handle empty input validation, and retrieve their communication history.

---

## 📂 System Logic & Class Structure
The core of the application is built around the `User` class, which handles all data and actions for individuals within the system.



### 👤 The User Class
* **Attributes:**
    * `username`: Stores the unique identity of the user.
    * `messages`: A dynamic list that acts as a storage for all sent communications.
* **Methods:**
    * `send_message(msg)`: Includes logic to verify if a message is empty before appending it to the history, providing feedback if no text was entered.
    * `view_messages()`: Retrieves and prints the entire message history for that specific user.

---

## 🛠️ Key Programming Features
* **Input Validation:** Prevents the system from storing empty or null messages.
* **Dynamic Storage:** Utilizes Python lists to manage a growing history of strings.
* **User Personalization:** Demonstrates how instance-specific data (messages) is kept separate between different `User` objects.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Programming Paradigm:** Object-Oriented Programming (OOP)

---

## 🚀 How to Use
1. Open the `Chat Application.ipynb` notebook.
2. Initialize a new user: `u1 = User("YourName", [])`.
3. Send a message: `u1.send_message("Hello World!")`.
4. View your history: `u1.view_messages()`.

---
