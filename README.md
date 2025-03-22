# 🌲 Diamond Tree Models: Decision Trees & Random Forests

This project demonstrates how to use **Decision Tree** and **Random Forest** models for both **regression** and **classification** tasks on the diamonds dataset.

We explore how diamond characteristics like dimensions and table size influence carat weight and cut quality.

---

## 📊 Project Objectives

- Predict **carat weight** using:
  - Decision Tree Regression
  - Random Forest Regression

- Classify **cut quality** (`Ideal` or not) using:
  - Decision Tree Classification
  - Random Forest Classification

---

## 📁 Dataset

- **Name**: Diamonds Dataset  
- **Source**: [Kaggle – Diamonds by Shivam Bansal](https://www.kaggle.com/datasets/shivam2503/diamonds)

> Download the dataset from [Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds) and place it in the `data/` folder as `diamonds.csv`.

---

## 🧪 Techniques Used

- Polynomial Feature Expansion (degree = 3)
- Data Standardization (`StandardScaler`)
- Tree-based Models:
  - `DecisionTreeRegressor` & `DecisionTreeClassifier`
  - `RandomForestRegressor` & `RandomForestClassifier`
- Model Evaluation:
  - R² Score
  - Confusion Matrix
  - Matthews Correlation Coefficient (MCC)
  - Classification Report
- Visualization:
  - `plot_tree` from `sklearn.tree`
  - `seaborn` heatmap for correlation analysis

---

## 🧱 Project Structure

```
diamond-tree-models/
│
├── data/
│   └── diamonds.csv
│
├── Diamond_Trees_Analysis.ipynb   # Full notebook with code & markdowns
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mgedna/diamond-tree-models.git
   cd diamond-tree-models
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset in `data/`:
   ```
   data/diamonds.csv
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook Diamond_Trees_Analysis.ipynb
   ```

---

## 👤 Author

**Edna Memedula**
📫 [LinkedIn](https://www.linkedin.com/in/edna-memedula-24b519245) • [GitHub](https://github.com/mgedna) 
