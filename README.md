An exploration of Hamiltonian neural networks, (an idea introduced in https://arxiv.org/pdf/1906.01563) for the purposes of simulating three systems: a simple harmonic oscillator, the duffing oscillator and the Hénon-Heiles system.

I compared the HNN with a more traditional neural network (one that attempts to approximate the derivatives of the canonical coordinates), and found the HNN tends to be better at precisely simulating these systems over long time horizons.

A more extensive treatment of the project and the results is available (in spanish) at `reporte.pdf`.

Requirements: `torch`, `numpy`, `matplotlib`, `scipy`
