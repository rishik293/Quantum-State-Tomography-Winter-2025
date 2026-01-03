# Machine Learning for Quantum State Tomography

**Project Status:** Week 1 Complete
**Student:** Rishik
**Enrollment number:** 24116107

## Project Overview
This project focuses on reconstructing the density matrix of unknown quantum states using measurement data. The goal is to compare standard Linear Inversion techniques with Machine Learning approaches (Neural Networks) in later weeks.

## Week 1: Foundation & Data Generation
**Objective:** Build a scalable tomography workflow using Pauli Projective Measurements.

### Key Features
- **Simulation:** Uses `Qiskit Aer` to simulate quantum circuits.
- **Data Generation:** Created a dataset of **Standard States** ($|0\rangle, |1\rangle, |+\rangle...$) and **Random Quantum States**.
- **Reconstruction:** Implemented **Linear Inversion** to estimate density matrices from measurement probabilities.
- **Analysis:** Analyzed the impact of shot noise on reconstruction fidelity (Fidelity vs. Shots).

### Files
- `Week1_QST_Assignment.ipynb`: Complete source code for data generation and reconstruction.
- `Week1_Report.pdf`: Technical report summarizing the methodology and results.
- `week1_data.npy`: The generated dataset containing measurement counts and ground truth states.

### Tech Stack
- Python, Qiskit, NumPy, Plotly
