# QComp - Oracle Synthesis

This repository contains the fourth QComp coding session on oracle synthesis for quantum algorithms, with a focus on reversible circuits, fixed-point arithmetic, polynomial evaluation, and the HHL inversion oracle approximation.

## Contents

- `QComp-TP-4-Oracle.ipynb`: main Jupyter notebook for the lab session.
- `QComp-TP-4-Oracle.html`: exported HTML version of the notebook.
- `requirements.txt`: Python dependencies needed to run the notebook.

## Topics Covered

1. Reversible circuit simulation with custom Boolean wires.
2. Half-adder and full-adder construction.
3. Ripple-carry addition in V-form.
4. Reversible multiplication.
5. Signed fixed-point representation.
6. Fixed-point addition, multiplication, powers, and polynomial evaluation.
7. Taylor approximation of the HHL inversion operator.
8. Circuit-level comparison between exact, Taylor, and fixed-point approximations.

## Setup

Create a virtual environment, then install the dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook QComp-TP-4-Oracle.ipynb
```

or use VS Code with the Jupyter extension.

## Notes

The notebook is educational and self-contained. Some circuits become large quickly because they explicitly synthesize reversible arithmetic gates.

## Author

Karim El Houdaigui
