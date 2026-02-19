This repository contains the code for the paper titled "Predicting and optimizing aromatics yield-selectivity trade-off in zeolite-catalyzed biomass fast pyrolysis using machine learning"

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Data preparation](#data-preparation)
- [Model training](#training)

# Overview

This repository contains the codes and dataset to train models for using the Random forest surrogate model coupled with the NSGA-II Optimizer.  
This repository contains the following:

* The main jupyter notebook whihc contains the codes used to develop the predicitve model and optimizer for the research project.
* For the notebook, we include the curated dataset in clean Excel sheets which are labelled correspondingly
* Necessary instructions to run the model and expected outcome are provided as comments in the notebook.

# System Requirements

## Hardware requirements
The code can run on any standard computer and does not require GPUs or clusters.

## Software requirements
The package has been tested on the following systems:
+ Windows 11 Pro for Workstations with 64-bit operating system, x64-based processor

### Python

A Python version of 3.6 or above is recommended. Most of the code is developed using standrad library packages including:

* Pandas 2.0.3 
* Numpy1.24.3 
* Scikit-learn 1.3.0
* Tensorflow 2.12.1
* Shap 0.40.0
* pymoo

## Installation guide

The codes can also be run on an exisiting environment provided the above listed packages are systemically installed using pip or conda commands.

## Data preparation

We provide the clean and labelled curated data as Excel sheets titled for both the notebooks. 
For the notebook titled "RF_Uncertainty_Parity.ipynb" use the excel sheet titled "curated_data_no_outlier" 
For the notebook titled "RF_NSGA_Catalysis_Optimization" use the excel sheet titled "promoter_only" 
