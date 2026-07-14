# MSc-Project-Codes

This repository contains the Python implementation developed as part of my M.Sc. dissertation.

## Project Overview

This project investigates the use of GARCH(1,1) models for gravitational-wave data analysis under non-stationary detector noise.

The work includes

- waveform detection in white Gaussian noise
- waveform detection in non-stationary noise
- ROC analysis
- Bayesian parameter estimation
- Joint GARCH likelihood
- Analysis using real LIGO detector noise

---

## Repository Structure

notebooks/

01_white_noise_detection.ipynb

02_nonstationary_detection.ipynb

03_simulated_parameter_estimation.ipynb

04_real_ligo_parameter_estimation.ipynb

---

## Software Requirements

Python 3.11+

Packages

- numpy
- scipy
- matplotlib
- emcee
- corner
- numba
- h5py
- statsmodels
- arch

Install using

pip install -r requirements.txt

---

## Data

Real detector noise was obtained from the LIGO Open Science Center (GWOSC).

---

## Author

Sravya K

M.Sc. Physics
