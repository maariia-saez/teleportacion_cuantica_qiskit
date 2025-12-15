# Análisis de la Teleportación Cuántica con Qiskit

Implementación en Python y Qiskit del trabajo académico **"Análisis Teórico y Experimental de la Teleportación Cuántica: Del Teorema de No-Clonación a la Internet Cuántica"** (2025).

## Contenido

Este repositorio incluye:

- `teleportacion_qiskit.ipynb`: Jupyter Notebook con la implementación completa del protocolo de teleportación cuántica, explicación paso a paso y visualización de resultados.

El notebook está organizado en tres simulaciones principales:

1. **Protocolo ideal**: Verificación teórica del protocolo de teleportación con fidelidad cercana al 100 % en simulador ideal.
2. **Experimento Zeilinger (1997)**: Simulación de las limitaciones de la BSM con óptica lineal, mostrando un éxito probabilístico.
3. **Hardware real (IBM Quantum)**: Ejecución en procesadores cuánticos de IBM para estudiar el efecto del ruido y la fidelidad experimental.

## Requisitos

- Python 3.x
- Qiskit 1.0+
- Qiskit Aer
- Matplotlib
- Cuenta de IBM Quantum (solo necesaria para la Simulación 3)

## Ejecución

1. Abrir `teleportacion_qiskit.ipynb` con Jupyter (por ejemplo, JupyterLab o VS Code).
2. Ejecutar las celdas en orden, comenzando por las de importación y configuración global.
3. La Simulación 3 solo se ejecutará correctamente si hay una cuenta de IBM Quantum configurada en la máquina local.

## Autoras

- **Alicia Elvira Montes Núñez**
- **María Sáez Díaz**

Realizado como parte de la asignatura *Introducción a la Información y la Computación Cuántica* (2025).
