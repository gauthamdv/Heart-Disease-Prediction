# ❤️ Heart Disease Prediction

## 🚀 Project Overview

This project predicts the risk of **heart disease** using patient health data. It implements multiple **machine learning models**, compares their performances, and identifies the best approach for prediction.

The project is split into two main analyses:

1. **Decision Trees vs Random Forests** – Basic model comparison.
2. **Other Classification Models** – Advanced comparison across multiple models, including cross-validation and hyperparameter tuning.

---

## 🛠️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/gauthamdv/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### 2️⃣ Install requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the data

Run the preprocessing script to clean and prepare the dataset stored in the `datasets/` folder:

```bash
python data-preprocessing.py
```

### 4️⃣ Run the Notebooks

#### a) Decision Trees vs Random Forest

Open the notebook `decisionTrees-vs-randomForest.ipynb`. This notebook compares **Decision Tree** and **Random Forest** performance.

* **Data:** `datasets/`
* **Models saved in:** `models/models_dr/`
* **Plots saved in:** `plots/plots_dr/`

#### b) Other Classification Models

Open the notebook `other-models.ipynb`. This notebook compares several classification algorithms across:

* Normal training

* Cross-validation

* Hyperparameter tuning

* **Models saved in:** `models/models_all/`

* **Plots saved in:** `plots/plots_all/`

---

## 📁 File Structure

```text
Heart-Disease-Prediction/
│
├─ datasets/                  # Raw and processed datasets
├─ models/
│  ├─ models_dr/              # Models from decision tree vs random forest notebook
│  └─ models_all/             # Models from other-models notebook
├─ plots/
│  ├─ plots_dr/               # Plots from decision tree vs random forest notebook
│  └─ plots_all/              # Plots from other-models notebook
├─ data-preprocessing.py      # Script for data cleaning and feature engineering
├─ decisionTrees-vs-randomForest.ipynb  # First notebook comparing Decision Tree and Random Forest
├─ other-models.ipynb         # Notebook comparing all other classification models
├─ requirements.txt           # Python dependencies
└─ README.md                  # Project documentation (this file)
```

---

## 📊 Models & Evaluation

* **Decision Trees vs Random Forests:** Basic comparison using accuracy and visualizations.
* **Other Models:** Includes multiple classifiers with cross-validation and hyperparameter tuning to find the **best model**.
* Plots are provided to visualize model performance, feature importance, and metrics.

---

## ⚡ Usage

1. Prepare the data using `data-preprocessing.py`.
2. Run `decisionTrees-vs-randomForest.ipynb` to see simple model comparisons.
3. Run `other-models.ipynb` to evaluate all classifiers, tune hyperparameters, and select the best model.
4. Check saved plots and models in their respective folders for results.

---

## 🤝 Contributions

Contributions are welcome! If you want to improve the repository, feel free to open a pull request or report issues.

---
