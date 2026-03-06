# 🗂️ Task Scheduler – Min Heap Priority System

A web-based Task Scheduling Application that implements a real Min Heap data structure to manage tasks based on priority. Built as a Data Structures capstone project.

🌐 Live Demo:
https://ppr276.github.io/Task-Scheduler-Min-Heap/

## 📌 Overview

This project demonstrates the practical implementation of a **Min Heap (Priority Queue)** to efficiently manage tasks based on priority levels. 

Tasks are inserted into a heap structure and automatically arranged such that the highest-priority task (lowest priority number) is always accessible in O(1) time, with insertion and removal operations performed in O(log n).

The application includes a responsive web interface for task input, visualization, and real-time heap status tracking.

---

## 🚀 Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Object-Oriented Programming
- Min Heap Data Structure

---

## 🧠 Core Data Structure Implemented

### Min Heap

- Insert → O(log n)
- Extract Min → O(log n)
- Peek (Get Next Task) → O(1)
- Heapify Up & Heapify Down implemented manually
- Custom priority comparison logic

The heap ensures that tasks with the highest priority (lowest numerical value) are processed first.

---

## ✨ Features

- Add tasks with:
  - Name
  - Priority (1–10)
  - Duration
  - Deadline
  - Description
- Real-time Min Heap operations
- Get next task without removal (Peek)
- Complete highest priority task (Extract Min)
- Automatic heap reordering
- Deadline-based urgency classification:
  - Urgent
  - Due Soon
  - On Track
- Task statistics dashboard:
  - Total tasks
  - Urgent tasks
  - Total duration
  - Heap size
- Interactive emoji feedback system
- Fully responsive UI

---

## 📊 Concepts Applied

- Data Structures (Min Heap / Priority Queue)
- Time Complexity Analysis
- Object-Oriented Programming
- DOM Manipulation
- Event Handling
- UI Design Principles
- Algorithm Visualization

---

## 🎯 Learning Outcomes

- Implemented heap operations from scratch
- Understood tree indexing logic in arrays
- Applied algorithmic thinking to real-world scheduling
- Integrated data structure logic with a frontend interface
- Analyzed performance complexity of heap operations

---

## ▶️ How to Run

1. Download or clone the repository.
2. Open `maxheap scheduler.html` in a browser.
3. Add tasks and observe heap-based priority behavior.

(No external backend required.)

---

## 👩‍💻 Author

Pamula Pravallika Reddy  
B.Tech Computer Science Engineering  
Amrita Vishwa Vidyapeetham, Chennai
