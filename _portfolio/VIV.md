---
title: Aeroelastic Analysis
subtitle: Dynamic Simulation & Signal Processing
image: assets/img/portfolio/aero-preview.jpg # This will be your card image
alt: Aeroelastic Analysis Simulation
caption:
  title: Aeroelastic Analysis
  subtitle: Limit Cycle Study
  category: Numerical Simulation
---

[← Back to Showcase](index.html)

# Dynamic Analysis of an Aeroelastic System

## 1. Project Objective
The main objective of this study was to model a mechanical system subjected to non-linear aerodynamic forces. The analysis focuses on evaluating system stability and investigating the onset of self-excited vibrations.

## 2. Methodology
I developed numerical models to integrate the governing equations of motion using Python/C++. To analyze the system's response under different parameter configurations, time-history signals were processed using signal processing techniques. Specifically, the Fast Fourier Transform (FFT) was implemented to extract dominant frequencies, and the Frequency Response Function (FRF) was computed to characterize the system behavior.

## 3. Results & Visualization
The phase space plot and the corresponding Poincaré map are presented below, clearly illustrating the steady-state periodic behavior of the system.

![Poincaré Map](poincare-map.png)

Below is the dynamic animation showing the evolution of the aeroelastic system over time:

![Aeroelastic Simulation Animation](simulation.gif)

## 4. Conclusions
The numerical results confirm that once the system exceeds a specific critical flow velocity, it undergoes a bifurcation leading to stable Limit Cycle Oscillations (LCO), as evidenced by the trajectory convergence in the phase portrait.

---
*Disclaimer: The projects, models, and simulations presented in this portfolio are intended solely for academic and illustrative purposes. The numerical data and results are not certified and should not be used for real-world industrial or commercial engineering applications.*
