# 2026 EDS 232 Kaggle Competition (Team coralWeavers)
This repository contains all relevant code and documents for the 2026 EDS 232 Kaggle Competition. Please refer to the Kaggle Competition homepage for additional information on competition rules and dataset access.

This repository is maintained by Vedika Shirtekar, Melannie Moreno Rolon, and Ixel Medrano.

## Description 
The purpose of this repository is to test different kinds of models to produce the lowest test MSE for predictions of dissolved inorganic carbon (DIC) evaluted by Kaggle. A linear (ridge regression) and nonlinear (Random Forest) approach was adopted to explore the diversity of obtained test MSEs and compare overall performance among models. 

## Repository Structure

```
├── data-submission # Contains submission files for predictions of DIC 
│   ├── submission_random_forest_baseline.csv
│   ├── submission_random_forest_tuned.csv
│   └── submission_ridge.csv
├── kaggle-notebook-competition.ipynb # Contains all relevent code for analysis
├── LICENSE
└── README.md
```

## Dataset 
The data used in this analysis is not housed in this repository. Please refer to the Kaggle Competition homepage for additional information on data access. 

## Acknowledgements
This repository is maintained as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the EDS 232: Machine Learning for Environmental Data Science course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.
