# Dynamical Systems and Bifurcation Analysis using Euler’s Method

🚀 Computational Physics project focused on simulating nonlinear autonomous systems and studying bifurcation behavior using Euler’s Numerical Method in Python. The project analyzes trajectory evolution, stability of fixed points, saddle-node and transcritical bifurcations, and the Duffing oscillator through numerical simulations and graphical visualization.

---

## Topics Covered

- Autonomous Dynamical Systems
- Euler’s Numerical Method
- Fixed Point Analysis
- Stability Analysis
- Saddle-Node Bifurcation
- Transcritical Bifurcation
- Duffing Oscillator
- Scientific Visualization using Matplotlib

---

## Problems Simulated

### 1. Autonomous System

The system studied is:

$$
\dot{x} = \sin(x)
$$

Trajectories are simulated for different initial conditions:

$$
x(0) = \pm1, \pm2
$$

The asymptotic behavior of solutions is analyzed numerically.

---

### 2. Bifurcation Analysis

#### (a) Saddle-Node Bifurcation

The system:

$$
\dot{x} = r - x^2
$$

is simulated for different values of parameter $r$ to observe the saddle-node bifurcation at:

$$
r = 0
$$

---

#### (b) Transcritical Bifurcation

The system:

$$
\dot{x} = rx - x^2
$$

is analyzed numerically to study transcritical bifurcation behavior.

Interactive trajectory visualization using sliders is also implemented.

---

### 3. Duffing Oscillator

The nonlinear system studied is:

$$
\dot{x} = r - \alpha x - \beta x^3
$$

The project investigates:

- Fixed points
- Stability
- Parameter dependence
- Possible bifurcations
- Effect of different values of $\alpha$ and $\beta$

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Numerical integration using Euler’s Method
- Stability and trajectory analysis
- Real-time parameter visualization
- Interactive bifurcation simulations
- Graphical representation of nonlinear dynamics

---

## Observations

- Stable and unstable fixed points emerge depending on parameter values.
- Saddle-node and transcritical bifurcations are clearly observed numerically.
- Small parameter variations significantly affect long-term system behavior.
- The Duffing oscillator exhibits rich nonlinear dynamics and multiple equilibrium states.

---

## Conclusion

This project demonstrates how numerical methods can be used to study nonlinear dynamical systems and bifurcation phenomena. Through trajectory simulations and stability analysis, the project provides insight into the qualitative behavior of autonomous systems and nonlinear oscillators.

---

## How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install dependencies:

```bash
pip install numpy matplotlib jupyter
```

Run the notebook:

```bash
jupyter notebook
```

---
