# 🚀 Solar System Simulation with Runge-Kutta and GPU Acceleration

This project simulates the motion of planets in the solar system using **numerical integration methods**. It compares **CPU-based** and **GPU-accelerated** implementations of the **Runge-Kutta 4th order (RK4)** algorithm to analyze performance and accuracy.

## 📌 Features

- RK4 numerical integrator for solving Newtonian gravitational motion
- Fetches real vector data from [NASA JPL Horizons](https://ssd.jpl.nasa.gov/horizons/)
- GPU acceleration using [CuPy](https://cupy.dev/)
- Performance benchmarking between CPU and GPU
- Visualization of planetary orbits
- Simulation of JWST orbit

## 🔧 Technologies Used

- Python
- NumPy & CuPy
- Matplotlib
- Astroquery & Astropy
- Jupyter Notebook

## 📊 Project Structure

- `main.ipynb` – CPU and GPU simulation of planetary motion with visualizations
- `README.md` – Overview and usage instructions

## 🧠 Key Concepts

- **N-body simulation**: Computes gravitational forces between multiple celestial bodies.
- **Runge-Kutta 4th order (RK4)**: A numerical method for solving ordinary differential equations.
- **GPU Acceleration**: Offloading parallel computations to GPU for significant speed-up.

## ▶️ How to Run

### Requirements

```bash
pip install numpy cupy matplotlib astroquery astropy
