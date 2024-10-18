# Wine Quality Classifier Project

## Overview

This project aims to build a **Wine Quality Classifier** that predicts the quality of wine based on its chemical properties. Three machine learning models—**Random Forest**, **SVM (Support Vector Machine)**, and **Neural Networks**—were tested to determine the best model for this task. The **Random Forest** model achieved the highest accuracy and performed the best at generalizing to unseen data.

### Models Tested:
- **Random Forest**: Best test accuracy of 69.9% with 45 trees.
- **SVM**: Cross-validation accuracy of 61.3%.
- **Neural Network**: Training accuracy of 96.9%, but test accuracy of 60.7%, showing overfitting.

### Dataset

The dataset contains various chemical properties of wines, such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Alcohol content
- pH, etc.

The target label is the **quality of wine** (ranging from 3 to 8).

## Requirements

Make sure to install the following dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib
```

### Running the Notebook
You can find the main code in the Jupyter Notebook file `Wine_Quality_Classifier.ipynb`.

To run the notebook, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/your-username/wine-quality-classifier.git
```
2. Navigate to the project directory:

```bash
cd wine-quality-classifier
```
3. Launch Jupyter Notebook:

```bash
jupyter notebook Wine_Quality_Classifier.ipynb
```
4. Run all the cells in the notebook to see the data preprocessing steps, model training, and evaluation.

## Project Structure
```bash
├── dataset
│   └── WineQT.csv           # Wine quality dataset
├── Wine_Quality_Classifier.ipynb  # Jupyter notebook with the project code
├── README.md                # Project overview and instructions (this file)
└── results
    └── model_comparison.png  # Optional: Comparison of model performances
