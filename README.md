# Extended Lotka-Volterra Model

Stochastic Predator–Prey Dynamics with Disease Outbreaks: An Extended Lotka–Volterra Model

**Author:** Dinh Nguyen  
**Year:** 2024  

## Description

This project extends the classic Lotka-Volterra predator-prey model to include disease dynamics. The model incorporates three populations: healthy prey, predators, and diseased prey.

## Model Equations

**Extended Lotka-Volterra:**
```
dx/dt = αx - βxy - εx
dy/dt = δxy - γy - θyz
dz/dt = εx - ηz
```

Where:
- `x`: Healthy prey population
- `y`: Predator population  
- `z`: Diseased prey population

## Contents

The notebook includes:
- Deterministic and stochastic simulations
- Steady state analysis
- Game theory analysis
- Monte Carlo simulations
- Gillespie algorithm implementation

## Usage

Open and run `extended_model.ipynb` in Jupyter Notebook.

