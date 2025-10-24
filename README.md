# OCTAHEDRAL NORMAL & SHEAR STRESSES | PRINCIPAL STRESS & PRINCIPAL PLANE

## 📘 Project Overview

This MATLAB-based GUI tool is developed to analyze **3D Stress States** of an element and visualize both:
1. **Octahedral Normal and Shear Stresses**, and  
2. **Principal Stresses and Principal Planes**.

It provides an **interactive visualization** of the stress tensor, along with computed stress components and 3D representations for better understanding of stress transformation and failure criteria in solids.

---

## ⚙️ Features

### 🧩 1. Octahedral Normal and Shear Stress GUI
- Accepts a **3D Stress Tensor** as input (`σxx`, `σyy`, `σzz`, `σxy`, `σyz`, `σzx`).
- Computes:
  - Principal Stresses  
  - Octahedral Normal Stress  
  - Octahedral Shear Stress  
- Visualizes:
  - 3D stress element with all normal and shear stress components  
  - Octahedral stress surface (σ_oct and τ_oct)  

### 🧮 2. Principal Stress and Principal Plane GUI
- Computes **Principal Stresses** and their **Directions** from a given 3D stress tensor.
- Displays:
  - Magnitudes and direction cosines of each principal stress.
  - 3D visualization of:
    - Original stress element  
    - Rotation to principal plane  
    - Element subjected to principal stresses only  

--- 

## GUI Preview:
![Principal Stress and Principal Plane](gui%20preview/principle_stress.png)

![Octahedral Normal and Shear Stress](gui%20preview/octahedral_stress.png)

---

## 🧠 Concepts Used
- 3D Stress Tensor Representation  
- Stress Transformation Equations  
- Eigenvalue and Eigenvector computation for Principal Stresses  
- Octahedral Shear Stress Theory (von Mises)  
- 3D Vector Geometry Visualization using MATLAB  

---

## 💻 Technologies Used
- **MATLAB GUI (App Designer / GUIDE)**  
- **3D Plotting and Visualization**  
- **Matrix Algebra and Eigenvalue Decomposition**  

---

## 📈 Applications
- Solid mechanics and elasticity studies  
- Stress analysis of 3D structures  
- Educational visualization for Theory of Elasticity  
- Validation of FEM stress results  

---

## 🧾 Author
**Jayant Lodhi (2024210009)**  

---

