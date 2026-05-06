# Credit Card Fraud Detection

A Jupyter notebook project for exploring **unsupervised machine learning** techniques to detect suspicious credit card transactions.

## Overview

This project uses `credit-card-detection-machinelearning-models.ipynb` to analyze transaction data and experiment with anomaly detection approaches such as clustering and outlier detection.

## Techniques Used

- Data loading and preprocessing with Pandas and NumPy
- Feature scaling with `StandardScaler` and `RobustScaler`
- Dimensionality reduction with `PCA` and `TSNE`
- Unsupervised models such as `KMeans`, `DBSCAN`, `IsolationForest`, and `LocalOutlierFactor`
- Evaluation and visualization with Matplotlib and Seaborn

## Project Files

- `credit-card-detection-machinelearning-models.ipynb` - main analysis notebook
- `converted-document.pdf` - reference document
- `creditcard.csv` - dataset file used by the notebook

## Setup

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Usage

Open the notebook in Jupyter Notebook, JupyterLab, or VS Code and run the cells in order.

```bash
jupyter notebook
```

If you are using VS Code, open `credit-card-detection-machinelearning-models.ipynb` directly and select the Python interpreter from your virtual environment.

## Notes

- The dataset file is ignored by Git because it is too large for a normal GitHub push.
- If you want to version large datasets, use Git LFS or store the data externally.

## License

No license file is included yet.
