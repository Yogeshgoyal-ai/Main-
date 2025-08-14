# Task 7: Support Vector Machines (SVM) Classification

This project implements SVM classification on the Breast Cancer dataset.

## Features:
- **Linear and RBF kernels** implemented and compared
- **Hyperparameter tuning** using GridSearchCV for RBF kernel
- **Cross-validation** for model performance evaluation
- **2D decision boundary visualization** for RBF kernel
- All outputs saved in the `outputs` folder

## Files:
- `breast_cancer.csv`: dataset
- `svm_classification.py`: main script
- `outputs/`: contains confusion matrices, classification reports, best params, CV scores, and decision boundary plot

## How to run:
```bash
pip install -r requirements.txt
python svm_classification.py
```

