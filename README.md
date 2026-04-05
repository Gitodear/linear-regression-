# Linear Regression - Diabetes Dataset Analysis

## 📋 Project Overview

This project implements a **Linear Regression model** to predict diabetes progression using the scikit-learn diabetes dataset. The notebook demonstrates the complete machine learning workflow including data loading, preprocessing, visualization, model training, and evaluation.

## 🎯 What This Project Does

- Loads the diabetes dataset (442 samples, 10 features)
- Performs exploratory data analysis with visualizations
- Splits data into training (70%) and testing (30%) sets
- Trains a Linear Regression model
- Evaluates model performance using MSE and R² score
- Displays model coefficients and intercept

## 📦 Technologies Used

- **Python 3.x**
- **NumPy** - Numerical computing
- **scikit-learn** - Machine learning library
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Pandas** - Data manipulation

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Gitodear/linear-regression-.git
cd linear-regression-
```

### 2. Create Virtual Environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install numpy scikit-learn matplotlib seaborn pandas
```

### 4. Run the Notebook

```bash
jupyter notebook LinearRegression.ipynb
```

## 📊 Project Structure

```
linear-regression/
├── LinearRegression.ipynb    # Main notebook with full analysis
├── README.md                 # Project documentation
└── .venv/                    # Virtual environment
```

## 🔍 Notebook Workflow

### Cell 1: Imports

```python
import numpy as np
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error, r2_score
from sklearn import datasets
import matplotlib.pyplot as plt
import seaborn as sns
```

### Cell 2: Load Data

- Loads diabetes dataset (442 samples × 10 features)
- Displays dataset shape and description

### Cell 3: Train-Test Split

- Splits data: 70% training, 30% testing
- Uses random_state=42 for reproducibility

### Cell 4: Data Visualization

- Creates 2×5 subplot grid
- Visualizes each feature vs target variable

### Cell 5-9: Model Training & Evaluation

- Trains Linear Regression model
- Makes predictions on test set
- Calculates MSE and R² score
- Displays model coefficients and intercept

## 📈 Key Metrics

- **Mean Squared Error (MSE)** - Measures prediction error magnitude
- **R² Score** - Indicates how well the model fits the data (0-1 scale)
- **Model Coefficients** - Weights assigned to each feature
- **Intercept** - Baseline prediction value

## 💡 How to Use

1. **Run all cells** in order from top to bottom
2. **View visualizations** to understand feature relationships
3. **Check the metrics** to evaluate model performance
4. **Modify as needed** - Change train_size ratio, features, or try different algorithms

## 🎓 Learning Outcomes

- Understanding linear regression concepts
- Data preprocessing and splitting
- Model training and evaluation
- Data visualization techniques
- Working with scikit-learn library

**Created by:** Tamaterkun
**Last Updated:** March 31, 2026
