# The Hubble Tension: A Critical Literature Review

A critical literature review examining the Hubble tension, its observational foundations, possible systematic uncertainties, and proposed directions for resolving the discrepancy.

## Overview

The Hubble tension refers to the discrepancy between measurements of the present-day expansion rate of the Universe obtained through different observational approaches.

This review examines the problem from both observational and methodological perspectives, with particular attention to:

- CMB-based measurements
- The local distance ladder
- Cepheid calibration uncertainties
- Independent and non-ladder measurements
- The ladder-vs-non-ladder interpretation
- Proposed theoretical explanations
- Future observational tests

The review critically discusses three central works:

1. Perivolaropoulos (2024)
2. Mörtsell et al. (2022)
3. Riess et al. (2022)

## Reproducibility

This repository contains the data and Python/Jupyter notebooks used to reproduce the figures presented in the literature review.

The workflow is:

**Data → Jupyter Notebook → Figure**

## Repository Structure

```text
Hubble-tension-literature-review/
│
├── data/
│   ├── h0_gaussian_posteriors_fig4_data.csv
│   ├── h0_late_universe_fig3_data.csv
│   ├── h0_representative_measurements_fig1_data.csv
│   └── mortsell_2022_fig2_data.csv
│
├── figures/
│   ├── figure1_representative_H0_measurements.png
│   ├── mortsell_2022_fig2_reproduced.png
│   ├── figure3_late_universe_H0.png
│   └── figure4_gaussian_H0_posteriors.png
│
├── notebooks/
│   ├── 01_representative_h0.ipynb
│   ├── 02_mortsell_calibration.ipynb
│   ├── 03_late_universeh0.ipynb
│   └── 04_h0_posteriors.ipynb
│
├── paper/
│   └── Literature Review ( edited ).pdf
│
├── references/
│   └── references.bib
│
├── .gitignore
└── README.md
