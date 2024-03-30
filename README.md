# Monty Hall Simulation

This Python code simulates the Monty Hall Problem, a probability puzzle .It assesses the probability of winning for switching (W) versus sticking (T) to the original decision.

__How to Run the Codet__

Prerequisites:

- Python 3 should be installed on your system.
- Required Python packages: numpy, matplotlib.

__Installing numpy and matplotlib:__

- Depending on your operating system, open a terminal (Linux/Mac) or command prompt (Windows).
- Run the following commands:

pip install numpy
pip install matplotlib

- Verify the installation:

import numpy
import matplotlib

__Running the Code:__

1. Save the provided Python code in a file, e.g., monty_hall_simulation.py.
2. Open your terminal or command prompt.
3. Navigate to the directory where monty_hall_simulation.py is saved.
4. Run the code using the command: 'python monty_hall_simulation.py'.
5. The program will prompt you to enter the number of doors (n), the number of doors with cars (k), and the number of samples.
6. After entering the values, click the "Run Simulation" button.
7. The program will display the probability of winning for switching and sticking, along with surface plots illustrating the relationship between n, k, and the ratio of P(win|W) to P(win|T).
8. To exit, close the plot window.

__Understanding the Code:__

- The simulation code is structured to run the Monty Hall Problem simulation and generate surface plots illustrating the probability ratios for different configurations of n and k.
- The Tkinter GUI allows users to input parameters and visualize the results interactively.

__Output:__

- The program outputs the probabilities of winning for switching and sticking, along with surface plots illustrating the relationship between n, k, and the probability ratio.
- The plots provide insights into how the probability ratio (P(win|W) / P(win|T)) changes with different values of n and k.

__Interpreting the Results:__

- Users can observe how the probability ratio (P(win|W) / P(win|T)) changes with different values of n and k.
- From this plot, we could infer the conditions under which switching is more advantageous than sticking, and vice versa.
- Generally, the probability of winning when switching is higher than the probability of winning when sticking, especially as the number of doors (n) and the number of cars (k) increase.
- This is because switching takes advantage of the host's revelation, which provides additional information that can be used to make a more informed decision. 

Note:
- Users can modify parameters such as the number of doors, the number of doors with cars, and the number of samples to analyze different scenarios.

