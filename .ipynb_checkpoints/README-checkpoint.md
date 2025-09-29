# breast_cancer_classification

## Purpose
The goal of this project is to predict whether a tumor is **benign or malignant** using clinical measurements from the [UCI Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

## Methods  
- Loaded data from UCI repository.  
- Preprocessed by dropping ID column, encoding diagnosis (M=1, B=0), and scaling features.  
- Applied **Logistic Regression** to the full feature set.  
- Reduced features with **PCA (2 components)** for comparison.

##  Results  
- Logistic Regression (full features): ~96% test accuracy  
- Logistic Regression (PCA=2): ~87% test accuracy  

##  Reflection  
- Logistic Regression works well on this dataset even without tuning.  
- PCA helps visualize but reduces accuracy.  
- **Next steps:** explore Random Forests, feature importance, and SHAP for interpretability.  

## Project Files  
- `breast_cancer_classification.ipynb`: Jupyter notebook with full code.  
- `requirements.txt`: Python dependencies.  
