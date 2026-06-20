# Quantum AI Exploration

A repository dedicated to my exploration of Quantum AI, where I learn, experiment, and implement concepts at the intersection of quantum computing and artificial intelligence.

## Overview

This repository serves as a personal workspace and portfolio for my journey into Quantum AI. Here you will find:

*   **Learning Materials:** Notes, summaries, and resources I've gathered.
*   **Experiments:** Code snippets, Jupyter notebooks, and small projects exploring quantum machine learning algorithms.
*   **Implementations:** More structured implementations of core Quantum AI concepts.

## Getting Started

### Prerequisites

*   [Python 3.12+](https://www.python.org/downloads/)
*   `pip` and `venv` (bundled with modern Python)

### Installation

1.  Clone the repository:

    ```bash
    git clone <your-repo-url>
    cd "Quantum AI"
    ```

2.  Create and activate a virtual environment:

    ```bash
    # Create the environment
    python -m venv venv

    # Activate it
    # Windows (PowerShell)
    .\venv\Scripts\Activate.ps1
    # macOS / Linux
    source venv/bin/activate
    ```

3.  Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Launch Jupyter and open a notebook:

```bash
jupyter notebook
```

Then start with the **[Quantum AI Basics](Quantum%20AI%20Basics/README.md)** module below.

## Modules

### [Quantum AI Basics](Quantum%20AI%20Basics/README.md)

A guided, hands-on introduction. Work through the notebooks in order:

1. **[Introduction to Quantum Computing](Quantum%20AI%20Basics/01_Introduction_to_Quantum_Computing.ipynb)** — qubits, superposition, measurement, entanglement.
2. **[Quantum Gates and Circuits](Quantum%20AI%20Basics/02_Quantum_Gates_and_Circuits.ipynb)** — the gate set and building circuits.
3. **[Quantum Machine Learning Basics](Quantum%20AI%20Basics/03_Quantum_Machine_Learning_Basics.ipynb)** — train a variational quantum classifier.

## Project Structure

```
Quantum AI/
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
├── Quantum AI Basics/        # Beginner notebooks (start here)
│   ├── README.md
│   ├── 01_Introduction_to_Quantum_Computing.ipynb
│   ├── 02_Quantum_Gates_and_Circuits.ipynb
│   └── 03_Quantum_Machine_Learning_Basics.ipynb
└── venv/                     # Virtual environment (git-ignored)
```

## Technologies Used

- **[Qiskit](https://github.com/Qiskit/qiskit)** + **qiskit-aer** — IBM's quantum computing SDK and simulator
- **[PennyLane](https://pennylane.ai/)** — differentiable quantum programming for quantum machine learning
- **NumPy**, **Matplotlib**, **scikit-learn** — data handling, plotting, and toy datasets
- **Jupyter** — interactive notebooks

## Goals

*   Understand the fundamental principles of quantum computing.
*   Apply quantum computing principles to machine learning and AI algorithms.
*   Build practical and experimental Quantum AI applications.
