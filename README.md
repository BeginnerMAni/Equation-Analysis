# Non-Linear Equation Analysis and Sensitivity Project

## Overview
This project focuses on solving and analyzing a non-linear equation. It includes root finding, stability analysis, graph plotting, and sensitivity analysis of the equation's parameters.

## Features
- **Expression Construction:** Dynamically constructs the non-linear equation based on user inputs.
- **Root Solving:** Finds equilibrium points of the equation and analyzes their stability using derivatives.
- **Graphical Representation:** Plots the equation and marks stable/unstable roots.
- **Sensitivity Analysis:** Computes the sensitivity of the output to changes in parameters such as κ (kappa), m, ρ (rho), σ (sigma), and C.

## Requirements
The script requires the following Python libraries:
- `control`
- `matplotlib`
- `numpy`
- `sympy`

You can install these dependencies using pip:
```bash
pip install control matplotlib numpy sympy
```

## Usage
1. Clone the repository or download the script file.
2. Run the script in a Python environment.
3. Enter the required parameter values when prompted:
   - κ (kappa)
   - m
   - ρ (rho)
   - σ (sigma)
   - C

The script will:
- Display the constructed equation.
- Solve and display the roots (equilibrium points) along with their stability status.
- Plot the graph of the function and perform sensitivity analysis.

## Outputs
- **Graph of f(Φ):** A plot showing the function behavior, with roots marked as stable or unstable.
- **Sensitivity Analysis Bar Chart:** Displays the relative contribution of each parameter to the output variance.
- **Console Output:** Detailed information on roots, stability, and sensitivity results.

## Example
Input values:
```
κ = 0.5
m = 1.0
ρ = 0.2
σ = 0.8
C = 1.5
```

Output:
- Equation: Constructed and displayed in the terminal.
- Roots: List of equilibrium points with stability analysis.
- Graphs: Displayed for visual inspection.

## License
This project is open source and distributed under the MIT License.

## Author
Developed as part of a mathematics-focused project for solving non-linear equations. Feel free to contribute or reach out for further improvements!

