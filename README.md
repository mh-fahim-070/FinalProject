

---

# TracPro 🗂️

*A Project Management & Collaboration System*

TracPro is a **Java-based desktop application** designed to help teams manage **projects, tasks, calendars, and real-time communication** in one place.
It combines **task tracking**, **Kanban-style workflow**, **calendar scheduling**, and **chat functionality** with a graphical user interface.

---

## 🎯 Project Objective

The main goal of TracPro is to:

* Manage projects and tasks efficiently
* Track progress visually
* Enable real-time team communication
* Practice object-oriented design and client–server architecture

This project was built as a **learning-focused system**, emphasizing **Java, networking, and GUI development**.

---

## ✨ Key Features

* 📋 **Task Management**

  * Create and manage tasks
  * Track task progress and priority
  * Calendar-based task views

* 📆 **Calendar & Kanban Views**

  * Daily task view
  * Kanban-style workflow visualization
  * Progress tracking

* 💬 **Real-Time Chat System**

  * Client–server messaging
  * File transfer support
  * Group chat functionality

* 👥 **User & Project Management**

  * Login and registration
  * Project creation
  * Team member management

* 🖥️ **Desktop GUI**

  * Built with JavaFX
  * FXML-based UI layouts
  * Custom CSS styling

---

## 🛠 Tech Stack

* **Java**
* **JavaFX**
* **FXML**
* **CSS**
* **Socket Programming (Client–Server)**
* **Object-Oriented Programming (OOP)**

---

## 📂 Project Structure

```bash
.
├── src
│   └── com/TracPro
│       ├── accounts        # User and account management
│       ├── calendar        # Task, project, and progress logic
│       ├── chat            # Chat packets and sync handlers
│       ├── gui             # JavaFX UI (FXML, controllers, styles)
│       ├── network
│       │   ├── client      # Client-side networking
│       │   └── server      # Server-side networking
│       └── Packet.java     # Base packet structure
├── storage                 # Local storage / persistence
├── .idea                   # IDE configuration
├── TracPro.iml
└── README.md
```

---

## ▶️ How to Run the Project

### Prerequisites

* Java JDK (8 or higher)
* JavaFX properly configured
* IntelliJ IDEA (recommended)

### Steps

1. Clone the repository
2. Open the project in IntelliJ IDEA
3. Configure JavaFX SDK in Project Settings
4. Run the **Server** first:

   ```java
   com.TracPro.network.server.Server
   ```
5. Run the **Client application**:

   ```java
   sample.Main
   ```

---

## 🧠 Learning Outcomes

Through this project, the following concepts were practiced:

* Java OOP principles
* Client–server communication
* Socket programming
* GUI development with JavaFX
* MVC-style separation
* Real-time data handling

---

## 📌 Notes

* This project is primarily **educational**
* Code may be improved or refactored as learning progresses
* UI and features may evolve over time



If you want, I can:

* Simplify this README for **academic submission**
* Make it **resume / recruiter focused**
* Add **screenshots section**
* Add **architecture diagram explanation**
* Rewrite it in **very basic English**

Just tell me 👍
