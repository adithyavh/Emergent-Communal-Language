# Convergence to a Common Protocol in Emergent Communication

## Table of Contents
- [About](#about)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Directory Structure](#directory)

## About

Emergent Communication is a flexible, bottom-up framework that studies the properties of protocols created by artificial agents (sender-receiver pairs) to coordinate and solve a task. This project focuses on studying how individual idiolects formed through local interactions are extrapolated to form a communal language.

This codebase implements EC from scratch in a population, using the Gumbel-Softmax Relaxation. You will also find implementations of Inner Speech, a new cognitive architecture, inspired by the Rational Speech Acts (RSA) framework.

## Getting Started

Please ensure you have anaconda installed. If not, install it using the instructions here: https://www.anaconda.com/download

Run the following bash commands on your terminal:  

```bash
conda env create -f environment.yaml
conda activate ec
```

## Usage

### Training Models

Data: The simulated objects used for training the models are created in the code itself. A random seed is set to ensure the data produced is consistent across execution runs, and to enable comparisons in performance.

1. Open Training.ipynb in a Jupyter environment.
2. Select 'ec' as your python kernel's environment. 
3. Click 'Run All', or individually run the relevant cell.

### Creating Visualisations from Saved Models and Training Results

1. Open Visualisations.ipynb in a Jupyter environment.
2. Select 'ec' as your python kernel's environment. 
3. Click 'Run All', or individually run the relevant cell.

## Directory Structure

```markdown
EC-Submission/
│
├──readme.md
│
├──environment.yaml
│
├──Training.ipynb
│
├──Visualisations.ipynb 
│
├──ModelFiles/
│    ├──exp8.1/
│    ├──exp8.2/
│    ├──...
│    └──exp8.8/
│
└──Images/
     ├──image1.pdf
     ├──...
     └──imageX.pdf
```