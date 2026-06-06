# XAI-tool4GEE-RemakeVN
A local notebook for land cover mapping and monitoring using Earth Engine
# Overview

This project was developed as an undergraduate thesis in Land Management.

The application provides an interactive workflow for Land Use/Land Cover (LULC) classification and change detection using remote sensing imagery and machine learning techniques.

Built on top of Google Earth Engine, the system supports image preprocessing, feature extraction, classification, accuracy assessment, area estimation, and temporal change analysis through an integrated graphical user interface.

# User interface

<img width="1842" height="891" alt="Screenshot 2026-06-07 041315" src="https://github.com/user-attachments/assets/3df7614f-266b-4c0b-b41a-5a5411a36851" />


# Key Features

## Remote Sensing Data Processing

Landsat 7, Landsat 8, Landsat 9 support
Sentinel-2 support
Sentinel-1 SAR integration
Cloud masking and image filtering
Multi-source data fusion

## Machine Learning Classification

Random Forest classifier
Training sample management
Feature engineering
Spectral indices generation
Topographic variable integration

## Accuracy Assessment

Holdout validation
Spatial Block Cross Validation
Confusion Matrix
Overall Accuracy (OA)
Kappa Coefficient
Quantity and Allocation Disagreement Metrics

## Change Detection

Land Use/Land Cover change analysis
Temporal classification workflow
Change matrix generation
Area transition statistics

## Advanced Analysis

SHAP feature importance analysis
Olofsson area estimation
Zonal statistics
Harmonic regression features
Time-series analysis

## Technologies

Python
Google Earth Engine
Geemap
Scikit-learn
Pandas
NumPy
Plotly
SHAP
Ipywidgets
Jupyter Notebook

# Research Topic

Machine Learning-Based Assessment of Land Use and Land Cover Change Using Remote Sensing Data.

# Author

Huy

Land Management Engineer

# Acknowledgements

Modified and extended from the original GeoAIR Lab project (MIT License).

The original system has been modified and extended for academic and research purposes, including interface redesign, workflow customization, additional analysis modules, validation methods, and change detection functions.

# License

This repository includes components derived from software released under the MIT License by GeoAIR Lab.

Original copyright:

Copyright (c) 2023 GeoAIR Lab
