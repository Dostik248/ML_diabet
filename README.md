# 🧠 Machine Learning Classification Project

## 💊 Drug Recommendation System using Decision Tree

Imagine you are a medical researcher collecting data from patients suffering from the same disease. During treatment, **one of five different drugs** produced a positive response for each patient.

🎯 **Project Goal**
Build a machine learning model that can **recommend the most suitable drug** for a future patient with the same condition.

This task is a **multiclass classification problem**, solved using the **Decision Tree algorithm**.

---

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Educational-lightgrey.svg)

---

## 📖 Project Overview

This repository implements a **Decision Tree–based classification model** to recommend drugs based on patient attributes. The project is designed to be **beginner-friendly** and suitable for learning core Machine Learning concepts such as:

* Feature-based decision making
* Multiclass classification
* Model evaluation

---

## 📋 Dataset Features

The dataset contains the following patient features:

| Feature         | Description                          |
| --------------- | ------------------------------------ |
| **Age**         | Age of the patient                   |
| **Sex**         | Gender (Male / Female)               |
| **BP**          | Blood Pressure (Low / Normal / High) |
| **Cholesterol** | Cholesterol level (Normal / High)    |
| **Na_to_K**     | Sodium-to-Potassium ratio            |

🎯 **Target Variable:**

* **Drug** — the recommended drug category (5 classes)

---

## 🌳 How Decision Tree Works

A Decision Tree predicts outcomes by asking a sequence of simple, interpretable questions:

* **Nodes** represent conditions (e.g., `BP = High?`)
* **Branches** represent decision outcomes
* **Leaf nodes** represent final predictions (drug type)

### ✅ Advantages

* Easy to understand and interpret
* Works well for multiclass problems
* Can be visualized for better insight

---

## 📈 Model Evaluation

Model performance is evaluated using standard classification metrics:

### Accuracy

Measures the proportion of correct predictions:

```
Accuracy = Correct Predictions / Total Predictions
```

### Confusion Matrix

Shows how well the model predicts each drug class and where misclassifications occur.

---

## 🧠 Prediction Example

**New Patient Data:**

* Age: 47
* Sex: Male
* BP: High
* Cholesterol: High
* Na_to_K: 15.0

👉 **Model Prediction:** `DrugY` *(example output)*

---

## 📁 Project Structure

```
project/
│
├── data/
│   ├── raw/            # Original dataset
│   └── processed/      # Preprocessed dataset
│
├── notebooks/
│   └── decision_tree.ipynb
│
├── src/
│   └── model.py        # Model training & prediction
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

## 🛠 Requirements

The project uses the following Python packages:

```txt
numpy
pandas
scikit-learn
matplotlib
graphviz
```

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🌳 Decision Tree Visualization

The trained Decision Tree can be visualized using **Graphviz**, which helps understand how decisions are made.

The visualization shows:

* Feature-based splits
* Decision thresholds
* Final drug recommendations at leaf nodes

This makes the model highly interpretable, which is especially important in medical applications.

---

## 📊 Model Results (from Notebook)

Based on experiments in the Jupyter Notebook:

* **Accuracy:** ~97% (may vary depending on train/test split)
* The model performs well across all 5 drug classes
* Minimal confusion between similar drug categories

These results indicate that the Decision Tree is effective for this classification task.

---

## ▶️ How to Run

1. Clone this repository
2. Install required packages
3. Open and run the notebook in `notebooks/`

---

## 📝 Conclusion & Future Work

### Conclusion

In this project, we successfully built a **Decision Tree–based multiclass classification model** to recommend drugs based on patient data. The model is accurate, interpretable, and suitable for educational and healthcare-related use cases.

### Future Work

Possible improvements include:

* Using ensemble methods (Random Forest, Gradient Boosting)
* Hyperparameter tuning for better generalization
* Adding cross-validation
* Deploying the model as a web application

---

## 🎯 Use Cases

* Drug recommendation systems
* Healthcare decision support tools
* Learning Decision Tree classification

---

## 👤 Author

**Dostonjon**

---

⭐ If you find this project useful, please give it a star on GitHub!
