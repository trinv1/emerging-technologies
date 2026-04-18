# Emerging Technologies Assignment

This repository contains a Jupyter Notebook project for module **Emerging Technologies** assignment implemented in **Python**. The main notebook is:

- `problems.ipynb`

The notebook explores the **Deutsch** and **Deutsch–Jozsa** quantum algorithms using **Qiskit**, showing how quantum computation can determine whether Boolean functions are **constant** or **balanced** more efficiently than classical methods.

## What the notebook covers

The notebook is structured as a sequence of problems and explanations. It includes:

- generation of random Boolean functions that are either constant or balanced
- classical testing to determine function type
- construction of one-bit quantum oracles for Deutsch’s algorithm
- implementation of Deutsch’s algorithm in Qiskit
- extension to the Deutsch–Jozsa algorithm for four-bit Boolean functions
- construction of quantum oracles from classical functions
- explanation of key concepts such as:
  - superposition
  - phase kickback
  - interference
  - measurement

The notebook combines short theory sections, commented Python code, and simulated quantum circuit outputs.

## Technologies used

- Python 3.12+
- Jupyter Notebook
- Qiskit
- Qiskit Aer

## Repository contents

- `problems.ipynb` - main submission notebook
- `README.md` - repository overview and setup instructions
- `requirements.txt` - required Python packages
- `.gitignore` - ignored files for repository cleanliness

## How to clone and run the notebook

Clone the repository:

**Clone notebook:** git clone https://github.com/trinv1/emerging-technologies

**Install dependenices:** pip install -r requirements.txt

**Start up notebook:** jupyter notebook problems.ipynb

## References

The implementation and conceptual explanations of the classical query problem, as well as the Deutsch and Deutsch–Jozsa algorithms, were informed by official IBM Quantum Learning materials:

- [IBM Quantum Learning – Deutsch Algorithm](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-algorithm)
- [IBM Quantum Learning – Deutsch–Jozsa Algorithm](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-jozsa-algorithm)

Additional sources were used to support conceptual understanding:

- [Oracle (Black-box function)](https://quantumcomputing.stackexchange.com/questions/4625/what-exactly-is-an-oracle/4626#4626)
- [Quantum Superposition](https://scienceexchange.caltech.edu/topics/quantum-science-explained/quantum-superposition)
- [Deutsch Algorithm (Lecture Notes)](https://www.cl.cam.ac.uk/teaching/1920/QuantComp/Quantum_Computing_Lecture_7.pdf)
- [Constructive and Destructive Interference](https://www.phys.uconn.edu/~gibson/Notes/Section5_2/Sec5_2.htm)