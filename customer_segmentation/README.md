# Customer Segmentation

This project explores **customer segmentation** using the `train.csv` dataset and produces **customer segments** saved in `Final_Customer_Segments.csv`.

## Dataset

- **Input**: `train.csv`
- **Output**: `Final_Customer_Segments.csv`

## Notebook

- `customer_segmentation.ipynb`

Typically includes steps like:
- data cleaning and preprocessing
- feature selection (e.g., Age, Income, Spending Score if applicable)
- feature scaling using StandardScaler
- finding optimal clusters using the Elbow Method
- applying K-Means clustering
- visualizing customer segments
- saving the final segments to CSV

## Results

- Customers grouped into meaningful clusters
- Each cluster represents a unique buying behavior
- Useful for targeted marketing strategies

## Requirements

- Python 3.x
- Jupyter Notebook/JupyterLab
- Common libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Usage

1. Ensure `train.csv` is in the same folder.
2. Open `customer_segmentation.ipynb` in Jupyter Notebook/JupyterLab.
3. Run cells in order.

## Output Files

- `Final_Customer_Segments.csv`

## License

Educational purposes.

