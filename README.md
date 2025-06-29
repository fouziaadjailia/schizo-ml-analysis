# Understanding Schizophrenia through Machine Learning

This repository contains the implementation of the experiments presented in the research paper:
**"Understanding the Interplay of Clinical Features and Cognitive Behavior in Schizophrenia: A Machine Learning Study"** (DISA 2023).

## 🧠 About the Study

This study explores how clinical and cognitive features correlate with schizophrenia using machine learning techniques. By applying multiple classifiers to a curated dataset, the research seeks to highlight important biomarkers and validate the discriminative capacity of psychological and clinical traits.

**Citation**:
> F. Adjailia, S. A. Hadri, A. Bouramoul,  
> *Understanding the Interplay of Clinical Features and Cognitive Behavior in Schizophrenia: A Machine Learning Study*,  
> IEEE DISA 2023. DOI: [10.1109/DISA59116.2023.10308933](https://doi.org/10.1109/DISA59116.2023.10308933)

## 🧪 Experimental Setup

- **Dataset**: Clinical and neurocognitive data from schizophrenia patients and healthy controls.
- **Features Used**:
  - PANSS (Positive and Negative Syndrome Scale)
  - MoCA (Montreal Cognitive Assessment)
  - BACS (Brief Assessment of Cognition in Schizophrenia)
  - Age, Gender, Clinical Diagnosis
  
- **Classifiers Used**:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Support Vector Machine (SVM)
  - AdaBoost
  - XGBoost

- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

## 📈 Results Summary

| Classifier       | Accuracy | F1-Score | ROC-AUC |
|------------------|----------|----------|---------|
| Logistic Regression | ~0.87 | ~0.86 | ~0.88 |
| Random Forest       | ~0.91 | ~0.91 | ~0.93 |
| XGBoost             | **~0.93** | **~0.92** | **~0.95** |
| SVM                 | ~0.88 | ~0.87 | ~0.89 |

XGBoost outperformed all other classifiers and showed strong predictive power using a compact set of neurocognitive and clinical features.



## 📚 Reference
If you find this work useful, please cite the original paper and consider giving this repo a ⭐.


## 🚀 Getting Started

### Requirements

```bash
pip install -r requirements.txt


