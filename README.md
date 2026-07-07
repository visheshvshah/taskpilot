<p align="center">
  <img src="logo.png" alt="TaskPilot Logo" width="220">
</p>

<h1 align="center">TaskPilot</h1>

<p align="center">
  <strong>An Intelligent Command-Line Task Management System built with Modern C++</strong>
</p>

<p align="center">
TaskPilot simplifies personal task management through smart prioritization, automated reminders, and persistent local storage within a lightweight command-line interface.
</p>

---

## 📖 Overview

TaskPilot is a console-based task management application developed using Modern C++. It enables users to efficiently organize, prioritize, and monitor daily tasks through an interactive command-line interface.

The application combines object-oriented programming with efficient data structures to provide intelligent task scheduling, deadline tracking, reminder notifications, and persistent CSV-based storage. It demonstrates practical usage of Modern C++ features including STL, multithreading, regular expressions, and file handling.

---

## ✨ Features

- Create, update, and delete tasks
- Assign priorities and deadlines
- Intelligent task recommendation using a Priority Queue
- Automated reminder notifications
- Persistent task storage using CSV files
- Mark tasks as completed
- View pending and completed tasks
- Deadline tracking
- Input validation using Regular Expressions
- Interactive command-line interface
- Cross-platform compatibility (Windows & Linux)

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

## 🧠 Core Concepts

- Object-Oriented Programming
- Standard Template Library (STL)
- Priority Queue Scheduling
- File Handling
- CSV Data Persistence
- Multithreading
- Regular Expressions
- Input Validation
- Modular Function Design
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
2. Enter a CSV filename to store tasks.
3. Create, update, and manage tasks through the interactive menu.
4. Tasks are automatically saved to the CSV file.
5. Existing tasks are loaded automatically on subsequent runs.

---

## 🚀 Getting Started

### Prerequisites

- GCC 11+ (or any compiler with C++17 support)

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

## 👨‍💻 Author

**Vishesh Shah**

B.Tech in Mathematics & Computing  
Dhirubhai Ambani University (DAU)

GitHub: https://github.com/visheshvshah

---

## 📜 License

This project is intended for educational purposes and continuous learning.
