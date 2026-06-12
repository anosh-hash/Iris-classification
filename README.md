# 🌸 Iris Flower Species Classification

A beginner-friendly Machine Learning project that classifies Iris flowers into three species —
**Setosa**, **Versicolor**, and **Virginica** — using petal and sepal measurements.

---

## 📌 Project Overview

| Item | Detail |
|------|--------|
| **Dataset** | Iris Dataset (150 samples, 4 features) |
| **Task** | Multi-class Classification |
| **Best Model** | SVM (RBF Kernel) – 96.67% accuracy |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |

---

## 🗂️ Repository Structure

```text
Iris-classification/
│
├── Iris classification.ipynb   ← Main Jupyter Notebook
├── Iris.csv                    ← Dataset file
├── Requirements.txt            ← Python dependencies
└── README.md                   ← Project documentation
```

---

## 🚀 How to Run

### Option 1: Google Colab *(Recommended)*
1. Open the notebook directly in [Google Colab](https://colab.research.google.com/).
2. Upload `Iris.csv` when prompted.
3. Run all cells sequentially.

### Option 2: Jupyter Notebook (Local)

**Step 1 – Clone this repository**
```bash
git clone https://github.com/anosh-hash/Iris-classification.git
cd Iris-classification
```

**Step 2 – Install dependencies**
```bash
pip install -r Requirements.txt
```

**Step 3 – Launch Jupyter Notebook**
```bash
jupyter notebook "Iris classification.ipynb"
```

---

## 📊 Project Workflow

| Step | Description |
|------|-------------|
| 1 | Import all required libraries |
| 2 | Load the Iris CSV dataset |
| 3 | Explore data (shape, types, missing values) |
| 4 | Visualise feature relationships with scatter plots & heatmap |
| 5 | Encode labels and split data (80% train / 20% test) |
| 6 | Train 4 classification models |
| 7 | Compare model accuracy |
| 8 | Print detailed classification report |
| 9 | Plot confusion matrix |
| 10 | Show feature importances (Random Forest) |
| 11 | Predict species for a new flower sample |

---

## 🤖 Models Compared

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 93.33% |
| Decision Tree | 90.00% |
| Random Forest | 90.00% |
| **SVM (RBF Kernel)** | **96.67% ✅** |

---

## 📈 Key Findings

- **Petal Length** and **Petal Width** are the most important features (~90% of importance).
- **Iris-Setosa** is clearly separable from the other two species.
- **SVM with RBF Kernel** achieved the highest accuracy of **96.67%**.
- The dataset is perfectly balanced — 50 samples per species.

---

## 🔧 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install all at once:
```bash
pip install -r Requirements.txt
```

---

## 📚 Concepts Covered

- Data loading and exploration with **Pandas**
- Data visualisation with **Matplotlib** and **Seaborn**
- Feature scaling with **StandardScaler**
- Train/test split with **stratified sampling**
- Classification models: Logistic Regression, Decision Tree, Random Forest, SVM
- Model evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 👤 Author

**Anosh S**  
Internship Project – Machine Learning  
[GitHub](https://github.com/anosh-hash)
