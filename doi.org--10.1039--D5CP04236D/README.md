# Excited-state intramolecular proton transfer and competing pathways in 3-hydroxychromone: a non-adiabatic dynamics study

## Overview

This repository contains non-adiabatic molecular dynamics initial conditions and trajectories in `.xyz` format of the 3-hydroxychromone upon excitation to the S1 and S2 excited states.
The simulations were performed using the SHARC software interfaced with GAUSSIAN16.
The computational detail can be found in the "Theoretical methods and computational details" section of the article.


> **DOI:** `https://doi.org/10.1039/D5CP04236D`

---

## Data Repository Structure

The data are stored in `https://uncloud.univ-nantes.fr/index.php/apps/files/files/2479667041?dir=/ATTOP-TEAM/XYZ/doi.org--10.1039--D5CP04236D` and the repository has the following structure.

```
3-hydroxychromone_data.tar.gz
├── Singlet_1
└── Singlet_2
```

The `.tar.gz` archive contains a folder for each excited state (S1 and S2 singlet excited states) from which the dynamics of the molecule considered in the study starts.
In each `Singlet_N` folder there are subfolders named `TRAJ_M` containing the initial condition (in SHARC format) and the non-adiabatic dynamics trajectory in `.xyz` format. 

---

## Data Description

Each `.xyz` trajectory file follows the standard format:

```
<number of atoms>
<comment line>
atom_label1   x1   y1   z1
atom_label2   x2   y2   z2
atom_label3   x3   y3   z3
...
```

---

## Citation

If you use this data in your work, please cite:

> Nardi, A. N.; Vacher, M.;\* *Phys. Chem. Chem. Phys.* **2026**, *28*, 4422-4432. DOI: `https://doi.org/10.1039/D5CP04236D`
