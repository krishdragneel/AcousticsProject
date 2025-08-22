<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acoustic Streaming in a Microchannel Cross Section</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        h1 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            text-align: center;
        }
        h2 {
            border-left: 4px solid #3498db;
            padding-left: 10px;
            margin-top: 30px;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            background: #f4f4f4;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        p {
            text-align: justify;
        }
        strong {
            color: #e74c3c;
        }
        .figure {
            text-align: center;
            margin: 20px 0;
        }
        .figure img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .figure-caption {
            font-style: italic;
            font-size: 0.9em;
            color: #777;
            margin-top: 5px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Acoustic Streaming in a Microchannel Cross Section ⚙️</h1>

    <p>This project investigates the phenomenon of <strong>acoustic streaming</strong> in a two-dimensional microchannel cross-section, a steady flow that arises from the interaction of acoustic waves and viscous effects in a fluid. [cite_start]This study combines both <strong>analytical theory</strong> and <strong>numerical simulation</strong> using COMSOL Multiphysics to model and analyze the flow[cite: 6, 7]. [cite_start]The findings have significant implications for <strong>particle manipulation</strong> in lab-on-a-chip and biomedical applications[cite: 8].</p>

    <h2>🔬 Key Concepts</h2>
    <ul>
        [cite_start]<li><strong>Acoustic Streaming:</strong> A steady flow induced in a fluid medium due to the nonlinear interaction of oscillatory acoustic waves and viscous effects[cite: 10]. [cite_start]It is crucial for controlling fluid and particle motion in microfluidic applications such as cell sorting, mixing, and targeted delivery[cite: 11].</li>
        [cite_start]<li><strong>Boundary-Driven Streaming (Rayleigh Streaming):</strong> This type of streaming is often dominant in microfluidic systems with a standing pressure field[cite: 53]. [cite_start]It is caused by the dissipation of acoustic energy in the thin viscous and thermal boundary layers near rigid walls, creating characteristic flow patterns[cite: 12].</li>
        [cite_start]<li><strong>Acoustic Radiation Force:</strong> Microparticles suspended in an acoustic field experience a net force due to acoustic radiation pressure[cite: 56]. [cite_start]This force, along with the <strong>viscous drag force</strong> from the streaming flow, determines a particle's trajectory[cite: 68].</li>
    </ul>

    <h2>💻 Simulation and Modeling</h2>
    [cite_start]<p>The project models a rectangular microchannel with a width ($W$) of 380 µm and a height ($H$) of 160 µm[cite: 186, 187]. [cite_start]The fluid is water, and the channel is excited at its resonance frequency, 1.9652 MHz, to create a horizontal half-wave mode[cite: 217, 219].</p>
    
    [cite_start]<p>The simulation in <strong>COMSOL Multiphysics</strong> used several physics interfaces[cite: 237]:</p>
    <ul>
        [cite_start]<li><strong>Pressure Acoustics:</strong> To compute the harmonic acoustic field[cite: 238].</li>
        [cite_start]<li><strong>Laminar Flow:</strong> To solve the time-averaged second-order streaming velocity field[cite: 239].</li>
        [cite_start]<li><strong>Heat Transfer in Fluids:</strong> To model acoustic heating from viscous dissipation[cite: 240].</li>
        [cite_start]<li><strong>Particle Tracing:</strong> To simulate particle trajectories based on acoustic radiation and drag forces[cite: 241].</li>
    </ul>

    [cite_start]<p>The <strong>Thermoviscous Boundary Layer Impedance (TVBLI)</strong> condition was used to analytically incorporate the effects of thin viscous and thermal boundary layers without numerically resolving them, which significantly reduced computational complexity while maintaining accuracy[cite: 253, 258].</p>

    <h2>📈 Key Results and Findings</h2>
    [cite_start]<p>The simulation results closely aligned with analytical predictions, validating the theoretical models[cite: 16].</p>
    <ul>
        [cite_start]<li><strong>Acoustic Pressure Field:</strong> The simulation confirmed a standing wave pattern with nodes and antinodes, consistent with the analytical Helmholtz equation solution[cite: 292, 348].</li>
        [cite_start]<li><strong>Acoustic Streaming Flow:</strong> The simulation reproduced the characteristic <strong>quadrupole-like Rayleigh streaming rolls</strong>, which are typical of boundary-driven streaming in rectangular geometries[cite: 377].</li>
        <li><strong>Particle Trajectories:</strong>
            <ul>
                [cite_start]<li><strong>Large particles</strong> ($a = 3 \mu$m) were primarily influenced by acoustic radiation forces and focused at pressure nodes[cite: 280, 426].</li>
                [cite_start]<li><strong>Small particles</strong> ($a = 0.4 \mu$m) were dominated by viscous drag and were entrained by the streaming rolls, circulating within them[cite: 281, 458, 460].</li>
            </ul>
        </li>
        [cite_start]<li><strong>Acoustic Heating:</strong> Energy dissipated in the boundary layers caused a small temperature rise on the order of millikelvins, which aligns with analytical expectations[cite: 303, 402, 404].</li>
    </ul>

    <h2>🚀 Conclusion</h2>
    [cite_start]<p>This study successfully demonstrates that a combination of analytical models and numerical simulations can effectively be used to predict and optimize acoustofluidic systems[cite: 474]. [cite_start]The findings highlight how acoustic streaming can be precisely controlled for applications like <strong>biomedical diagnostics, cell sorting, and lab-on-a-chip technologies</strong>[cite: 475].</p>

</div>

</body>
</html>
