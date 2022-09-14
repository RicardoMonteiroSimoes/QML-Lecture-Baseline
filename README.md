# Qiskit lecture help

This repository can be used to help you construct lectures on quantum machine learning concepts using proven and tested circuits.

# Installation

We suggest the installation of `miniconda` to run the experiments. `miniconda` allows the creation of virtual python environments and keeps things clean. You can find the correct install for you [here](https://docs.conda.io/en/latest/miniconda.html). Once installed, you can create a virtual environment for this repository using `conda create -n desiredName python=3.9`. Afterwards activate the environment using `conda activate desiredName`, and then run `pip install -r requirements.txt` to install all required packages.

## Content

 - requirements.txt
   - Just run `pip install -r requirements.txt` to install all packages. Make sure you are on Python >= 3.9.0!
 - datasets.ipynb
   - This file will generate/load all the datasets you require to run the scripts in this repository. This helps keep the repository small
 - experiments/
   - qsvm.ipynb
     - This notebook is used to demonstrate quantum enhanced support vector machines, as well as compare them to classical counterparts using the given datasets
   - qnn.ipynb
     - In this notebook you will see the quantum equivalent of a neural network, and perform experiments on it.