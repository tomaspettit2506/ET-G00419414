# Assessment Summer 25/26 (Year 4️⃣)
**Author:** Tomás Pettit

**Student ID:** G00419414

**Course:** Software Development

**Module:** Emerging Technology 💻

## Overview
This repository contains a complete Python implementation of the difference between classical and quantum algorithms. The assessment is divided into 5 problems covering generate random boolean, classical test, Quantum Oracles, Qiskit, and scaling algorithms.

## Requirements
- `Python 3.8^` (for modern type hints like list[int])

### Dependencies
Install required packages using:

```bash
pip install -r requirements.txt
```
Main dependencies: `numpy` for 32-bit unsigned integer operations and mathematical functions.

## How To Run

### Using Jupyter Notebook
1. Clone this repository: `git clone https://github.com/tomaspettit2506/ET-G00419414.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter notebook`
4. Open `problems.ipynb`
5. Run cells sequentially from top to bottom (without any errors)

**Note:** Cells must be run in order as later problems depend on functions from earlier problems.

## Project Structure
```text
.
├── problems.ipynb      # Main notebook with problem solutions
├── README.md          # This file
├── requirements.txt   # Python package dependencies
└── .gitignore        # Git ignore rules
```

## Problems Implemented

### Problem 1: Generating Random Boolean Functions
Implements a Python function generator that creates random Boolean functions guaranteed to be either constant (always return the same value) or balanced (return True for exactly half the inputs). These functions serve as test cases for the quantum algorithm.

### Problem 2: Classical Testing for Function Type
Develops a classical algorithm to determine whether a mystery Boolean function is constant or balanced by querying it with different inputs. Analyzes the query complexity (worst case: 9 queries for 4-bit functions) to establish a baseline for quantum comparison.

### Problem 3: Quantum Oracles
Implements quantum oracles for all possible single-bit Boolean functions, as required by Deutsch's algorithm. Each oracle is a reversible quantum circuit in Qiskit that encodes a classical Boolean function $f(x)$ as a transformation $(x, y) \rightarrow (x, y \oplus f(x))$, where $\oplus$ is XOR. This ensures reversibility, a requirement for quantum operations.

### Problem 4: Deutsch's Algorithm with Qiskit
[Quantum circuit implementation for single-bit functions]

[Coming Soon]

### Problem 5: Scaling to the Deutsch–Jozsa Algorithm
[Generalizing to four-bit Boolean functions]

[Coming Soon]

## Technologies Used
- Python
- Jupyter Notebook
- Qiskit (Quantum computing framework)
- NumPy
- Matplotlib


## References
- [Deutsch-Jozsa Algorithms | IBM Quantum Platform](https://quantum.cloud.ibm.com/learning/en/modules/computer-science/deutsch-jozsa)
- [Qiskit Documentation](https://www.ibm.com/quantum/qiskit)
- [Qiskit Computating Fundamentals](https://quantum.cloud.ibm.com/learning/en)
- [Classical Information](https://quantum.cloud.ibm.com/learning/en/courses/basics-of-quantum-information/single-systems/classical-information)