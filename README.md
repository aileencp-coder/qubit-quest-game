# Qubit Quest — The Quantum Escape Room

**Team 3Q — Quantum Quest Qubits**

*Think Quantum. Solve the Impossible.*

## Project Overview

Qubit Quest is an interactive educational game that introduces fundamental quantum computing concepts through three hands-on missions. Built with Python, Streamlit, Qiskit, and Qiskit Aer, the application allows players to predict quantum measurement outcomes, execute quantum circuits, and visualize results without requiring quantum hardware.

## Missions

### 1. Superposition Lab
Apply a Hadamard gate to a qubit initialized in the zero state and explore the expected 50/50 measurement distribution.

### 2. Entanglement Chamber
Create a Bell state using a Hadamard gate and a CNOT gate. Observe the correlated measurement outcomes 00 and 11.

### 3. Measurement Lab
Explore how an RY rotation changes measurement probabilities at different angles, including 0°, 90°, and 180°.

## Technologies Used

- Python
- Streamlit
- Qiskit
- Qiskit Aer
- Matplotlib

## Features

- Interactive mission selection
- Quantum circuit simulation
- Player predictions and immediate feedback
- Measurement count graphs
- Adjustable simulation shots and rotation angle
- Score tracking across three missions

## Installation

Install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed by Streamlit in your browser.

## Learning Outcomes

Players explore superposition, entanglement, quantum gates, and probabilistic measurement through interactive simulations.

## Team

**3Q — Quantum Quest Qubits**

Project: Qubit Quest — The Quantum Escape Room

## Disclaimer

This is an educational prototype that uses a quantum simulator. It does not require physical quantum hardware.
