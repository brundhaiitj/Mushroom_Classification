# 🍄 Mushroom Classification using Machine Learning

This project focuses on classifying mushrooms as **edible** or **poisonous** using machine learning techniques. It uses a dataset of mushroom characteristics and explores various preprocessing, dimensionality reduction, and classification models.

---
## Files

* `mushroom_classification.py` – Code notebook
* `IML PROJECT.pdf` – Full report
* `README.md` – Project summary
* `Mushroom_Classification.pptx` – Project Presentation
* `mushrooms.csv` – Dataset

---

## Dataset Overview

* **Source**: UCI Machine Learning Repository
* **Instances**: 8124
* **Attributes**: 23 categorical features including:

  * `cap-shape`, `cap-color`, `gill-size`, `odor`, `spore-print-color`, etc.
* **Target Variable**: `class` (edible or poisonous)

---

## Preprocessing

* **Missing Values**: None
* **Duplicates**: None
* **Encoding**: Ordinal Encoding used to convert categorical features into numeric format

---

## Classification Models & Results

| Model                   | Accuracy (%) |
| ----------------------- | ------------ |
| K-Nearest Neighbors     | **99.91**    |
| SVM (RBF Kernel)        | **100.0**    |
| Logistic Regression     | 94.67        |
| Decision Tree (Gini)    | 96.14        |
| Decision Tree (Entropy) | 95.85        |

**Best Performers**:

* **KNN** and **SVM (RBF)** consistently achieved near-perfect classification performance.

---

## Model Evaluation

* Evaluation Metrics:

  * **Accuracy**
  * **Precision**
  * **Recall**
  * **F1-Score**
* Confusion Matrices analyzed for each model
* Cross-validation used for hyperparameter tuning (e.g., K in KNN)

---

## Key Findings

* Outlier removal significantly improved LDA performance
* PCA effectively reduced dimensionality while retaining most variance
* KNN and SVM are robust classifiers for this dataset
* Logistic Regression performed well despite the dataset's complexity
* Decision Trees offer good interpretability with high accuracy

---

## Technologies Used

* Python
* NumPy, Pandas, Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook
