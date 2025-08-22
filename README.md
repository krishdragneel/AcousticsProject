
Acoustic Streaming in a Microchannel Cross Section ⚙️
This project investigates the phenomenon of 

acoustic streaming in a two-dimensional microchannel cross-section, a steady flow that arises from the interaction of acoustic waves and viscous effects in a fluid. This study combines both 


analytical theory and numerical simulation using COMSOL Multiphysics to model and analyze the flow. The findings have significant implications for 


particle manipulation in lab-on-a-chip and biomedical applications.

🔬 Key Concepts

Acoustic Streaming: A steady flow induced in a fluid by the nonlinear interaction of oscillatory acoustic waves and viscous effects. It's crucial for controlling fluid and particle motion in microfluidic applications like cell sorting and targeted delivery.



Boundary-Driven Streaming (Rayleigh Streaming): This is the dominant type of acoustic streaming in confined spaces like microchannels. It is caused by the dissipation of acoustic energy in the thin viscous and thermal boundary layers near rigid walls, creating characteristic flow patterns.






Acoustic Radiation Force: Microparticles suspended in an acoustic field experience a net force due to acoustic radiation pressure. This force, along with the 

viscous drag force from the streaming flow, determines a particle's trajectory.


💻 Simulation and Modeling
The project models a rectangular microchannel with a width (

W) of 380 µm and a height (H) of 160 µm. The fluid is water, and the channel is excited at its resonance frequency, 1.9652 MHz, to create a horizontal half-wave mode.



The simulation in COMSOL Multiphysics used several physics interfaces:


Pressure Acoustics: To compute the acoustic field.


Laminar Flow: To compute the steady streaming velocity field.


Heat Transfer in Fluids: To model acoustic heating from viscous dissipation.


Particle Tracing: To simulate particle trajectories based on acoustic radiation and drag forces.

The 

Thermoviscous Boundary Layer Impedance (TVBLI) condition was used to analytically incorporate the effects of thin viscous and thermal boundary layers without numerically resolving them, which significantly reduced computational complexity while maintaining accuracy.


📈 Key Results and Findings
The simulation results closely aligned with analytical predictions, validating the theoretical models.




Acoustic Pressure Field: The simulation confirmed a standing wave pattern with nodes and antinodes, consistent with the analytical Helmholtz equation solution.



Acoustic Streaming Flow: The simulation reproduced the characteristic quadrupole-like Rayleigh streaming rolls, driven by boundary-layer shear stresses. * 


Particle Trajectories:


Large particles (a=3μm) were primarily influenced by acoustic radiation forces and focused at pressure nodes.     * 


Small particles (a=0.4μm) were dominated by viscous drag and were entrained by the streaming rolls, circulating within them. * 



Acoustic Heating: Energy dissipation in the boundary layers caused a small temperature rise on the order of millikelvins, which aligns with analytical expectations.


🚀 Conclusion
This study successfully demonstrates that a combination of analytical models and numerical simulations can effectively be used to predict and optimize acoustofluidic systems. The findings highlight how acoustic streaming can be precisely controlled for applications like 

biomedical diagnostics, cell sorting, and lab-on-a-chip technologies
