# Biological Dynamics Simulations

This repository contains Python implementations and analyses of various biological dynamical systems from HW 4, exploring population genetics, predator-prey dynamics, oscillatory behaviors, chaos, and gene regulatory networks.

## Contents

1. **Mutation Dynamics in Mice**
   - ODE: `P' = 2*P*(1-P)*(1-3*P)`
   - Analysis of fixed points, stability, and long-term behavior
   - Python simulation with `solve_ivp`  

2. **Turkey-Quail Population Dynamics**
   - ODE System:
     ```
     T' = 24*T - 2*T^2 - 3*T*Q
     Q' = 15*Q - Q^2 - 3*T*Q
     ```
   - Nullcline and equilibrium analysis
   - Stability evaluation and vector field visualization  

3. **Limit Cycles and Oscillatory Behavior**
   - Identification of stable and unstable limit cycles
   - Visualization of attractors and repellers  

4. **Oscillations in Biology**
   - Examples include predator-prey cycles and circadian melatonin production
   - Analysis of stable, unstable, and neutral oscillatory states  

5. **Chaos**
   - Lorenz system demonstration
   - Deterministic yet sensitive dynamics with differing initial conditions  

6. **Gene Regulatory Networks**
   - ODE models: e.g., `dx_i/dt = β x_j / (1 + x_j^n) - γ x_i`
   - Discussion of stochastic and SDE approaches  

7. **Lac Operon Dynamics**
   - ODE: `dx/dt = (a + x^2)/(1 + x^2) - r*x`
   - Analysis of steady states, bistability, and bifurcation plots
   - Trajectory simulations under varying parameters 
