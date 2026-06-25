# Quantum AI Basics

A hands-on, beginner-friendly introduction to quantum computing and quantum machine learning. Each notebook mixes plain-English explanations with runnable code (Qiskit and PennyLane) and finishes with a summary and references.

## Notebooks

| # | Notebook | What you'll learn |
|---|----------|-------------------|
| 00 | [Subatomic Particles — Explained in Depth](00_Subatomic_Particles_Explained.ipynb) | What matter is made of: atoms, quarks, leptons, the Standard Model, forces, quantum behaviour, and real-world uses |
| 01 | [Introduction to Quantum Computing](01_Introduction_to_Quantum_Computing.ipynb) | Qubits, superposition, measurement, and entanglement (Bell state) with Qiskit |
| 02 | [Quantum Gates and Circuits](02_Quantum_Gates_and_Circuits.ipynb) | Single- and multi-qubit gates, statevectors, and building circuits |
| 03 | [Quantum Machine Learning Basics](03_Quantum_Machine_Learning_Basics.ipynb) | Variational quantum circuits — train a quantum classifier with PennyLane |
| 04 | [Machine Learning & AI Foundations](04_Classical_ML_and_AI_Foundations.ipynb) | Classical ML/AI: supervised learning, neural nets, gradient descent — and how they map to QML |
| 05 | [Quantum Hardware & Chip Breakthroughs](05_Quantum_Hardware_and_Chip_Breakthroughs.ipynb) | Real machines & 2024–2026 news: Google Willow, Microsoft Majorana 1/2, IBM's roadmap |
| 06 | [The Future of Quantum AI](06_The_Future_of_Quantum_AI.ipynb) | How the field will develop: timelines, use cases, barren plateaus, AI⇄quantum co-evolution |
| 07 | [Quantum Algorithms In-Depth](07_Quantum_Algorithms_In_Depth.ipynb) | Complexity classes (BQP), the QFT, phase estimation, Shor & Grover (runnable), VQE/QAOA, and error correction (surface vs. qLDPC) |

Work through them in order — each builds on the previous one.

> ⚠️ **Notebooks 05 & 06 cover fast-moving news** (current as of June 2026). Qubit counts and roadmaps change every few months — check the cited official sources for the latest.

## Setup

From the repository root:

```bash
# activate your virtual environment first (see the root README)
pip install -r requirements.txt
jupyter notebook
```

Then open the `Quantum AI Basics` folder and start with notebook 00.

> **Tip:** Each notebook has a `%pip install ...` cell at the top so it can also run standalone (e.g. in Google Colab). Comment it out after the first run.

## Libraries used

- **[Qiskit](https://github.com/Qiskit/qiskit)** — IBM's quantum computing SDK (notebooks 01, 02 & 07)
- **[PennyLane](https://pennylane.ai/)** — differentiable quantum programming for QML (notebook 03)
- **scikit-learn** — classical machine learning (notebook 04)
- NumPy & Matplotlib — data and plotting throughout
