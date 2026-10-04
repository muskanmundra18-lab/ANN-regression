# ANN Regression on Power Plant Data

A regression project that uses an **Artificial Neural Network implemented in PyTorch** to predict electrical power output from power-plant measurements.

## Dataset

The project uses `powerplant_data.csv`, containing **9,568 observations and 5 columns**.

The target variable is:

```text
PE
```

The remaining features are used as model inputs.

## Workflow

```text
Power Plant Data
      ↓
Train/Test Split
      ↓
StandardScaler
      ↓
Tensor Conversion
      ↓
ANN
      ↓
Regression Prediction
      ↓
R² Evaluation
```

## Model

The ANN is implemented using PyTorch and trained with mini-batches.

The project includes:

- Feature scaling
- PyTorch tensors
- DataLoader
- Fully connected neural network
- Regression loss
- R² evaluation

## Tech Stack

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/muskanmundra18-lab/ANN-regression.git
cd ANN-regression
```

Install dependencies:

```bash
pip install pandas numpy torch scikit-learn matplotlib
```

Open:

```text
ANN_regression.ipynb
```

## Why This Project?

This project demonstrates how neural networks can be applied to **continuous-value prediction**, rather than classification.

## Future Improvements

- Add MAE and RMSE alongside R²
- Plot predicted vs. actual values
- Add validation-loss tracking
- Tune network depth and hidden-layer sizes
- Compare ANN performance with Random Forest and Gradient Boosting

## Author

**Muskan Mundra**
