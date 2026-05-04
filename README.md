# CT Reconstruction using Inverse Problems

## Overview
This project focuses on 2D and 3D CT reconstruction using inverse problem formulations and regularization techniques. The goal is to study and improve reconstruction quality under noisy and ill-posed conditions.

The implementation is based on Python and the Operator Discretization Library (ODL), and includes both synthetic and real data experiments.

---

## Methods

The following approaches are implemented and evaluated:

- Filtered Back Projection (FBP)
- Huber regularization
- Parameter studies for regularization strength

The project explores reconstruction behavior in both 2D and 3D settings, with a focus on noise robustness and reconstruction quality.

---

## Implementation

- Python (NumPy, SciPy)
- ODL (Operator Discretization Library)
- Jupyter notebooks for experiments and visualization

Reconstruction pipelines are implemented for:
- Synthetic test cases
- Real 3D CT data

---

## Results

- Comparison of classical and regularized reconstruction methods  
- Analysis of noise sensitivity and parameter selection  
- Visualization of reconstructed slices in 2D and 3D  

---

## Notes

- Large datasets are excluded from the repository  
- Code can be run using synthetic data or small test cases  
- GPU acceleration may be required for full 3D reconstruction  

---

## About ODL

This project uses [ODL](https://github.com/odlgroup/odl), a Python library for solving inverse problems by discretizing operators on function spaces in a mathematically consistent way.
