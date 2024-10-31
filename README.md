# Accelerated Design of Microring Lasers with Multi-Objective Bayesian Optimization
This repository contains data and a Jupyter Notebook used for the optimization of growth and geometry parameters for bottom-up grown multi-quantum well (MQW) InP/InAsP microring lasers. By utilizing Bayesian optimization and Design of Experiments techniques, the goal is to streamline the design process and improve device performance.

## Overview:
Multi-quantum well (MQW) microring lasers require precise tuning of various growth and structural parameters to achieve optimal optical properties, including minimized lasing thresholds, specific communication wavelengths, and high yield. BoTorch, utilizing a qNParEGO acquisition function, is employed to conduct multi-objective Bayesian optimization, specifically targeting these objectives.

## Key Features:
- Multi-Objective Bayesian Optimization: Utilizes BoTorch's qNParEGO acquisition function to efficiently explore and exploit the parameter space, targeting multiple objectives simultaneously.
- Principal Component Analysis (PCA) Enhanced Design of Experiment (DoE): PCA is applied to identify patterns and fill in data gaps in the initial dataset, which allows for an informed exploration of growth and geometry parameters.

## Dependencies
- Python 3.8+
- Jupyter Notebook
- BoTorch for Bayesian optimization
- torch for computational backend
- scikit-learn for PCA and dataset handling
- pyDoE for Latin Hypercube Sampling (LHS)
- matplotlib and Seaborn for plotting and visualizations

## Usage
- Installation: Clone this repository and install the required libraries.
- Run Notebook: Open the Jupyter Notebook to start the optimization process.
- Adjust Parameters: Modify dataset, bounds, objectives, and acquisition functions as needed to explore different design goals.

