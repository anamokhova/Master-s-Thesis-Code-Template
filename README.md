# 🎓 Gauss Quadrature-Based Green’s Function Evaluation

**Supporting code for Master's Thesis:**  
*Fast Evaluation of the Acoustic, Half-Space Impedance Green’s Function*  
University of Zurich – Institute of Mathematics  
Author: Anastasia Mokhova

---

## 📘 Overview

This repository contains a Python implementation of numerical methods for evaluating the **acoustic Green’s function** in a half-space with impedance boundary conditions.

The computational strategy is based on **Gauss-Legendre**, **Gauss-Laguerre**, and **hybrid quadrature** techniques designed for highly accurate and efficient numerical integration.

These methods support theoretical findings presented in the corresponding Master’s Thesis.

---

## 📁 Contents

- `Master's Thesis_Code template.ipynb`:  
  Jupyter notebook containing the full implementation, utility functions, and examples.

- `upper bound function_quadrature_comparison.ipynb`:  
  Computes and visualizes theoretical error bounds for each quadrature method for the upper bound function of  $\psi_\nu$.  
  Estimates constants to validate convergence rates and predict the number of required quadrature nodes.

- `psi_nu_quadrature_comparison.ipynb`:  
  Applies Gauss-Legendre, hp-adaptive Gauss-Legendre, and Gauss-Laguerre quadrature to compute the integral $\psi_\nu$.  
  Estimates constants to validate convergence behavior, predict node requirements, and compare the practical performance of each method.


---

## ⚙️ Requirements

Python 3.8+

### Required Libraries

Install with:

```bash
pip install numpy scipy sympy matplotlib mpmath

