# Geometric Control Toolbox (Basile–Marro)

This repository contains a MATLAB toolbox for **Geometric Control Theory**, based on the classical framework developed by **G. Basile and G. Marro**.

The toolbox provides computational routines for the analysis and synthesis of linear time-invariant (LTI) systems using geometric methods, with a focus on subspace-based characterizations.

> ⚠️ **Disclaimer**  
> This repository is **not an original theoretical contribution**.  
> It is a **software implementation and reorganization** of tools and algorithms developed by Basile & Marro, intended for educational, research, and reproducibility purposes.

---

## Features

The toolbox includes routines for:

- Controlled invariant subspaces
- Conditioned invariant subspaces
- Output-nulling subspaces
- Input-containing subspaces
- Disturbance decoupling problems
- Friend matrices computation
- Structural decompositions of LTI systems
- Support for continuous-time systems

All computations are performed using standard MATLAB matrix operations.

---

## References

The toolbox is based on the theory presented in:

- G. Basile, G. Marro,  
  *Controlled and Conditioned Invariants in Linear System Theory*,  
  Prentice Hall, 1992.

Users are strongly encouraged to consult the book for the **theoretical background and proofs**.

---

## Requirements

- MATLAB (tested on recent versions)
- Control System Toolbox (recommended)

---

## Installation

Clone the repository and add it to your MATLAB path:

```matlab
addpath(genpath('path_to_repository'))
savepath
