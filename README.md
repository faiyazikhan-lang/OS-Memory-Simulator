# OS Memory Management: FIFO Page Replacement Simulator

## 🚀 Project Overview
This project is a Python-based simulator designed to visualize the **First-In-First-Out (FIFO)** page replacement algorithm. It demonstrates how an Operating System manages memory when the number of page requests exceeds the available physical frames.

## 📄 Technical Report
*   **Situation**: I needed to demonstrate a core Operating System concept Virtual Memory management for my CSE323 course project.
*   **Task**: My objective was to implement a functional simulator that calculates "Page Faults" using the FIFO logic for a given reference string and frame capacity.
*   **Action**: Using Python, I developed a script that tracks the memory state. I implemented a queue based system where the oldest page is evicted (using `.pop(0)`) to make room for new entries when capacity is reached.
*   **Result**: The simulator successfully identified 9 page faults for the tested 10-page sequence, providing a clear visual trace of memory "Hits" and "Misses."

## 🎥 Demo Video
[**Click here to watch the demo**](INSERT_YOUR_YOUTUBE_OR_LOOM_LINK_HERE)

## 💻 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Run the code cell to see the memory trace table.
