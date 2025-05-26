# Mathematical Climate Modelling: El Niño–Southern Oscillation (ENSO)

This repository contains the code and presentation materials for a research project on mathematical climate modelling using Python.

## Overview

- ENSO can be mathematically modelled using coupled PDEs describing interactions between sea surface temperature, the atmosphere, and the ocean.
- The PDEs are discretized using finite differences for numerical simulation, enabling the computation of the observed temperature *T* over space and time.
- Dimensionality reduction via proper orthogonal decomposition is applied to reduce the system's dimension from 2000 to 4.
- The SINDy algorithm is used to identify an ODE model for the dynamical system.

## Built With

- Python (NumPy, Matplotlib, PySINDy, pandas)

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/ericahan22/ENSO-modelling.git
   cd ENSO-modelling
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook:
   ```bash
   jupyter notebook ENSO_model.ipynb
