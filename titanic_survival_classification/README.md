# Titanic Survival Classification

This project builds a classification model to predict passenger survival on the Titanic using the classic Titanic dataset.

## Dataset

The dataset used is `titanic.csv`, containing passenger information such as age, sex, fare, class, and embarkation port, with the target variable `Survived`.

## Notebook

`titanic_survival_classification.ipynb`: This notebook performs the following tasks:

- **Data Preprocessing**
  - Drops irrelevant columns: `PassengerId`, `Name`, `Ticket`, `Cabin`
  - Handles missing values: fills `Age` with the median and `Embarked` with the mode
  - Encodes categorical variables: maps `Sex` to binary values (`male: 0`, `female: 1`)
  - One-hot encodes `Embarked` using `pd.get_dummies` (dropping the first category to avoid multicollinearity)

- **Feature Engineering**
  - Separates features (`X`) and target (`y`)
  - Fills any remaining missing values with `0`

- **Model Training & Evaluation**
  - Splits data into training and testing sets (80/20 split with `random_state=42`)
  - Standardizes features using `StandardScaler`
  - Trains a `LogisticRegression` model
  - Evaluates the model using:
    - Accuracy Score
    - Confusion Matrix
    - Classification Report

## Requirements

To run this notebook, you need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: pandas, numpy, scikit-learn

You can install the required libraries using pip:

```
pip install pandas numpy scikit-learn
```

## Usage

1. Ensure the `titanic.csv` file is in the same directory as the notebook.
2. Open `titanic_survival_classification.ipynb` in Jupyter Notebook.
3. Run the cells in order to train the model and view evaluation results.

## License

This project is for educational purposes.

