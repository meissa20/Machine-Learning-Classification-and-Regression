## Project Structure

Machine-Learning-Classification-and-Regression/
├── data/ # Dataset files (optional - if included)
│ ├── magic_gamma.csv # Classification dataset
│ └── california_housing.csv # Regression dataset
├── KNN.ipynb # Classification notebook
├── Regression.ipynb # Regression notebook
└── README.md # This file


## Notebooks Overview

### 1. KNN.ipynb (Classification)
**Dataset**: MAGIC Gamma Telescope  
**Tasks**:
- Balance the dataset (undersample gamma class)
- Train/Val/Test split (70%/15%/15%)
- K-Nearest Neighbors implementation with various K values
- Performance evaluation:
  - Accuracy, Precision, Recall, F1-score
  - Confusion matrices
- Comparative analysis of different K values

### 2. Regression.ipynb
**Dataset**: California Housing Prices  
**Tasks**:
- Train/Val/Test split (70%/15%/15%)
- Implementation of:
  - Linear Regression
  - Lasso Regression
  - Ridge Regression
- Performance metrics:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

## How to Run
1. Ensure you have Python 3.8+ installed
2. Install required packages:
   ```bash
   pip install numpy pandas scikit-learn matplotlib jupyter

### 3. Run the notebooks:
```bash
  jupyter notebook KNN.ipynb
  jupyter notebook Regression.ipynb
