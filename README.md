Algorithm Visualizer
Algorithm Visualizer is a Python application that uses Pygame to visually represent sorting algorithms.
It displays a randomized array of bars, each with a different height, and shows how different sorting algorithms arrange these bars in real-time.
The goal is to help users understand how each algorithm works by showing the process step-by-step.

Features
Visual representation of common sorting algorithms (e.g., Bubble Sort, Merge Sort, Quick Sort)
Color-coded bars to show the current state of sorting
Dynamic bar animations to represent swaps and comparisons
Configurable settings for array size, sorting speed, and selected algorithm

How It Works
The application begins by generating a randomized list of numbers represented by vertical bars of varying heights.
When a sorting algorithm is selected, the visualizer will display the sorting process step-by-step:

Randomized Array Generation: Creates a list of bars with random heights but uniform width.
Sorting: Runs the selected sorting algorithm and visually represents swaps, comparisons, and placements.
Animation: Uses Pygame to draw each frame of sorting in a separate color to highlight ongoing operations.

Technologies Used
Python: Core programming language used for the application.
Pygame: Graphics library used to create the visualizer, handle rendering, and manage screen updates.

