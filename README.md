# applied-ML-toolkit

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Latest-orange.svg)](https://pytorch.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-orange.svg)](https://scikit-learn.org/)

**ML Foundations** is a core reference repository containing ground-up implementations of classic machine learning algorithms, deep learning primitives (PyTorch), and foundational data manipulation pipelines (NumPy & Pandas). 

This repository serves as both an educational resource and a toolkit for core algorithmic logic without heavy reliance on high-level, black-box frameworks.

## 🧠 Features

* **Classic Machine Learning**: From-scratch implementations of fundamental algorithms such as Linear Regression (via Normal Equation), Logistic Regression (via SGD), K-Nearest Neighbors, and Adaboost/Random Forest concepts.
* **Deep Learning Primitives**: Comprehensive examples of PyTorch tensor initialization, matrix math, broadcasting, and advanced indexing.
* **Data Manipulation**: Practical workflows for data engineering including handling ragged arrays (padding), outlier detection, vector normalization, and Pandas aggregations.

## 📂 Project Structure

```text
.
├── Basic Algorithms/
│   ├── KNN_Scratch.py               # K-Nearest Neighbors implementation from scratch
│   └── Learning_Rate_detection.py   # Utilities for learning rate optimization
├── Classic_ml/
│   ├── 0_linear_regression_normal_eq.py # Linear regression using the normal equation
│   ├── 1_logistic_regression_SGD.py     # Logistic regression using Stochastic Gradient Descent
│   ├── 6_Random_Forest.py               # Ensemble methods, Bagging, and AdaBoost concepts
│   ├── 7_data_manipulation.py           # NumPy & Pandas data wrangling techniques
│   └── numpy_pandas_pracs/
│       └── padding row.py               # Ragged array standardization and missing value imputation
├── 1_tensor_initialization.py       # PyTorch tensor generation and type casting
├── 2_tensor_math.py                 # PyTorch linear algebra and mathematical operations
└── 3_indexing_tensor.py             # Advanced PyTorch tensor slicing and masking
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed. It is recommended to use a virtual environment.

```bash
# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/ml-foundations.git
cd ml-foundations

# Install dependencies
pip install torch numpy pandas scikit-learn
```

## 💡 Usage Examples

**Running a Classic ML Model (Logistic Regression with SGD):**
```bash
python Classic_ml/1_logistic_regression_SGD.py
```

**Testing PyTorch Tensor Math:**
```bash
python 2_tensor_math.py
```

## 🤝 Contributing

Contributions are welcome! If you would like to add new from-scratch algorithm implementations or improve existing data manipulation scripts:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AlgorithmName`)
3. Commit your changes (`git commit -m 'Add AlgorithmName'`)
4. Push to the branch (`git push origin feature/AlgorithmName`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.