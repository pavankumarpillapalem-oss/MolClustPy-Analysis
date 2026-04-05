# MolClustPy-Analysis: EGFR and Nephrin Signaling Dynamics

This repository contains a quantitative analysis of multivalent biomolecular clustering using the MolClustPy framework.

## Project Overview
This study investigates how molecular valency and ligand concentration influence the steady-state distribution of signaling complexes in two biological systems:
1. EGFR (Epidermal Growth Factor Receptor): Modeling early signaling events based on the Blinov (2006) model.
2. Nephrin-Nck-NWASP: A high-valency clustering model used to study molecular stoichiometry.

## Technical Analysis and Methodology
The analysis extends beyond basic simulation by incorporating the following:
* Weighted Mean Cluster Size: Calculation of average cluster size weighted by molecular occupancy to better represent signaling platform density.
* Steady-State Verification: Simulations were extended to t=30s to ensure the system reached thermodynamic equilibrium.
* Statistical Comparisons: Analysis of the largest signaling platforms to compare the clustering capacity of EGFR versus the Nephrin-Nck-NWASP system.

## Key Repository Files
* EGFR_model.ipynb: Primary analysis notebook containing statistical calculations and visualizations.
* test_dataset/: Contains processed summary statistics (pyStat) while excluding heavy raw simulation data.
