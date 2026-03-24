## 🚀 Rocket Nozzle CFD Simulation (ANSYS Fluent)

This project focuses on the **computational analysis of a rocket nozzle** using **ANSYS Fluent**, aimed at understanding high-speed compressible flow behavior and nozzle performance.

### 📌 Project Overview

* Developed a **3D nozzle model** and performed CFD simulation
* Analyzed **supersonic flow expansion** using an **inviscid, steady-state model**
* Investigated flow characteristics such as:

  * Pressure distribution
  * Velocity variation
  * Temperature gradients

### ⚙️ Simulation Details

* **Solver Type:** Pressure-based, steady-state
* **Flow Model:** Inviscid (compressible flow)
* **Fluid:** Ideal gas (rocket exhaust approximation)
* **Inlet Conditions:**

  * Total Pressure: 9.8 MPa
  * Temperature: 3710 K
* **Outlet Conditions:**

  * Atmospheric pressure (101325 Pa)

### 🔬 Mesh & Convergence

* Mesh Type: Tetrahedral
* Total Cells: ~16,658
* Orthogonal Quality: ~0.247 (acceptable for initial CFD study)
* Solution achieved **full convergence** with residuals below 1e-6

### 📊 Key Outcomes

* Successful simulation of **high-speed nozzle flow expansion**
* Clear visualization of **flow acceleration and thermodynamic changes**
* Validated numerical stability with converged residuals

### 🛠️ Tools Used

* ANSYS Fluent
* Pre-processing (geometry & meshing)
* Post-processing (contours & residual analysis)

### 📁 Contents

* Simulation report (PDF)
* Mesh and setup details
* Contour and residual plots

---

### 💡 Future Improvements

* Include **viscous (turbulence) models** for more realistic results
* Perform **parametric study** on nozzle geometry
* Compare with **analytical/isentropic flow results**

---
