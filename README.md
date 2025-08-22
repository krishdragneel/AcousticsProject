# Acoustic Streaming in a Microchannel Cross Section ⚙️

[cite_start]This project investigates **acoustic streaming**, a nonlinear phenomenon that creates a steady fluid flow due to the viscous dissipation of acoustic waves[cite: 5]. [cite_start]This study focuses on modeling and analyzing acoustic streaming in a two-dimensional microchannel cross section[cite: 6]. [cite_start]Using both **analytical theory** and **numerical simulation** with COMSOL Multiphysics, the project explores the generation of acoustic streaming rolls, temperature gradients, and particle transport[cite: 7]. [cite_start]The results demonstrate how these microscale effects can be used for particle manipulation in lab-on-a-chip and biomedical applications[cite: 8].

***

### 🔬 Key Concepts
* [cite_start]**Acoustic Streaming**: The steady flow induced in a fluid due to the nonlinear interaction of acoustic waves and viscous effects[cite: 10]. [cite_start]It is critical for microfluidic applications that require precise control over fluid and particle motion, such as cell sorting and mixing[cite: 11].
* [cite_start]**Boundary-Driven Streaming (Rayleigh Streaming)**: A type of acoustic streaming that is often dominant in microfluidic systems with a standing pressure field[cite: 53]. [cite_start]It arises from shear in the viscous boundary layers near rigid walls[cite: 51].
* [cite_start]**Acoustic Radiation Force**: A net force experienced by microparticles in an acoustic field[cite: 56]. [cite_start]This force, along with the **viscous drag force** from the streaming flow, determines a particle's trajectory[cite: 68].

***

### 💻 Simulation and Modeling
[cite_start]The system modeled is a rectangular microchannel with a width ($W$) of **380 µm** and a height ($H$) of **160 µm**[cite: 186, 187]. [cite_start]The fluid used is water [cite: 210][cite_start], and the channel is excited at its resonance frequency of **1.9652 MHz**[cite: 218].

[cite_start]The simulation was performed using **COMSOL Multiphysics** and involved several physics interfaces and couplings[cite: 236, 237, 242]:
* [cite_start]**Pressure Acoustics, Frequency Domain**: To compute the harmonic acoustic field[cite: 238].
* [cite_start]**Laminar Flow**: To solve for the time-averaged streaming velocity field[cite: 239].
* [cite_start]**Particle Tracing for Fluid Flow**: To evaluate particle trajectories based on acoustic radiation and drag forces[cite: 241].

[cite_start]To improve efficiency, the **Thermoviscous Boundary Layer Impedance (TVBLI)** condition was used to analytically incorporate the effects of the thin viscous and thermal boundary layers, which avoids the need to numerically resolve them[cite: 253, 258].

***

### 📈 Key Results and Findings
[cite_start]The simulation results closely matched the analytical predictions, validating the theoretical models[cite: 16].

* [cite_start]**Acoustic Pressure Field**: The simulation confirmed the standing wave pattern predicted by the Helmholtz solution, showing clear pressure nodes and antinodes[cite: 290, 348].
* [cite_start]**Acoustic Streaming Flow**: The simulation reproduced the characteristic **quadrupole-like Rayleigh streaming rolls** [cite: 296, 377][cite_start], which are driven by boundary-layer shear stresses[cite: 378]. 
* **Particle Trajectories**:
    * [cite_start]**Large particles** ($a = 3 \mu$m) were primarily influenced by the acoustic radiation force and focused at pressure nodes[cite: 280, 426].
    * [cite_start]**Small particles** ($a = 0.4 \mu$m) were dominated by viscous drag and were entrained by the streaming rolls, circulating within them[cite: 281, 458, 460].
* [cite_start]**Acoustic Heating**: Acoustic energy dissipated in the boundary layers resulted in a small temperature rise on the order of millikelvins[cite: 303, 402].

[cite_start]The close match between simulation and theory validates the use of analytical models for predicting acoustic streaming behavior[cite: 313]. [cite_start]This study demonstrates how acoustic streaming can be effectively used for particle manipulation, with applications in biomedical diagnostics and cell sorting[cite: 475].
