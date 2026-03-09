# Modelling Complex Systems – IDC 621

This repository contains computational models developed as part of the **IDC 621: Modelling Complex Systems** course. The aim of this project is to study how complex collective behavior can emerge from simple local interactions using numerical simulations.

The repository currently includes implementations of two well-known models in complex systems.

---

## 1. Cellular Automaton Model for Laser Dynamics

This model simulates laser dynamics using a **cellular automaton framework**. The system evolves on a discrete grid where each cell represents the state of a laser element. Local interaction rules govern excitation, photon emission, and relaxation processes.

The model demonstrates how **collective laser behavior** and temporal patterns can emerge from simple local update rules.

Key ideas explored:

- Cellular automata in physical systems  
- Local interaction rules and emergent behavior  
- Modeling excitation and photon dynamics in lasers  

---

## 2. Kuramoto Model for Synchronization

The Kuramoto model describes **synchronization in a population of coupled oscillators**. Each oscillator has its own natural frequency but interacts with others through sinusoidal coupling.

The simulations in this repository explore:

- Time evolution of oscillator phases  
- Emergence of synchronization  
- Order parameter dynamics  
- Synchronization transitions for different frequency distributions (Gaussian, Lorentzian, Laplace)

Visualizations included:

- Evolution of the synchronization order parameter \( r(t) \)
- Phase distribution on the unit circle
- Synchronization transition \( r_\infty \) vs coupling strength \( K \)

---

## Tools and Libraries

The simulations are implemented in **Python** using:

- `NumPy` for numerical computation  
- `Matplotlib` for visualization  

---

## Course Information

**Course:** IDC 621 – Modelling Complex Systems  


---


## Author

Project developed as part of the coursework for **IDC 621 – Modelling Complex Systems**.

**Submitted by AMARNATH (MS22070)**
