# open-string-worldsheet-sim
Relativistic Open String: Transverse Oscillations

Numerical simulation and animation of transverse vibrational modes on an open relativistic bosonic string with free endpoints (Neumann boundary conditions)

Interactive Simulation
Run and interact with the animated worldsheet solution directly in your browser:
https://colab.research.google.com/drive/1-rHTOQMdDlqSlEW3pxOvV9NABjtHDfrP?usp=sharing 
Physics Context & Equations of Motion
In Barton Zwiebach's A First Course in String Theory, the transverse coordinates of an open relativistic string moving in flat spacetime obey the wave equation with free boundary conditions:
- Boundary Conditions: Neumann boundary conditions at endpoints (sigma = 0, pi), enforcing vanishing momentum flow off string ends
- Mode Expansion: Superposition of transverse oscillation modes (n = 1, 2, 3) governed by:
  X(tau, sigma) = x + (p / (pi * T)) * tau + sumₙ (Aₙ * cos(n * tau) * cos(n * sigma))
- Tech Stack: Python 3, NumPy, Matplotlib (ArtistAnimation / JSHTML)
