
---

# Acoustic Streaming in a Microchannel Cross Section ⚙️

This project investigates **acoustic streaming**, a nonlinear phenomenon that generates a steady fluid flow due to the viscous dissipation of acoustic waves. The study focuses on modeling and analyzing acoustic streaming in a **two-dimensional microchannel cross section**. Using both **analytical theory** and **numerical simulations with COMSOL Multiphysics**, the project explores the generation of streaming rolls, temperature gradients, and particle transport.

The results demonstrate how these microscale effects can be leveraged for **particle manipulation** in lab-on-a-chip and **biomedical applications**.

---

## 🔬 Key Concepts

* **Acoustic Streaming**
  A steady flow induced in a fluid due to the nonlinear interaction of acoustic waves and viscous effects. It plays a crucial role in microfluidic systems for applications like **cell sorting**, **mixing**, and **fluid transport**.

* **Boundary-Driven Streaming (Rayleigh Streaming)**
  A type of streaming that arises in systems with a **standing pressure field**, driven by shear forces in the viscous boundary layers near rigid walls.

* **Acoustic Radiation Force**
  A net force acting on microparticles in an acoustic field. Combined with **viscous drag**, it governs particle motion and positioning.

---

## 💻 Simulation and Modeling

* **Geometry:**
  A **rectangular microchannel** with width **W = 380 µm** and height **H = 160 µm**.

* **Fluid:**
  Water.

* **Excitation Frequency:**
  **1.9652 MHz** (resonance frequency).

* **Software:**
  **COMSOL Multiphysics** using the following physics interfaces:

  * **Pressure Acoustics, Frequency Domain** – Computes the harmonic acoustic field.
  * **Laminar Flow** – Solves for the time-averaged streaming velocity field.
  * **Particle Tracing for Fluid Flow** – Evaluates particle trajectories based on radiation and drag forces.

* **Boundary Layer Modeling:**
  The **Thermoviscous Boundary Layer Impedance (TVBLI)** condition was used to account for thin viscous and thermal boundary layers analytically, avoiding computationally expensive meshing.

---

## 📈 Key Results and Findings

* **Acoustic Pressure Field**
  Simulations matched the Helmholtz-based analytical solution, showing standing wave patterns with clear **pressure nodes and antinodes**.

* **Acoustic Streaming Flow**
  Simulations reproduced the characteristic **Rayleigh streaming rolls** (quadrupole-like structures) driven by boundary-layer shear.

* **Particle Trajectories**

  * **Large particles (a = 3 μm):**
    Dominated by **acoustic radiation force**; focused at **pressure nodes**.
  * **Small particles (a = 0.4 μm):**
    Dominated by **viscous drag**; **entrained** by streaming rolls and circulated within them.

* **Acoustic Heating**
  Small temperature rise (\~millikelvins) due to energy dissipation in the boundary layers.

---

## ✅ Conclusions

* Simulation results closely matched analytical predictions, validating the theoretical models.
* The study demonstrates the effective use of **acoustic streaming for particle manipulation** in microfluidic systems.
* Applications include **biomedical diagnostics**, **cell sorting**, and **lab-on-a-chip technologies**.

---

