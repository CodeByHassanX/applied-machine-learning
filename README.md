# Titanic Data Analysis Lab

This repository contains a Jupyter notebook for exploring and preprocessing the Titanic dataset as part of an Applied Machine Learning course.

## Dataset

The dataset used is `titanic.csv`, which contains information about passengers on the Titanic, including features like age, sex, fare, etc., and the target variable for survival.

## Notebook

`titanic_data_exploration.ipynb`: This notebook performs the following tasks:

- Loads the dataset using pandas
- Handles missing values (fills Age with median, Embarked with mode)
- Computes basic statistics (mean, median, mode for Age and Fare)
- Visualizes distributions of Age and Fare using seaborn and matplotlib
- Encodes categorical variables (e.g., Sex using LabelEncoder)

## Requirements

To run this notebook, you need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

You can install the required libraries using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Ensure the `titanic.csv` file is in the same directory as the notebook.
2. Open `titanic_data_exploration.ipynb` in Jupyter Notebook.
3. Run the cells in order to execute the analysis.

## License

This project is for educational purposes.