# Visualized Pi Approximation with Monte Carlo Simulation (Python)

This program provides a simple, visual demonstration of approximating the value of the mathematical constant $\pi$ (pi) using the Monte Carlo simulation method on the console.

## Usage

1.  **Download:** First, download the program.
2.  **Open:** Open it with a program that can run Python code (for example, Visual Studio Code or PyCharm).
3.  **Install:** Install the necessary libraries in the console: `pip install numpy matplotlib`
4.  **Run:** Execute the program in the console: `python estimating_pi.py`
5.  **Display:** The program will open a window with two graphs:
    * **Randomly Generated Dots:** Shows the randomly created points. Red dots are inside the imaginary circle, and blue dots are outside. The title displays the count of red and blue dots.
    * **Pi Approximation:** You can follow how the estimated value of pi changes as more points are generated on a line graph.
6.  **Tracking:** The graphs will continuously update as the program generates more and more points.
7.  **Close:** Close the graph window to end the program.

## Features

* **Generating Random Points:** Creates random points within the area of a square.
* **Coloring Points:** Colors the points red if they fall within the imaginary circle and blue if they fall outside.
* **Estimating Pi:** Continuously calculates and displays the estimated value of $\pi$ based on the ratio of points inside the circle to the total number of points.
* **Visual Display:** You can observe the distribution of points and the evolution of the $\pi$ estimation on two graphs.

## Used Language

* Python

## Required Libraries

* NumPy
* Matplotlib

## Author

[Donát Csépke]
