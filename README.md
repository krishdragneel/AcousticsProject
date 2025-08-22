Acoustic Streaming in a Microchannel Cross Section ⚙️
This project investigates 

acoustic streaming, a nonlinear phenomenon that creates a steady fluid flow due to the viscous dissipation of acoustic waves. This study focuses on modeling and analyzing acoustic streaming in a two-dimensional microchannel cross section. Using both 


analytical theory and numerical simulation with COMSOL Multiphysics, the project explores the generation of acoustic streaming rolls, temperature gradients, and particle transport. The results demonstrate how these microscale effects can be used for particle manipulation in lab-on-a-chip and biomedical applications.


🔬 Key Concepts

Acoustic Streaming: The steady flow induced in a fluid due to the nonlinear interaction of acoustic waves and viscous effects. It is critical for microfluidic applications that require precise control over fluid and particle motion, such as cell sorting and mixing.



Boundary-Driven Streaming (Rayleigh Streaming): A type of acoustic streaming that is often dominant in microfluidic systems with a standing pressure field. It arises from shear in the viscous boundary layers near rigid walls.



Acoustic Radiation Force: A net force experienced by microparticles in an acoustic field. This force, along with the 

viscous drag force from the streaming flow, determines a particle's trajectory.

💻 Simulation and Modeling
The system modeled is a rectangular microchannel with a width (

W) of 380 µm and a height (H) of 160 µm. The fluid used is water , and the channel is excited at its resonance frequency of 


1.9652 MHz.

The simulation was performed using 

COMSOL Multiphysics and involved several physics interfaces and couplings:



Pressure Acoustics, Frequency Domain: To compute the harmonic acoustic field.


Laminar Flow: To solve for the time-averaged streaming velocity field.


Particle Tracing for Fluid Flow: To evaluate particle trajectories based on acoustic radiation and drag forces.

To improve efficiency, the 

Thermoviscous Boundary Layer Impedance (TVBLI) condition was used to analytically incorporate the effects of the thin viscous and thermal boundary layers, which avoids the need to numerically resolve them.


📈 Key Results and Findings
The simulation results closely matched the analytical predictions, validating the theoretical models.


Acoustic Pressure Field: The simulation confirmed the standing wave pattern predicted by the Helmholtz solution, showing clear pressure nodes and antinodes.



Acoustic Streaming Flow: The simulation reproduced the characteristic quadrupole-like Rayleigh streaming rolls , which are driven by boundary-layer shear stresses.



Particle Trajectories:


Large particles (a=3μm) were primarily influenced by the acoustic radiation force and focused at pressure nodes.



Small particles (a=0.4μm) were dominated by viscous drag and were entrained by the streaming rolls, circulating within them.




Acoustic Heating: Acoustic energy dissipated in the boundary layers resulted in a small temperature rise on the order of millikelvins.


The close match between simulation and theory validates the use of analytical models for predicting acoustic streaming behavior. This study demonstrates how acoustic streaming can be effectively used for particle manipulation, with applications in biomedical diagnostics and cell sorting
