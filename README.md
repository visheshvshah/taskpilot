<p align="center">
  <img src="logo.png" alt="TaskPilot Logo" width="220">
</p>

<h1 align="center">TaskPilot</h1>

<p align="center">
  <strong>A Modern C++ Command-Line Productivity Tool featuring Intelligent Task Scheduling, Deadline Tracking, and Persistent Storage.</strong>
</p>

<p align="center">
TaskPilot helps users efficiently organize, prioritize, and track their daily tasks through an interactive command-line interface powered by Modern C++.
</p>

---

## 📖 Overview

TaskPilot is a feature-rich command-line task management application developed using Modern C++. It is designed to simplify personal productivity by allowing users to organize, prioritize, monitor, and manage their daily tasks from a lightweight console application.

Managing multiple tasks manually often leads to missed deadlines and reduced productivity. TaskPilot addresses this challenge by providing a centralized platform where users can create, update, organize, and monitor tasks with intelligent scheduling and automated reminders.

The application enables users to maintain a structured to-do list, assign priorities, update deadlines, track completed and pending tasks, identify overdue tasks, and receive intelligent recommendations on which task should be completed first based on urgency and priority.

All tasks are stored locally using CSV-based persistent storage, ensuring that user data is preserved across multiple sessions. The project demonstrates practical implementation of Object-Oriented Programming, Modern C++17 features, STL containers, multithreading, regular expressions, priority queues, and file handling to solve a real-world productivity problem.

---

## ✨ Features

- ➕ Create new tasks with descriptions, priorities, and deadlines
- ✏️ Update existing task details and deadlines
- ❌ Delete tasks that are no longer required
- ✅ Mark tasks as completed
- 📋 View pending and completed tasks
- ⏰ Track approaching and overdue deadlines
- 🚨 Automatic reminder notifications for upcoming tasks
- 🎯 Intelligent task recommendation based on priorities and deadlines
- 📂 Persistent task storage using CSV files
- 📊 Export tasks for structured offline viewing
- 🔍 Input validation using Regular Expressions
- 🖥️ Interactive command-line interface
- 🌐 Cross-platform compatibility (Windows & Linux)

---

## 💡 Why TaskPilot?

TaskPilot was built to demonstrate how Modern C++ can be applied to solve a practical productivity problem using efficient algorithms, robust software design, and modern programming concepts.

Unlike a basic CRUD-based console application, TaskPilot integrates intelligent task prioritization, automated reminders, deadline tracking, persistent storage, multithreading, and input validation into a complete productivity solution.

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Language | C++17 |
| Programming Paradigm | Object-Oriented Programming |
| Data Structures | Vector, Priority Queue |
| Standard Library | STL |
| Concurrency | Multithreading (`std::thread`) |
| Validation | Regular Expressions |
| Storage | CSV File Handling |
| Utilities | Chrono, File Streams |

---

## 🧠 Core Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Standard Template Library (STL)
- Priority Queue Scheduling
- File Handling
- CSV Data Persistence
- Multithreading
- Regular Expressions
- Input Validation
- Modular Programming
- Software Design Principles

---

## 📂 Project Structure

```text
TaskPilot/
│
├── Task.cpp
├── README.md
├── logo.png
└── .gitignore
```

---

## ⚙️ How It Works

1. Launch the application.
2. Enter a CSV filename to store your tasks.
3. Create, update, or remove tasks through the interactive menu.
4. Assign priorities and deadlines to each task.
5. Receive reminder notifications for upcoming deadlines.
6. View pending, completed, and overdue tasks.
7. Get intelligent recommendations for the next task based on priority and deadlines.
8. Tasks are automatically saved and loaded during future sessions.

---

## 🚀 Getting Started

### Prerequisites

- GCC 11+ (or any compiler supporting C++17)
- C++17 enabled compiler

### Clone the Repository

```bash
git clone https://github.com/visheshvshah/taskpilot.git
cd taskpilot
```

### Compile

```bash
g++ -std=c++17 Task.cpp -o TaskPilot
```

### Run

**Windows**

```bash
TaskPilot.exe
```

**Linux / macOS**

```bash
./TaskPilot
```

---

## ⚠️ Special Requirements

> **Warning**
>
> TaskPilot uses multithreading to provide typing animations, reminder notifications, and timed delays throughout the application.
>
> The project has been tested successfully on supported C++17 compilers.
>
> If you encounter compilation or runtime issues, ensure that:
>
> - Your compiler supports the C++17 standard.
> - Your operating system provides thread support.
> - Appropriate thread execution permissions are available.

---

## 👨‍💻 Author

**Vishesh Shah**

B.Tech in Mathematics & Computing  
Dhirubhai Ambani University (DAU)

GitHub: https://github.com/visheshvshah

---

## 📜 License

This project is intended for educational purposes and continuous learning.
