# 🌸 Iris Flower Classification

## 📌 Project Overview

Iris Flower Classification is a machine learning classification project that predicts the species of an iris flower based on its sepal and petal measurements.

The model classifies flowers into three species:

* **Setosa**
* **Versicolor**
* **Virginica**

This project demonstrates the complete machine learning workflow from data exploration and visualization to model training, evaluation, and prediction.

---

## 🎯 Objective

To build a machine learning model that can accurately classify iris flowers into their respective species using:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 📊 Dataset

The classic **Iris Dataset** available through Scikit-learn is used in this project.

The dataset contains:

* **150 samples**
* **4 numerical features**
* **3 flower species**
* **50 samples per species**

### Features

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |

### Target

The target variable represents the flower species:

* Setosa
* Versicolor
* Virginica

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```text
Iris Dataset
     ↓
Data Loading
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Data Visualization
     ↓
Train/Test Split
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Confusion Matrix
     ↓
Flower Species Prediction
```

---

## 🤖 Machine Learning Models

Three classification algorithms were implemented:

### 1. Logistic Regression

Used as a simple and effective baseline classification model.

### 2. K-Nearest Neighbors (KNN)

Classifies a flower based on the characteristics of nearby training samples.

### 3. Decision Tree

Uses a tree-based structure to make classification decisions based on feature values.

---

## 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The project also compares the performance of all three models.

---

## 📊 Exploratory Data Analysis

The project includes:

* Dataset information
* Statistical summary
* Missing-value checking
* Duplicate-value checking
* Class distribution
* Pair plot
* Scatter plots
* Correlation heatmap

These visualizations help understand relationships between flower measurements and species.

---

## 🔮 Prediction

The trained models can predict the species of a new iris flower using its:

```text
Sepal Length
Sepal Width
Petal Length
Petal Width
```

Example:

```text
Input:
[5.1, 3.5, 1.4, 0.2]

Prediction:
Setosa
```

---

## 📁 Project Structure

```text
iris-flower-classification/
│
├── iris_flower_classification.ipynb
├── processed_iris_dataset.csv
└── README.md
```

---

## ▶️ How to Run

### Option 1 — Google Colab

1. Download `iris_flower_classification.ipynb`
2. Open Google Colab
3. Select **File → Upload notebook**
4. Upload the notebook
5. Select **Runtime → Run all**

No separate dataset upload is required because the Iris dataset is loaded directly from Scikit-learn.

---

## 💡 Key Learnings

Through this project, I learned:

* How to explore a classification dataset
* Data visualization using Matplotlib and Seaborn
* Train/test splitting
* Feature scaling
* Classification algorithms
* Model evaluation
* Confusion matrix analysis
* Comparing multiple ML models
* Making predictions using trained models

---

## 🚀 Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Random Forest classification
* Support Vector Machine (SVM)
* Interactive prediction interface
* Streamlit web application
* Model deployment

---

## 👨‍💻 Author

**Manav Verma**

B.Tech CSE (AI)

GitHub: [Add your GitHub profile link here]

LinkedIn: [Add your LinkedIn profile link here]

---

## ⭐ Conclusion

This project provides a practical implementation of a complete machine learning classification pipeline using the Iris dataset. Multiple classification algorithms are trained and compared to identify the most suitable model for predicting iris flower species.
