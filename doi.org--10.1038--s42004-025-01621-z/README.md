# Ultrafast probing of isotope-induced explicit symmetry breaking in ethylene

## Overview

This repository contains non-adiabatic molecular dynamics trajectories in `.xyz` format of ethylene cation in D0 and upon excitation to the D1, D2, D3, and D4 excited states.
The simulations were performed using OpenMolcas software (version 22.10-354-g7f2c128).
The computational detail can be found in the "Theoretical methods" section of the article.


> **DOI:** `https://doi.org/10.1038/s42004-025-01621-z`

---

## Data Repository Structure

The data are stored in `https://uncloud.univ-nantes.fr/index.php/s/osFxMk8LbF867Mx` and the repository has the following structure.

```
12C12C_data.tar.gz
└── 12C12C_data/
    ├── D0_trajectories/       # Trajectories initiated from state D0
    ├── D1_trajectories/       # Trajectories initiated from state D1
    ├── D2_trajectories/       # Trajectories initiated from state D2
    ├── D3_trajectories/       # Trajectories initiated from state D3
    └── D4_trajectories/       # Trajectories initiated from state D4

13C12C_data.tar.gz
└── 13C12C_data/
    ├── D0_trajectories/       # Trajectories initiated from state D0
    ├── D1_trajectories/       # Trajectories initiated from state D1
    ├── D2_trajectories/       # Trajectories initiated from state D2
    ├── D3_trajectories/       # Trajectories initiated from state D3
    └── D4_trajectories/       # Trajectories initiated from state D4

13C13C_data.tar.gz
└── 13C13C_data/
    ├── D0_trajectories/       # Trajectories initiated from state D0
    ├── D1_trajectories/       # Trajectories initiated from state D1
    ├── D2_trajectories/       # Trajectories initiated from state D2
    ├── D3_trajectories/       # Trajectories initiated from state D3
    └── D4_trajectories/       # Trajectories initiated from state D4
```

It contains a folder for each isotopologue considered in the study.
Each folder contains `.xyz` files, one per trajectory, with the atomic coordinates at each time step.

---

## Data Description

Each `.xyz` trajectory file follows the standard format:

```
<number of atoms>
<comment line>
C   x1   y1   z1
C   x2   y2   z2
H   x3   y3   z3
H   x4   y4   z4
H   x5   y5   z5
H   x6   y6   z6
```

---

## Citation

If you use this data in your work, please cite:

> Nardi, A. N.; Boyer, A.; Hu, Y.; Loriot, V.; Lépine, F.; Vacher, M.;\* Nandi, S.\* Ultrafast probing of isotope-induced explicit symmetry breaking in ethylene, *Commun. Chem.*, **2025**, *8*, 222. DOI: `https://doi.org/10.1038/s42004-025-01621-z`
