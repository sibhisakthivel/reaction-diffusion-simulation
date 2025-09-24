# Reaction–Diffusion Simulation

This model is an implementation of a **finite-difference reaction–diffusion model** to simulate the emergence of natural patterns, such as cheetah fur markings. It applies numerical techniques (finite differences, Laplace operator) to solve a set of coupled **reaction–diffusion equations**. By modeling the interaction of an **activator**, **substrate**, and **inhibitor**, the simulation reproduces emergent spatial patterns over time. This project connects to chemistry, biology, and physics by demonstrating how **nonlinear dynamics and diffusion processes** give rise to complex natural phenomena.

---

## Techniques Used
- Random initialization of concentrations on a 2D grid.
- Finite-difference approximation of the **Laplacian operator**.
- Iterative updates of **reaction–diffusion equations**:
  - Activator self-amplification and substrate consumption.
  - Substrate and inhibitor dynamics with decay and saturation terms.
- Cyclic **boundary conditions** in both spatial dimensions.
- Time-stepping simulation on a 3D grid \((x, y, t)\).
- Visualization with `matplotlib` and `seaborn` heatmaps.

---

## Files
- `reaction-diffusion-simulation.ipynb` → Jupyter notebook with simulation code and visualizations.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sibhisakthivel/reaction-diffusion-simulation.git
   cd reaction-diffusion-simulation

2. Install dependencies:

    ```bash
    pip install numpy matplotlib seaborn

3. Open the notebook:

    ```bash
    jupyter notebook reaction-diffusion-simulation.ipynb

4. Run all cells to generate heatmaps showing pattern evolution over time.