# Clinical Agreement in Wearable Technologies: A Bayesian Approach
This repository contains the code, data, and documentation for the descriptive project on the clinical validation of wearable devices (respiratory rate in COPD and heart rate). The analysis transitions from traditional frequentist metrics to a probabilistic Bayesian hierarchical framework.

## Repository Structure
* `/data`: Cleaned datasets and a link to the confidential dataset.
* `/code_r`: Scripts for pre-processing, exploratory analysis, and hierarchical Bayesian modelling (`brms`, `INLA`).
* `/app_python`: Code for the amortised Bayesian inference (`BayesFlow`) and the interactive web application.
* `/docs`: Final project report (PDF).

## Requirements and Installation
To reproduce the analysis or run the prototype, the following environments are required:
* R and RStudio.
* Packages: `tidyverse`, `brms`, `INLA`.
* Python 3.8 or higher.
* Packages: `streamlit`, `bayesflow`, `pandas`.

## Authors: 
Carla Jiménez Argudo, Isaac Gimeno Gimeno, Michele Romero Calero, Marta Martínez Martínez and Fernanda de Paula Gonçalves.
