# Quantum-Basics

A collection of foundational quantum computing notebooks built with Qiskit.

## Notebooks

| Notebook | What you learn | Expected output |
|:--|:--|:--|
| [Superposition and Bell States](Super%20Position%20and%20Bell-State/Superposition_and_Bell_States.ipynb) | How a Hadamard gate puts a qubit in superposition, and how Hadamard + CNOT entangle two qubits into the \|Φ⁺⟩ Bell state | Superposition: about 50% `0` / 50% `1` (e.g. `{'0': 502, '1': 498}`). Bell state: about 50% `00` / 50% `11`, never `01` or `10` (e.g. `{'00': 506, '11': 494}`) |

Each notebook includes circuit diagrams, simulator results from 1000 shots, and an explanation of why the counts come out the way they do. Counts vary slightly between runs.

## Setup

Install the requirements, preferably in a separate Python environment:

```bash
pip install -r requirements.txt
jupyter notebook
```

Circuits run locally on the Qiskit Aer simulator, so no IBM Quantum account is needed.

## License

MIT
