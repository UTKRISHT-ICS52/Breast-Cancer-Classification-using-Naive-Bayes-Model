# Breast-Cancer-Classification-using-Naive-Bayes-Model

## Project Overview

This project implements a Machine Learning classification model using the Gaussian Naive Bayes algorithm to classify breast cancer tumors into two categories: Benign and Malignant.

The model is developed using the Breast Cancer dataset and applies probability-based classification to predict tumor categories based on numerical features.

## Objectives

- Implement Gaussian Naive Bayes for binary classification.
- Understand the application of Bayes' theorem in Machine Learning.
- Perform data preprocessing and train-test splitting.
- Classify tumors into Benign and Malignant categories.
- Evaluate model performance using multiple classification metrics.
- Visualize the Confusion Matrix and ROC Curve.

## Dataset

**Dataset:** Breast Cancer Dataset

**Target Classes:**
- 0 – Benign (Non-cancerous)
- 1 – Malignant (Cancerous)

The dataset contains numerical features extracted from digitized images of breast mass samples.

Some important features include:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm

**Gaussian Naive Bayes**

Gaussian Naive Bayes is a supervised Machine Learning algorithm based on Bayes' theorem. It is commonly used for classification problems involving continuous numerical features.

The algorithm assumes that features follow a Gaussian (normal) distribution within each class and uses conditional independence between features to estimate class probabilities.

## Project Workflow

1. Dataset Loading
2. Data Exploration and Analysis
3. Missing Value Checking
4. Duplicate Record Checking
5. Data Preprocessing
6. Feature and Target Separation
7. Train-Test Split (80:20)
8. Gaussian Naive Bayes Model Training
9. Model Prediction
10. Performance Evaluation
11. Confusion Matrix Visualization
12. Classification Report
13. ROC Curve Analysis
14. Final Results Summary

## Model Configuration

| Parameter | Value |
|---|---|
| Algorithm | Gaussian Naive Bayes |
| Training Data | 80% |
| Testing Data | 20% |
| Random State | 42 |
| Classification Type | Binary Classification |
| Target Classes | Benign and Malignant |

## Results and Performance

The Gaussian Naive Bayes model was evaluated using the following metrics:

| Evaluation Metric | Score |
|---|---|
| Accuracy | Refer to notebook output |
| Precision | Refer to notebook output |
| Recall | Refer to notebook output |
| F1-Score | Refer to notebook output |
| ROC-AUC | Refer to notebook output |

### Confusion Matrix

The confusion matrix visualizes the correctly and incorrectly classified Benign and Malignant cases.

### Classification Report

The classification report provides Precision, Recall, F1-score, and Support for both target classes.

### ROC Curve

The ROC curve evaluates the model's ability to distinguish between Benign and Malignant classes using different classification thresholds.

## Results and Conclusion

The Gaussian Naive Bayes algorithm was successfully implemented for breast cancer classification.

The model demonstrates how probability-based classification can be applied to distinguish between Benign and Malignant tumor cases using numerical features.

The experiment highlights the importance of Bayes' theorem, data preprocessing, model evaluation, and performance visualization in Machine Learning.

The model's effectiveness should be assessed using its actual evaluation metrics, particularly recall for the Malignant class.

## Repository Structure

```text
Breast-Cancer-Naive-Bayes/
│
├── Naive_Bayes.ipynb
├── breast cancer.csv
└── README.md
```

## Installation and Execution

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Project

Open `Naive_Bayes.ipynb` and execute all cells sequentially.

Make sure the dataset CSV file is available at the path specified in the notebook.

## Author

**Utkrisht Patel**

B.Tech – Computer Science and Engineering

Researcher | Machine Learning | IoT

---

**Disclaimer:** This project is developed for educational and research purposes only. It is not a clinically validated diagnostic system and should not be used for medical decision-making.
