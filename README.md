# Subject-Independent-SSVEP-Classification-Using-Single-Channel-Dry-EEG
This repository contains the MATLAB implementation of a subject-independent Steady-State Visual Evoked Potential (SSVEP)-based Brain–Computer Interface (BCI) framework using a low-cost single-channel dry EEG system.

    # Subject-Independent SSVEP Classification Using Single-Channel Dry EEG

## Overview
This repository contains MATLAB implementation of a subject-independent SSVEP classification framework using:

- FBCCA-inspired spectral feature fusion
- ReliefF feature selection
- PSO-optimized ensemble learning
- SHAP/LIME explainability
- LOSO validation

## Requirements
- MATLAB R2024a
- Signal Processing Toolbox
- Statistics and Machine Learning Toolbox
- Wavelet Toolbox

## Dataset
Dataset link:

https://data.mendeley.com/datasets/px9dpkssy8/draft?a=7140665d-a0f0-40b2-a9fd-a731d21b6222
## How to Run

1. Open MATLAB
2. Run:
main.m

## Output
The framework generates:
- PSD figures
- FFT spectra
- PSO convergence curves
- Confusion matrices
- SHAP/LIME analysis

## Validation Protocol
Leave-One-Subject-Out (LOSO)

