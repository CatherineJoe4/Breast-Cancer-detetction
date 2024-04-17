# Breast Cancer Detection

This project aims to predict whether a breast tumor is malignant (cancerous) or benign (non-cancerous) based on various features. The dataset used in this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

## Dataset Description

The dataset contains information about breast tumors, including their characteristics measured from digitized images. It includes features such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and more. The target variable is the diagnosis, which indicates whether the tumor is malignant (M) or benign (B).

## Requirements

- Python 3
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn





## Results

The following machine learning algorithms were trained and evaluated on the dataset:

- Logistic Regression
  - Accuracy: 94.41%
  - Precision: 89.47%
  - Confusion Matrix:
    
    [[84  6]
     [ 2 51]]
    

- K-Nearest Neighbors
  - Accuracy: 93.71%
  - Precision: 90.74%
  - Confusion Matrix:
    
    [[85  5]
     [ 4 49]]
    

- Support Vector Machine (Linear Kernel)
  - Accuracy: 95.80%
  - Precision: 91.23%
  - Confusion Matrix:
    
    [[85  5]
     [ 1 52]]
    

- Support Vector Machine (RBF Kernel)
  - Accuracy: 93.71%
  - Precision: 97.83%
  - Confusion Matrix:
    
    [[89  1]
     [ 8 45]]
    

- Naive Bayes
  - Accuracy: 93.71%
  - Precision: 92.31%
  - Confusion Matrix:
    
    [[86  4]
     [ 5 48]]
    

- Decision Tree
  - Accuracy: 95.80%
  - Precision: 95.80%
  - Confusion Matrix:
    
    [[86  4]
     [ 2 51]]
    

- Random Forest
  - Accuracy: 98.60%
  - Precision: 98.11%
  - Confusion Matrix:
    
    [[89  1]
     [ 1 52]]
    

## Conclusion

The Random Forest algorithm achieved the highest accuracy of 98.60% in predicting breast tumor diagnosis. It also demonstrated high precision in classifying both malignant and benign tumors.

