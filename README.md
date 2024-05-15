# Machine Learning Force Fields for Transition Metal Complexes

This repository contains the code and data used in my Bachelor's thesis project, where I developed machine learning models to predict the HOMO-LUMO gap in transition metal complexes.

## Project Overview

The project involved the development of machine learning models using the largest Coulomb matrix elements as features. The models were trained on the tmQM dataset, which contains the geometries and properties of a large transition metal–organic compound space.


## Getting Started

Best to run this project on Google Colab

## Dependencies

- Python 3.7+
- NumPy
- pandas
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn



## Dataset

The transition metal quantum mechanics tmQM [Link](https://github.com/bbskjelstad/tmqm) data set was used in this project, which contains the geometries and properties of a large transition metal–organic compound space. tmQM comprises 86,665 mononuclear complexes extracted from the Cambridge Structural Database.

The data files used for this project are:
- tmQM_y.csv: Contains the quantum properties including the target variable HOMO-LUMO gap.
- tmQM_X2.xyz.gz: Contains the Cartesian coordinates of all metal complexes optimized in .xyz format, compressed by gzip.

## Notebooks

The project consists of two notebooks:

- Data_analysis.ipynb: This notebook contains the exploratory data analysis and preprocessing steps. It provides insights into the data and prepares it for the machine learning models.

- Model_development.ipynb: This notebook contains the development of several models
