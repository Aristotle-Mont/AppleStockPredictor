# AppleStockPredictor

```markdown
# Linear Regression for High Price Prediction

This Python script demonstrates how to perform linear regression for predicting high prices using a dataset from a CSV file. The script includes data preprocessing, model training, evaluation, and visualization.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone or download this repository to your local machine.
2. Replace the `txt_file_path` variable with the path to your CSV file containing the dataset.
3. Ensure that your dataset contains columns for 'Low', 'Close', and 'High' prices.
4. Run the script in your Python environment.

The script will load the data, preprocess it by handling missing values, train a linear regression model, make predictions, and visualize the results.

## Results

The script will print the Mean Squared Error (MSE) and the R-squared (R2) score as evaluation metrics for the model's performance. It will also display a scatter plot showing the actual high prices in blue and the predicted high prices in red.
