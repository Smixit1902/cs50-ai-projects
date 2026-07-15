# CS50 Artificial Intelligence Projects

This repository showcases my solutions and implementation details for Harvard's **CS50's Introduction to Artificial Intelligence with Python** course. Each project focuses on designing and implementing core AI concepts and algorithms from scratch.

> **Academic Honesty Disclaimer:** This repository is intended strictly for portfolio display and educational reference. If you are currently taking the CS50 AI course, please adhere to the course's Academic Honesty guidelines and do not copy this code.

---

## 🚀 Projects Overview

### 🎬 Degrees (Search)
An AI agent that finds the shortest path between two actors by determining how many "degrees of separation" apart they are through their shared movie credits (the "Six Degrees of Kevin Bacon" challenge).

*   **Core Concepts:** Breadth-First Search (BFS), Depth-First Search (DFS), Graph Theory.
*   **Key Learning:** Optimized pathfinding logic to process data efficiently across a complex web of interconnected nodes.
*   **Implementation:** Developed custom frontier tracking using Python objects to parse real-world movie datasets safely and quickly.

---

## 🛠️ Technical Stack & Tools

*   **Language:** Python 3.12+
*   **Version Control:** Git & GitHub
*   **Key Paradigm:** Graph algorithms, Search optimization, Heuristics

---

## ⚙️ How to Run locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com cs50-ai-projects.git
   cd cs50-ai-projects
   ```

2. **Navigate to a specific project folder:**
   ```bash
   cd degrees
   ```

3. **Execute the Python entry point:**
   ```bash
   python degrees.py large
   ```
   *(Note: Dataset folders like `large/` and `small/` must be downloaded from the original CS50 distribution and placed in the project directory, as they are excluded via `.gitignore` to keep repository size lean).*

---

## 📝 Reflection & Architecture

Building these projects reinforced my understanding of computational limits and execution costs. For instance, in the **Degrees** project, switching from standard recursion to a queue-based `Breadth-First Search` frontier significantly improved performance, reducing what could have been a multi-minute recursive lookup into an instantaneous result.
