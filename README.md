# 🍄 Mushroom Classification (Group 46)

A machine learning project to classify mushrooms as **edible** or **poisonous** using supervised learning and dimensionality reduction techniques.

---

## 📊 Dataset

* **Source**: UCI Mushroom Dataset
* **Instances**: 8124
* **Features**: 22 categorical
* **Target**: `class` (edible or poisonous)

---

## 🔧 Preprocessing

* No missing or duplicate values
* Ordinal encoding for categorical variables
* Outliers removed using IQR method

---

## 📉 Dimensionality Reduction

* **PCA**: 9 components explained \~90.57% variance (after outlier removal)
* **LDA**: Improved class separation, accuracy up to 99.07%

---

## 🤖 Models & Accuracy

| Model         | Accuracy |
| ------------- | -------- |
| KNN           | 99.91%   |
| SVM (RBF)     | 100.0%   |
| Logistic Reg. | 94.67%   |
| Decision Tree | \~96%    |

Best performers: **KNN** and **SVM (RBF Kernel)**

---

## 📂 Files

* `Mushroom_Classification.py` – Code notebook
* `IML PROJECT.pdf` – Full report
* `README.md` – Project summary
* `Mushroom_Classification.pptx` – Project Presentation
* `mushroom.csv` – Dataset

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/mushroom-classification.git
cd mushroom-classification
jupyter notebook Mushroom_Classification_grp_46.ipynb
```
