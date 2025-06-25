# 💤 Sleep Inducer — A DSA + OOP Console Simulation

**Sleep Inducer** is a C++ console-based simulation built as a course project to demonstrate practical application of **Data Structures & Algorithms (DSA)** and **Object-Oriented Programming (OOP)** concepts.

The project focuses on optimally assigning inmates to dormitories and channels based on their **daily sleep schedule** and **penalty constraints**, simulating a conflict-free scheduling mechanism.

---

## 📌 Features

- 📊 Accepts dynamic input of inmate sleep patterns and penalty constraints
- 🏠 Distributes inmates across dormitories and channels using time conflict resolution
- 📦 Uses **Stacks** from STL to simulate channel allocation and maintain groupings
- 📁 Outputs structured assignment results to `output.txt` for record-keeping
- 🎨 Uses ANSI escape codes for colorful and readable terminal output

---

## 🧠 Concepts Used

- Object-Oriented Programming (C++ classes, constructors)
- STL containers: `vector`, `stack`, `pair`
- Sorting algorithms and greedy allocation logic
- Constraint satisfaction simulation
- File I/O (`ofstream`) to export results

---

## 🧪 Sample Inputs

- Number of inmates
- Inmate data: `Name`, `EarpodID`, `Sleep Pattern (7 days)`, `Penalty`
- Number of dorms and their respective channel capacities

---

## 🖥️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Bhavya-2805/Sleep-Inducer.git
   cd Sleep-Inducer
