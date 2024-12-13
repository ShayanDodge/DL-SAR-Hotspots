# DL-SAR-Hotspots

# Predicting SAR Hotspot Locations Using Deep Learning

This repository contains the source code for the research study **"A Deep Learning-Based Prediction of Specific Absorption Rate Hot-Spots Induced by Broadband Electromagnetic Devices: A Pilot Study"**. The project involves a deep learning model for predicting the location of SAR (Specific Absorption Rate) hotspots using input images and frequency values.

---

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

---

## Overview
This project aims to predict the (x, y) coordinates of SAR hotspots in images based on:
1. **Input Images**: Resized images of electromagnetic SAR distributions.
2. **Frequency**: The frequency at which the SAR is measured.

The deep learning model utilizes Convolutional Neural Networks (CNNs) for image processing and dense layers for numerical input processing.

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

Install all dependencies using:
```bash
pip install -r requirements.txt
