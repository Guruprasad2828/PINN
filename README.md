# 2D Heat Equation using Physics-Informed Neural Networks (PINN) with Validation via NASTRAN

This project demonstrates how to solve the **2D heat transfer equation** using **Physics-Informed Neural Networks (PINNs)** and compares the results against high-fidelity simulations from **NASTRAN** to validate accuracy.

---

##  Objective

- To use PINNs for solving the 2D steady/transient heat equation over a defined domain.
- To simulate the same problem in NASTRAN and validate the neural network’s predictions.
- To visualize and compare the temperature distribution using 2D contour plots.

---

##  What is a PINN?

Physics-Informed Neural Networks combine the power of deep learning with physical laws (like differential equations). Instead of relying only on data, they learn to satisfy the underlying physics — in this case, the 2D heat equation.

---

## Tools & Technologies

- **Python** (NumPy, PyTorch/TensorFlow, Matplotlib)
- **PINN Framework** (custom implementation or libraries like DeepXDE)
- **NASTRAN** (for FEM simulation and validation)
- **Matplotlib/Seaborn** (for plotting 2D contours)

---

##  Problem Setup

- **Domain**: 2D rectangular region (user-defined)
- **Equation**: 2D heat equation (steady-state or time-dependent)
- **Boundary Conditions**: Dirichlet or Neumann (as per setup)
- **Validation**: Simulation results from NASTRAN

---

##  Results

- The PINN model learns the temperature distribution over the domain.
- 2D contour plots from PINN and NASTRAN show **high correlation**.
- Errors are minimal, indicating that PINNs can be reliable tools for heat transfer problems.





