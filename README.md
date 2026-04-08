
# ATTOP publications
This work is licensed under a
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

## Automated Selection of Nuclear Coordinates for Reduced Dimensionality Nonadiabatic Dynamics
V. Delmas, A. N. Nardi, I. C. D. Merritt, A. Ferté, I. Fdez. Galván and M. Vacher
J. Chem. Theory Comput. 21, 13, 6611–6621 (2025)
[https://doi.org/10.1021/acs.jctc.5c00110](doi.org/10.1021/acs.jctc.5c00110)
[ArXiv](https://arxiv.org/abs/2509.09329) and [HAL](https://hal.science/hal-05221538/) links.

Poor scaling of dynamics simulations with number of dimensions is currently a major limiting factor in the simulation of photochemical processes. In this work, we investigate ways to reduce the dimensionality of many-atom systems with a view toward enhancing computational efficiency while maintaining accuracy. Using mixed quantum-classical Trajectory Surface Hopping (TSH) simulations of three photoreactive molecules - trans-azomethane (tAZM), butyrolactone (Bulac), and furanone (Fur) - we explore two different dimensionality reduction techniques: Principal Component Analysis (PCA) and Normal Mode Variance (NMV). Dynamics simulations are run in full dimensionality and reduced dimensionality, employing either PCA or NMV, and the impact of the dimensionality reduction on selected electronic and geometric properties of the dynamics is evaluated. For all three molecules, both PCA and NMV can be used to select lower-dimensional spaces in which the full-dimensionality dynamics results are reproduced. PCA reduction outperforms NMV in all systems, allowing for a more significant dimensionality reduction without loss of accuracy. The improved accuracy of PCA is, for tAZM, mostly seen in the electronic properties while for both Fur and Bulac the advantage is clear in the ring-opening reaction itself as well. The present approach opens routes to simulation of larger photochemically relevant systems, through the use of automated dimensionality reduction, avoiding human bias.

## Ultrafast probing of isotope-induced explicit symmetry breaking in ethylene
A. N. Nardi, A. Boyer, Y. Hu, V. Loriot, F. Lépine, M. Vacher and S. Nandi
Commun. Chem. 8, 222 (2025)
[https://doi.org/10.1038/s42004-025-01621-z](https://doi.org/10.1038/s42004-025-01621-z)
[ArXiv](https://arxiv.org/abs/2509.09268) and [HAL](https://hal.science/ILM/hal-05263331v1) links.

Symmetry governs nature’s laws, yet many of the natural phenomena occur due to the breakdown of symmetry. Here, we show how isotope-induced inversion symmetry breaking influences ultrafast photoisomerization processes in ethylene. Using extreme ultraviolet pump – near infrared probe time-of-flight mass spectrometry, we find that replacing one of the carbon atoms in ethylene with a 13C isotope leads to twice-faster structural relaxation via ethylene-ethylidene isomerization in the photo-excited molecular cation. Advanced trajectory surface hopping calculations incorporating the nuclear symmetry of the molecular systems, reveal that it arises from the mixing of different normal modes in the isotope-substituted species, interactions otherwise forbidden by symmetry. Although the mixing does not alter the symmetry of the electronic Hamiltonian, it modifies that of the nuclear Hamiltonian, causing explicit symmetry breaking. This facilitates efficient intra-molecular vibrational energy redistribution, lowering the isomerization yield. Our findings offer opportunities to use isotope-induced nuclear symmetry breaking to control the outcome of light-molecule interactions across ultrafast timescales.

## Photodissociation of Cr(CO)4bpy: a non-adiabatic dynamics investigation
B. Ciborowski and M. Vacher  
J. Comput. Chem. 46, e70021 (2025)  
[https://doi.org/10.1002/jcc.70021](https://doi.org/10.1002/jcc.70021)  
[ArXiv](https://doi.org/10.48550/arXiv.2501.07322) and [HAL](https://hal.science/hal-04892446) links.  

Carbonyl complexes of d6 metals with an α-diimine ligand exhibit both emission and ligand-selective photodissociation from MLCT states. Studying this photodissociative mechanism is challenging for experimental approaches due to an ultrafast femtosecond timescale and spectral overlap of multiple photoproducts. The photochemistry of a prototypical system Cr(CO)4bpy is investigated with non-adiabatic dynamic simulations. Obtained 86 fs lifetime of the bright S3 state and 13% quantum yield are in good agreement with experimental data. The present simulations suggest a ballistic mechanism of photodissociation, which is irrespective of the occupied electronic state. This is in contrast to the previously established mechanism of competitive intersystem crossing and dissociation. Selectivity of axial photodissociation is shown to be caused by the absence of an avoided crossing in the equatorial direction.

## Signature of attochemical quantum interference upon ionization and excitation of an electronic wavepacket in fluorobenzene
A. Ferté, D. Austin, A. A. Johnson, F. McGrath, J. P. Malhado, J. P. Marangos and M. Vacher  
Phys. Rev. Lett. 133, 203201 (2024)  
[https://doi.org/10.1103/PhysRevLett.133.203201](https://doi.org/10.1103/PhysRevLett.133.203201)  
[ArXiv](https://doi.org/10.48550/arXiv.2309.08269) and [HAL](https://hal.science/hal-04892444v1) links.  

Ultrashort pulses can excite or ionize molecules and populate coherent electronic wave packets, inducing complex dynamics. In this Letter, we simulate the coupled electron-nuclear dynamics upon ionization to different electronic wave packets of (deuterated) benzene and fluoro-benzene molecules, quantum mechanically and in full dimensionality. In fluoro-benzene, the calculations unravel both interstate and intrastate quantum interferences that leave clear signatures of attochemistry and charge-directed dynamics in the shape of the autocorrelation function. The latter are in agreement with experimental high-harmonic spectroscopy measurements of benzenes and fluoro-benzene.

## Simulating Attochemistry: Which Dynamics Method to Use?
T. Tran, A. Ferté and M. Vacher  
J. Phys. Chem. Lett. 15, 3646-3652 (2024)  
[https://doi.org/10.1021/acs.jpclett.4c00106](https://doi.org/10.1021/acs.jpclett.4c00106)  
[ArXiv](https://doi.org/10.48550/arXiv.2405.17276) and [HAL](https://hal.science/hal-04590060v1) links.  

Attochemistry aims to exploit the properties of coherent electronic wavepackets excited via attosecond pulses to control the formation of photoproducts. Such molecular processes can, in principle, be simulated with various nonadiabatic dynamics methods, yet the impact of the approximations underlying the methods is rarely assessed. The performances of widely used mixed quantum-classical approaches, Tully surface hopping, and classical Ehrenfest methods are evaluated against the high-accuracy DD-vMCG quantum dynamics. This comparison is conducted for the valence ionization of fluorobenzene. Analyzing the nuclear motion induced in the branching space of the nearby conical intersection, the results show that the mixed quantum-classical methods reproduce quantitatively the average motion of a quantum wavepacket when initiated on a single electronic state. However, they fail to properly capture the nuclear motion induced by an electronic wavepacket along the derivative coupling, the latter originating from the quantum electronic coherence property, key to attochemistry.

## Dissociation and Isomerisation Following Ionization of Ethylene: Insights from Nonadiabatic Dynamics Simulations
L. Fransén, T. Tran, S. Nandi and M. Vacher  
J. Phys. Chem. A 128, 1457-1465 (2024)  
[https://doi.org/10.1021/acs.jpca.3c06512](https://doi.org/10.1021/acs.jpca.3c06512)  
[ArXiv](https://arxiv.org/html/2405.17266) and [HAL](https://hal.science/hal-04499942v1) links.  

Photoionized and electronically excited ethylene C2H4+ can undergo H-loss, H2-loss, and ethylene–ethylidene isomerization, where the latter entails a hydrogen migration. Recent pioneering experiments with few-femtosecond extreme ultraviolet pulses and complementary theoretical studies have shed light on the photodynamics of this prototypical organic cation. However, no theoretical investigation based on dynamics simulations reported to date has described the mechanisms and time scales of dissociation and isomerization. Herein, we simulate the coupled electron–nuclear dynamics of ethylene following vertical ionization and electronic excitation to its four lowest-lying cationic states. The electronic structure is treated at the CASSCF level, with an active space large enough to describe bond breaking and formation. The simulations indicate that dissociation and isomerization take place mainly on the cationic ground state and allow the probing of previous hypotheses concerning the correlation between the photochemical outcome and the traversed conical intersections. The results, moreover, support the long-standing view that H2-loss may occur from the ethylidene form. However, the ethylene–ethylidene isomerization time predicted by the simulations is considerably longer than those previously inferred from indirect experimental measurements.

## Which Electronic Structure Method to Choose in Trajectory Surface Hopping? Azomethane as a Case Study
T. V. Papineau, D. Jacquemin and M. Vacher  
J. Phys. Chem. Lett. 15, 636-643 (2024) [https://doi.org/10.1021/acs.jpclett.3c03014](https://doi.org/10.1021/acs.jpca.3c06512)  
[ArXiv](https://arxiv.org/abs/2405.17271) and [HAL](https://hal.science/hal-04590057) links.  

Nonadiabatic dynamics simulations have become a standard approach to explore photochemical reactions. Such simulations require underlying potential energy surfaces and couplings between them, calculated at a chosen level of theory, yet this aspect is rarely assessed. Here, in combination with the popular trajectory surface hopping dynamics method, we use a high-accuracy XMS-CASPT2 electronic structure level as a benchmark for assessing the performances of various post-Hartree–Fock methods (namely, CIS, ADC(2), CC2, and CASSCF) and exchange–correlation functionals (PBE, PBE0, and CAM-B3LYP) in a TD-DFT/TDA context, using the isomerization around a double bond as test case. Different relaxation pathways are identified, and the ability of the different methods to reproduce their relative importance and time scale is discussed. The results show that multireference electronic structure methods should be preferred, when studying nonadiabatic decay between excited and ground states. If not affordable, TD-DFT with TDA and hybrid functionals and ADC(2) are efficient alternatives but overestimate the nonradiative decay yield and thus may miss deexcitation pathways.

## Sensitivity of Kß mainline X-ray emission to structural dynamics in iron photosensitizer
J. Rogvall, R. Singh, M. Vacher and M. Lundberg  
Phys. Chem. Chem. Phys. 25, 10447-10459 (2023) [https://doi.org/10.1039/D2CP05671B]()  
[ArXiv](https://arxiv.org/abs/2405.15615v1) and [HAL](https://hal.science/hal-04273596) links.  

Photochemistry and photophysics processes involve structures far from equilibrium. In these reactions, there is often strong coupling between nuclear and electronic degrees of freedom. For first-row transition metals, Kβ X-ray emission spectroscopy (XES) is a sensitive probe of electronic structure due to the direct overlap between the valence orbitals and the 3p hole in the final state. Here the sensitivity of Kβ mainline (Kβ1,3) XES to structural dynamics is analyzed by simulating spectral changes along the excited state dynamics of an iron photosensitizer [FeII(bmip)2]2+ [bmip = 2,6-bis(3-methyl-imidazole-1-ylidine)-pyridine], using both restricted active space (RAS) multiconfigurational wavefunction theory and a one-electron orbital-energy approach in density-functional theory (1-DFT). Both methods predict a spectral blue-shift with increasing metal–ligand distance, which changes the emission intensity for any given detection energy. These results support the suggestion that the [FeII(bmip)2]2+ femtosecond Kβ XES signal shows oscillations due to coherent wavepacket dynamics. Based on the RAS results, the sensitivity to structural dynamics is twice as high for Kβ compared to Kα, with the drawback of a lower signal-to-noise ratio. Kβ sensitivity is favored by a larger spectral blue-shift with increasing metal–ligand distance and larger changes in spectral shape. Comparing the two simulations methods, 1-DFT predicts smaller energy shifts and lower sensitivity, likely due to missing final-state effects. The simulations can be used to design and interpret XES probes of non-equilibrium structures to gain mechanistic insights in photocatalysis.
