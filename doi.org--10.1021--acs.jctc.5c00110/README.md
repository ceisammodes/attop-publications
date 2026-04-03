# Automated Selection of Nuclear Coordinates for Reduced Dimensionality Nonadiabatic Dynamics

## Overview

This repository contains non-adiabatic molecular dynamics trajectories in `.xyz` format of:
- *trans*-azomethane upon excitation to the S1 excited state.
- butyrolactone upon excitation to the S2 excited state.
- furanone excitation to the S2 excited state.

used in the study of the automated selection of nuclear coordinates for reduced dimensionality non-adiabatic dynamics.
The simulations were performed using a local modified version of the OpenMolcas software.
The computational detail can be found in the "Computational Details" section of the article.


> **DOI:** `doi.org/10.1021/acs.jctc.5c00110`

---

## Data Repository Structure

The data are stored in `https://uncloud.univ-nantes.fr/index.php/apps/files/files/2479382529?dir=/ATTOP-TEAM/XYZ/doi.org--10.1021--acs.jctc.5c00110` and the repository has the following structure.

```
trans-azomethane.tar.gz
└── trans-azomethane/
    ├── trans-azomethane.Opt.xyz
    ├── trans-azomethane.freq.molden
    └── trans-azomethane_data

butyrolactone.tar.gz
└── butyrolactone/
    ├── butyrolactone.Opt.xyz
    ├── butyrolactone.freq.molden
    └── butyrolactone_data

furanone.tar.gz
└── furanone/
    ├── furanone.Opt.xyz
    ├── furanone.freq.molden
    └── furanone_data
```

It contains a folder for each molecule considered in the study.
Each folder contains:
- an `.Opt.xyz` and `.freq.molden` file which contain the equilibrium geometry of the molecule and the frequencies computed at the FC point.
- a data folder containing the `.xyz` trajectories of the full-dimensional ensemble.

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

> Delmas, V.; Nardi, A. N.; Merritt, I. C. D.; Ferté, A.; Galván, I. Fdez.; Vacher, M.;\* *J. Chem. Theory Comput.* **2025**, *21*, 13, 6611-6621. DOI: `https://doi.org/10.1021/acs.jctc.5c00110`
