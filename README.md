# 👑 8-Queens Chess Game: A Structured Programming Approach

[![Language](https://img.shields.io/badge/Language-C%2B%2B-blue.svg)](https://en.cppreference.com/)
[![Environment](https://img.shields.io/badge/IDE-Visual%20Studio%202019-purple.svg)](https://visualstudio.microsoft.com/vs/older-downloads/)
[![University](https://img.shields.io/badge/Pharos-University-green.svg)](https://www.pua.edu.eg/)
[![Department](https://img.shields.io/badge/Dept-Computer%20Engineering-red.svg)](#)

## 📖 Project Overview
This project is an interactive implementation of the classic **8-Queens Puzzle**. It was developed to demonstrate the principles of **Structured Programming**, focusing on algorithmic logic and procedural abstraction. The goal is to place 8 queens on an 8x8 board such that no two queens attack each other.

**Academic Context:**
* **University:** Pharos University in Alexandria (PUA).
* **Faculty:** Faculty of Engineering.
* **Department:** Computer Engineering Department.
* **Course:** Structured Programming.

## ✨ Features
- **Interactive Gameplay:** Users can manually input coordinates to place queens.
- **Real-time Validation:** Automated checking for row, column, and diagonal conflicts.
- **Dynamic Board Visualization:** A clear console-based representation of the 8x8 grid.
- **Structured Design:** Modular code architecture for readability and maintenance.

## 🧠 Core Logic & Implementation
The program is built using a structured, step-by-step approach:
1. **Board Initialization:** Efficient setup of the 8x8 matrix representing the chessboard.
2. **Safety Check Logic:** A dedicated function `isSafe(int row, int col)` validates each move by checking:
    - Vertical and horizontal attacks.
    - Upper and lower diagonal threats.
3. **User Interaction:** Robust input handling to capture player moves and provide immediate feedback on the game state.

## 🛠️ Technical Stack
- **Language:** C++
- **IDE:** Microsoft Visual Studio 2019
- **Paradigm:** Structured / Procedural Programming

### 🚀 Getting Started

To get the project up and running on your local machine, follow these steps:

#### 1. Open the Project
* **Launch** Visual Studio 2019.
* Navigate to **File** -> **Open** -> **Project/Solution**.
* Select the `8-Queen-Game.sln` file or the main `.cpp` source file.

#### 2. Run the Game
* Press `Ctrl + F5` to compile and launch the console application without debugging.

---

### 📂 Repository Structure

The project directory is organized as follows:

```text
├── 8-Queen-Game.cpp      # Main source code containing core game logic
├── 8-Queen-Game.sln      # Visual Studio solution file for environment setup
├── 8-Queen-Game.vcxproj  # Visual Studio project configuration file
└── README.md             # Project documentation and guide

### 🧠 Core Logic & Implementation

The program is built using a **Structured Programming** approach, dividing the game into clear, logical modules:

* **Board Initialization:** Setting up and resetting the 8x8 matrix representing the chessboard.
* **Safety Check:** A dedicated function `isSafe(int row, int col)` validates the placement of each queen against existing queens to prevent conflicts.
* **User Interaction:** Robust input handling to capture player moves, update the board state, and provide real-time feedback.
