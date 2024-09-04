# Qiskit_notes_QRNG
A Jupyter notebook documenting my learning journey with Qiskit, including notes and my first project: a Quantum Random Number Generator.

## Documentation of My Qiskit Learning Journey
Welcome to my repository! This project documents my journey into the world of quantum computing using Qiskit. This repository includes a Jupyter Notebook that captures my learning process, notes, and my first hands-on project: a Quantum Random Number Generator (QRNG).

## Overview
As part of my exploration into quantum computing, I embarked on a structured learning path using Qiskit, IBM’s open-source quantum computing framework. This repository serves as a comprehensive record of my progress, including theoretical insights, practical coding exercises, and the development of my initial quantum computing project.

## Contents
### Qiskit_Learning_Journey.ipynb: A Jupyter Notebook that documents my learning journey with Qiskit. It includes notes on quantum computing principles, Qiskit tutorials, and reflections on the learning process.

### QRNG_Project: The folder containing my first project—a Quantum Random Number Generator. This project demonstrates the application of quantum principles to generate a random binary value.
## Quantum Random Number Generator (QRNG) Project
### Overview
The QRNG project utilizes quantum computing to produce a random number by applying a Hadamard gate to a qubit and measuring the result. The randomness stems from the quantum superposition principle, where the qubit has an equal probability of being in the 0 or 1 state.
### How It Works
- Circuit Initialization: A quantum circuit is created with one qubit and one classical bit.
- Hadamard Gate Application: The Hadamard gate is applied to the qubit, putting it into a superposition state.
- Measurement: The qubit is measured, and the result is stored in the classical bit.
- Simulation: The circuit is executed using Qiskit’s AerSimulator.
- Result Extraction: The outcome of the measurement is retrieved and converted to a random number (0 or 1).

## Getting Started
### To replicate my work, follow these steps:

#### Clone the Repository:

- Copy code
git clone https://github.com/donabarot/Qiskit_notes_QRNG.git
cd Qiskit_notes_QRNG
Install Required Libraries: Ensure you have the necessary Python packages installed:


- Copy code
pip install qiskit qiskit-aer
Run the QRNG Script: Execute the QRNG script to generate a random number:

- Copy code
python QRNG_Project/qrng.py
Explore the Jupyter Notebook: Open the Qiskit_Learning_Journey.ipynb file to view my notes and reflections on learning Qiskit.

## Future Plans
I am excited to continue exploring quantum computing and Qiskit. Future updates will include more advanced projects and deeper dives into quantum algorithms.

Acknowledgments
Special thanks to the Qiskit community and all the resources that have guided me on this learning journey.

Feel free to explore, contribute, or reach out with any questions or feedback!
