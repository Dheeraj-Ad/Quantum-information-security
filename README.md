# 🔐 Quantum Information Security

## Overview
This project explores **quantum-based approaches to information security**, combining classical cryptographic principles with quantum algorithms and simulation.  
The goal is to demonstrate how **quantum computing concepts** (superposition, entanglement, and qubits) can enhance or challenge modern cryptographic systems.

Key Features:
- Implementation of **quantum key distribution (QKD)** concepts in Python.
- Simulation of **quantum-resistant cryptographic algorithms**.
- Comparative analysis between **classical encryption** and **quantum-secure methods**.
- Visualization of quantum states and security outcomes.

---

## Tech Stack
- **Programming Language:** Python 3.10+
- **Libraries:**
  - `qiskit` – Quantum circuits and simulation
  - `numpy`, `scipy` – Mathematical foundations
  - `matplotlib`, `plotly` – Visualization
  - `cryptography` – Classical encryption for comparison

---

## Project Structure

---

## Methodology
1. **Quantum Key Distribution (QKD)**  
   - Implemented BB84 protocol using Qiskit.  
   - Simulated eavesdropping detection via quantum state collapse.  

2. **Quantum-Resistant Cryptography**  
   - Tested lattice-based algorithms and post-quantum schemes.  
   - Benchmarked against classical RSA/AES.  

3. **Visualization**  
   - Plotted qubit states, entanglement, and key exchange outcomes.  
   - Compared error rates under different noise models.  

---

## Results
- Demonstrated secure key exchange using QKD with >95% accuracy in ideal conditions.  
- Showed vulnerabilities of RSA under simulated quantum attacks.  
- Highlighted post-quantum algorithms as viable replacements for classical encryption.  

---

## References
- Nielsen, M. A., & Chuang, I. L. (2010). *Quantum Computation and Quantum Information*. Cambridge University Press.  
- Shor, P. W. (1994). *Algorithms for Quantum Computation: Discrete Logarithms and Factoring*.  
- Qiskit Documentation (2025). https://qiskit.org/documentation/  
- NIST Post-Quantum Cryptography Project (2025). https://csrc.nist.gov/projects/post-quantum-cryptography  

---

## Demo
Run the simulation:
```bash
python src/main.py
