# Thermal Tensor Decomposition

## Overview
This repository hosts a Python-based analysis focused on identifying materials through their heat transfer processes. Utilizing CP and Tucker tensor decomposition methods, the project analyzes a series of heat distribution images represented as tensors, to compare and identify the thermal diffusivity characteristics of an unknown material against known ones.

## Key Features
- **Heat Transfer Analysis**: Implements the heat diffusion equation to simulate heat transfer across materials.
- **Tensor Decomposition**: Applies CP and Tucker decomposition to extract features from heat distribution tensors.
- **Material Identification**: Uses Akaike Information Criterion (AIC) to select optimal decomposition ranks and identify the unknown material by comparing thermal properties.

## Dataset
The `heatT.mat` file contains three tensors:
1. Heat transfer in Material 1
2. Heat transfer in Material 2
3. An unknown material undergoing heat transfer

## Requirements
- Python
- `Numpy`
- `Pandas`
- `Tensorly` for tensor decomposition
- `Itertools`
- `Scipy`


