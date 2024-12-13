# DL-SAR-Hotspots

This repository contains the two Jupyter notebooks for Predicting SAR Hotspot Locations and Values:

 **1. Predicting SAR Hotspot Locations (`Hotspots_Position.ipynb`)**
This notebook contains the source code for predicting the location of SAR (Specific Absorption Rate) hotspots using deep learning, specifically a Convolutional Neural Network (CNN). The model takes input images and frequency values to predict the position of SAR hotspots.

**2. Predicting the SAR Hotspot Value (`Hotspots_Value.ipynb`)**
The objective of this notebook is to estimate the SAR at a given location within an image where the hotspot is located, based on both the image data and associated frequency values. The deep learning model uses CNN to predict the SAR value at the identified hotspot location.

---

## Requirements
To run this project, you need the following:
- **Python** 3.8 or above
- Libraries:
  - `TensorFlow` >= 2.10.0
  - `Pandas`
  - `Numpy`
  - `Pillow`
  - `Matplotlib`
  - `SciPy`
  - `Scikit-learn`
