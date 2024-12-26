# RPM

Rock Physics Models (RPM):
This repository contains implementations of various rock physics models for predicting elastic moduli, performing pore aspect ratio inversion, and conducting sensitivity analyses. The models included are:

KT (Kuster-Toksoz Model)

SCA (Self-Consistent Approximation)

DEM (Differential Effective Medium)

SCA-DEM Hybrid Model

Repository Overview
The repository is organized into the following Python notebooks, each focusing on a specific functionality:

Min_est.ipynb:
Estimation of matrix elastic moduli and data filtering based on Hashin-Shtrikman bounds.

Alp.ipynb:
Computation of a single pore aspect ratio for elastic moduli modeling in wells.

RPM_com.ipynb:
Comparative analysis of different rock physics models.

Inv_alp.ipynb:
Inversion of pore aspect ratios for well log data.

RPM_sen.ipynb:
Sensitivity analysis of elastic moduli predictions with respect to pore aspect ratios.

Wallula.xlsx:
Contains well log responses for the Wallula well, used as input data for the provided scripts.

This code is developed by Nitin Nagarkoti, rersearch scholar in Indian Institute of Technology Roorkee.
