# Quantum Teleportation Analysis with Qiskit

Python and Qiskit implementation of the academic work **"Análisis Teórico y Experimental de la Teleportación Cuántica: Del Teorema de No-Clonación a la Internet Cuántica" (Theoretical and Experimental Analysis of Quantum Teleportation: From the No-Cloning Theorem to the Quantum Internet)** (2025).

## Contents

This repository includes:

- `teleportacion_qiskit.ipynb`: Jupyter Notebook containing the complete implementation of the quantum teleportation protocol, step-by-step explanation, and visualization of results.

The notebook is organized into three main simulations:

1. **Ideal Protocol**: Theoretical verification of the teleportation protocol with fidelity close to 100% on an ideal simulator.
2. **Zeilinger Experiment (1997)**: Simulation of BSM (Bell State Measurement) limitations using linear optics, demonstrating probabilistic success.
3. **Real Hardware (IBM Quantum)**: Execution on IBM quantum processors to study the effect of noise and experimental fidelity.

## Requirements

- Python 3.x  
- Qiskit 1.0+  
- `qiskit-ibm-runtime`  
- Matplotlib  
- IBM Quantum Account (only required for Simulation 3)

Recommended installation:

```bash
pip install qiskit qiskit-ibm-runtime matplotlib
```


## Usage

1. Open `teleportacion_qiskit.ipynb` with Jupyter (e.g., JupyterLab or VS Code).  
2. Run cells in order, starting with the import and global configuration cells.  
3. Simulation 3 will only execute correctly if an IBM Quantum account is configured on the local machine.

## Authors

- **Alicia Elvira Montes Núñez**  
- **María Sáez Díaz**

Created as part of the *Introducción a la Información y la Computación Cuántica (Introduction to Quantum Information and Computing)* course (2025).
