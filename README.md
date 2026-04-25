# Room Occupancy Classification - MPA MLF 2026

This project aims to classify the number of persons in a room from 60 GHz radar delay-Doppler images.

## Task

The model predicts one of four classes:
- 0: no person
- 1: one person
- 2: two persons
- 3: three persons

## Method

A simple Convolutional Neural Network was trained using PyTorch.

Main steps:
- data loading
- image preprocessing
- train/validation split
- CNN training
- validation evaluation
- Kaggle submission generation

## Results

The final baseline CNN achieved a Kaggle public score of 0.92545.

## Files

- `notebook.ipynb`: main notebook with preprocessing, training and submission generation
- `README.md`: project description
- `.gitignore`: excludes datasets and large files

The dataset is not included in this repository.
