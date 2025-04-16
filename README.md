# 🚀 Progress Bar in C

## 📌 Overview
This project implements a **terminal-based progress bar** in C, simulating the progress of multiple tasks with randomized step increments. It visually represents each task's completion percentage.

## ✨ Features
- Displays progress bars for multiple tasks.
- Randomized progress steps for a dynamic effect.
- Clears and updates the screen for smooth visualization.
- Works on both Windows and Linux.

## 🔧 How to Use
1. Clone the repository:
   ```bash
   
   git clone <your-repo-link>
   ```
2. Compile the code:
   ```bash
   
   gcc progress_bar.c -o progress_bar
   ```
3. Run the executable:
   ```bash
   
   ./progress_bar
   ```

## 🔗 Future Enhancements
- Add **color formatting** for better visuals using ANSI escape codes.
- Implement a **multi-threaded version** for real-time updates.
- Allow **customizable task numbers and progress behavior**.

## 📄 Code Breakdown
- **Task Structure:** Uses a struct to store `id`, `progress`, and `step` values.
- **Randomized Progress:** Each task progresses at a unique rate using `rand()`.
- **Dynamic Rendering:** The screen clears and updates continuously for smooth display.
