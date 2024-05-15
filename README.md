# Machine Learning Force Fields for Transition Metal Complexes

This repository contains the code and data used in my Bachelor's thesis project, where I developed machine learning models to predict the HOMO-LUMO gap in transition metal complexes.

## Project Overview

The project involved the development of machine learning models using the largest Coulomb matrix elements as features. The models were trained on the tmQM dataset, which contains the geometries and properties of a large transition metal–organic compound space.


## Repository Structure

- `data/`: This directory contains the tmQM dataset used for training and testing the models.
- `models/`: This directory contains the trained machine learning models.
- `notebooks/`: This directory contains Jupyter notebooks with exploratory data analysis and model development.
- `src/`: This directory contains Python scripts for data preprocessing, model training, and evaluation.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the notebooks in the `notebooks/` directory to understand the data analysis and model development process.
4. Use the scripts in the `src/` directory to train the models on your own or to use the pre-trained models on new data.

## Dependencies

- Python 3.7+
- NumPy
- pandas
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Contributing

Feel free to fork this repository and contribute. Pull requests are welcome.

## License

This project is licensed under the MIT License.

## Contact

For any questions or concerns, please open an issue in this repository.

## Dataset

The transition metal quantum mechanics tmQM [Link](https://github.com/bbskjelstad/tmqm) data set was used in this project, which contains the geometries and properties of a large transition metal–organic compound space. tmQM comprises 86,665 mononuclear complexes extracted from the Cambridge Structural Database.

The data files used for this project are:
- tmQM_y.csv: Contains the quantum properties including the target variable HOMO-LUMO gap.
- tmQM_X2.xyz.gz: Contains the Cartesian coordinates of all metal complexes optimized in .xyz format, compressed by gzip.

## Notebooks

The project consists of two notebooks:

- Data_analysis.ipynb: This notebook contains the exploratory data analysis and preprocessing steps. It provides insights into the data and prepares it for the machine learning models.

- Model_development.ipynb: This notebook contains the development of several models
