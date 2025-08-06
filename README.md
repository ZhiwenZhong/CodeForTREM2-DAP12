# CodeForTREM2-DAP12
**Unraveling the Molecular Dance: Insights into TREM2/DAP12 Complex Formation in Alzheimer’s Disease through Molecular Dynamics**

This repository contains scripts and analysis workflows associated with the paper:  
**Zhong Z., Ulmschneider M.B., Lorenz C.D. (2024). Unraveling the Molecular Dance: Insights into TREM2/DAP12 Complex Formation in Alzheimer’s Disease through Molecular Dynamics. *ACS Omega*.**  
DOI: [10.1021/acsomega.4c03060](https://pubs.acs.org/doi/10.1021/acsomega.4c03060)

---

## Overview
The study investigates the molecular mechanisms underlying the association between **TREM2** and **DAP12**, two key proteins implicated in Alzheimer's disease, using **all-atom molecular dynamics (MD) simulations**. We explore:
- Complex formation dynamics of TREM2-DAP12 in lipid bilayers.
- Impact of Alzheimer’s-related mutations on structural stability and interaction patterns.
- Key interfacial residues and hydrogen bonding networks stabilizing the complex.

---

## Repository Contents
- **`input_files/`**  
  System setup files (GROMACS-compatible topology, coordinates).
- **`scripts/`**  
  Python scripts for:
  - Trajectory processing (using MDAnalysis).
  - Hydrogen bond analysis.
  - RMSD/RMSF calculations.
  - Contact map generation.
- **`analysis_notebooks/`**  
  Jupyter notebooks for advanced visualization and analysis.
- **`figures/`**  
  Example plots and data figures generated from the analysis.

---

## Requirements
- **GROMACS** (version ≥ 2021)
- **Python 3.x** with:
  - `MDAnalysis`
  - `NumPy`
  - `Matplotlib`
  - `Pandas`
  - `Seaborn`

---
