# QComp Oracle Synthesis

<p align="center">
  <img src="https://img.shields.io/badge/Quantum%20Computing-Oracle%20Synthesis-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

<p align="center">
  <b>Quantum oracle synthesis and circuit construction for quantum computing exercises.</b>
</p>

---

## Overview

This repository contains a practical notebook dedicated to **oracle synthesis in quantum computing**.

The main objective is to build, analyze and simulate quantum oracles used in quantum algorithms. The project is structured around a Jupyter notebook that introduces the theoretical ideas, implements the corresponding circuits, and explores their behavior through concrete examples.

This work is part of a quantum computing practical session focused on the construction of Boolean oracles and their implementation as quantum circuits.

---

## Repository Content

```text
QComp-Oracle-Synthesis/
│
├── QComp-TP-4-Oracle.ipynb     # Main Jupyter notebook
├── QComp-TP-4-Oracle.html      # Exported HTML version
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
└── .gitignore
```

---

## Topics Covered

This repository explores several key notions in quantum computing:

* Quantum oracle construction
* Boolean functions encoded as quantum circuits
* Reversible computation
* Ancilla qubits
* Controlled quantum gates
* Circuit synthesis
* Simulation of quantum circuits
* Practical implementation in Python notebooks

---

## Main Notebook

The main file is:

```text
QComp-TP-4-Oracle.ipynb
```

It contains the full practical work, including:

* explanations of oracle-based quantum computation;
* implementation of quantum circuits;
* step-by-step construction of oracle operators;
* simulations and interpretation of results.

An HTML version is also provided for easier reading:

```text
QComp-TP-4-Oracle.html
```

---

## Installation

First, clone the repository:

```bash
git clone https://github.com/karimelhoudaigui/QComp-Oracle-Synthesis.git
cd QComp-Oracle-Synthesis
```

Then create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

```bash
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Notebook

Launch Jupyter:

```bash
jupyter notebook
```

Then open:

```text
QComp-TP-4-Oracle.ipynb
```

You can also use JupyterLab:

```bash
jupyter lab
```

---

## Project Goal

The goal of this project is to understand how a classical Boolean function can be embedded into a quantum computation through an oracle.

In quantum algorithms, oracles are central objects. They allow information about a function to be queried coherently, enabling quantum speedups in algorithms such as:

* Deutsch-Jozsa algorithm
* Grover search
* Simon algorithm
* Bernstein-Vazirani algorithm

This notebook focuses on the practical construction of such objects at the circuit level.

---

## Mathematical Idea

Given a Boolean function

```math
f : \{0,1\}^n \rightarrow \{0,1\}
```

the associated quantum oracle is usually represented as:

```math
U_f : |x\rangle |y\rangle \mapsto |x\rangle |y \oplus f(x)\rangle
```

This transformation must be reversible and unitary, which is why oracle synthesis naturally connects classical logic, reversible computation and quantum circuit design.

---

## Skills Practiced

Through this project, you will practice:

* translating Boolean logic into quantum circuits;
* using controlled gates to encode conditions;
* understanding reversibility constraints;
* simulating quantum circuits;
* interpreting quantum states and measurement outcomes;
* connecting theoretical quantum algorithms with concrete implementations.

---

## Technologies

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Quantum%20Computing-6A0DAD?style=flat-square" />
</p>

---

## Author

**Karim EL HOUDAIGUI**

Double-degree engineering background in **High-Performance Computing** and **Quantum Information**, with interests in numerical simulation, quantum computing, quantum foundations and scientific computing.

Website: [elhoudaiguimath.com](https://elhoudaiguimath.com)

---

## License

This repository is intended for educational and research purposes.

You may adapt the material for learning, teaching or experimentation, provided that proper credit is given.

---

<p align="center">
  <b>Exploring quantum computation one oracle at a time.</b>
</p>
