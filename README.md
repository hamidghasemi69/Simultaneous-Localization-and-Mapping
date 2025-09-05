# Simultaneous Localization and Mapping (SLAM)

**Implementing Simultaneous Localization and Mapping Technique to Track the Location of a Robot in a 2D World**

This project demonstrates the implementation of the Simultaneous Localization and Mapping (SLAM) technique to track the location of a robot in a two-dimensional environment. The SLAM algorithm allows the robot to build a map of its surroundings while simultaneously keeping track of its own location within that map.

---

## Project Overview

- **`Objective`**: Implement SLAM to enable a robot to navigate and map an unknown environment in 2D.
- **`Approach`**: Utilize a combination of motion models and sensor data to estimate the robot's position and map the environment.
- **`Environment`**: Simulated 2D world with predefined landmarks.

---

## Repository Structure

- **Robot Moving and Sensing.ipynb** — Jupyter notebook for simulating robot movement and sensor readings.
- **Omega and Xi, Constraints.ipynb** — Jupyter notebook for defining and calculating constraints in the SLAM process.
- **Landmark Detection and Tracking.ipynb** — Jupyter notebook for detecting and tracking landmarks in the environment.
- **Zip Your Project Files and Submit.ipynb** — Jupyter notebook for preparing and submitting the project files.
- **helpers.py** — Python script containing helper functions for the SLAM implementation.
- **robot_class.py** — Python script defining the robot class and its methods.

---

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

`pip install numpy matplotlib`

---

## Running the Notebooks

1. Clone the repository:
   
  `git clone https://github.com/hamidghasemi69/Simultaneous-Localization-and-Mapping.git`
  
  `cd Simultaneous-Localization-and-Mapping`

2. Open the Jupyter notebooks:
   `jupyter notebook`

3. Follow the instructions in the notebooks to simulate robot movement, define constraints, and detect and track landmarks.

---

## Results

The SLAM implementation successfully enables the robot to navigate and map the `2D` environment, demonstrating the feasibility of `SLAM` techniques in robotics.

---

## Acknowledgements

- `Python Libraries`: Utilized numpy for numerical computations and matplotlib for visualizations.

- `SLAM Algorithms`: Implemented basic SLAM algorithms for educational purposes.


---

## Contact & Contributions

- Author: `Hamid Ghasemi`

- Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.



