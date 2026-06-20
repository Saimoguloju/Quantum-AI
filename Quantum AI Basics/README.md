# Quantum AI Basics

A hands-on, beginner-friendly introduction to quantum computing and quantum machine learning. Each notebook mixes plain-English explanations with runnable code (Qiskit and PennyLane) and finishes with a summary and references.

## Notebooks

| # | Notebook | What you'll learn |
|---|----------|-------------------|
| 01 | [Introduction to Quantum Computing](01_Introduction_to_Quantum_Computing.ipynb) | Qubits, superposition, measurement, and entanglement (Bell state) with Qiskit |
| 02 | [Quantum Gates and Circuits](02_Quantum_Gates_and_Circuits.ipynb) | Single- and multi-qubit gates, statevectors, and building circuits |
| 03 | [Quantum Machine Learning Basics](03_Quantum_Machine_Learning_Basics.ipynb) | Variational quantum circuits — train a quantum classifier with PennyLane |

Work through them in order — each builds on the previous one.

## Setup

From the repository root:

```bash
# activate your virtual environment first (see the root README)
pip install -r requirements.txt
jupyter notebook
```

Then open the `Quantum AI Basics` folder and start with notebook 01.

> **Tip:** Each notebook has a `%pip install ...` cell at the top so it can also run standalone (e.g. in Google Colab). Comment it out after the first run.

## Libraries used

- **[Qiskit](https://github.com/Qiskit/qiskit)** — IBM's quantum computing SDK (notebooks 01 & 02)
- **[PennyLane](https://pennylane.ai/)** — differentiable quantum programming for QML (notebook 03)
- NumPy, Matplotlib, scikit-learn for data and plotting
