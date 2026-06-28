# 🩺 Breast Cancer Tumor Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

Breast cancer is one of the most common cancers affecting women worldwide. Early detection plays a vital role in improving survival rates.

This project develops a **Machine Learning model** that classifies breast tumors as **Malignant** or **Benign** using the **Breast Cancer Wisconsin Diagnostic Dataset** provided by Scikit-learn.

A **Gaussian Naive Bayes Classifier** is trained and evaluated to predict tumor diagnosis with high accuracy.

---

# 🎯 Objectives

- Perform data loading and preprocessing
- Explore the breast cancer dataset
- Train a Gaussian Naive Bayes classifier
- Predict tumor type
- Evaluate model performance
- Compare actual vs predicted values

---

# 📂 Dataset

This project uses the built-in **Breast Cancer Wisconsin Diagnostic Dataset** available in Scikit-learn.

### Dataset Information

| Feature | Value |
|----------|--------|
| Samples | 569 |
| Features | 30 |
| Classes | 2 |
| Target | Malignant / Benign |
| Missing Values | None |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

# ⚙ Machine Learning Algorithm

The project uses:

## Gaussian Naive Bayes

Naive Bayes is a probabilistic machine learning algorithm based on Bayes' Theorem. GaussianNB assumes numerical features follow a Gaussian (Normal) distribution.

Advantages:

✔ Fast

✔ Simple

✔ Works well on small datasets

✔ Excellent baseline classifier

---

# 🔍 Workflow

Dataset

⬇

Load Breast Cancer Dataset

⬇

Convert to DataFrame

⬇

Feature Selection

⬇

Train-Test Split

⬇

Gaussian Naive Bayes Training

⬇

Prediction

⬇

Performance Evaluation

---

# 📊 Model Performance

## Accuracy

**97.37%**

---

## Confusion Matrix

| Actual | Predicted |
|---------|-----------|
| TN = 40 | FP = 3 |
| FN = 0 | TP = 71 |

---

## Classification Report

| Metric | Malignant | Benign |
|----------|-----------|---------|
| Precision | 1.00 | 0.96 |
| Recall | 0.93 | 1.00 |
| F1-Score | 0.96 | 0.98 |

Overall Accuracy:

**97.37%**

---

# 📸 Output Screenshots

Add screenshots inside the **images/** folder.

```
images/

accuracy.png

confusion_matrix.png

classification_report.png

prediction_output.png

dataset_preview.png
```

Example:

```md
## Dataset Preview

![Dataset](images/dataset_preview.png)

## Accuracy

![Accuracy](images/accuracy.png)

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

## Classification Report

![Report](images/classification_report.png)

## Prediction

![Prediction](images/prediction_output.png)
```

---

# 📁 Project Structure

```
Breast-Cancer-Tumor-Classification/

│

├── Breast_Cancer_Classification.ipynb

├── README.md

├── requirements.txt

├── .gitignore

├── LICENSE

└── images/

```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Breast-Cancer-Tumor-Classification.git
```

Move inside project

```bash
cd Breast-Cancer-Tumor-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Run all notebook cells.

---

# 📈 Results

✔ Model Accuracy: **97.37%**

✔ No Missing Values

✔ Gaussian Naive Bayes Classifier

✔ Efficient Tumor Classification

---

# 🔮 Future Improvements

- Hyperparameter tuning
- Feature selection techniques
- Cross-validation
- Compare multiple classifiers
- Deploy using Streamlit
- Build a web application

---

# 👩‍💻 Author

**Shreya Patil**

Data Science & Machine Learning Enthusiast

---

⭐ If you found this project useful, don't forget to Star this repository.
