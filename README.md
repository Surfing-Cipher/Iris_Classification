# Iris_Classification
Iris Flower Classification using Scikit-Learn | Logistic Regression, KNN, Decision Tree &amp; SVM | Model Evaluation with Confusion Matrix &amp; F1 Score | Pickle Model Saving

# Why All Models Show 100% Accuracy on the Iris Dataset
Reason:
The Iris dataset is:
  ➥ Small (only 150 samples)
  ➥ Well-balanced across the 3 classes
  ➥ Has clearly separable features (especially petal length & width)
That’s why even simple models like KNN or Logistic Regression can achieve nearly perfect accuracy on test sets especially when: 
  ➥ they use scaled data 
  ➥ having a good random state for train-test splitting

Hence 100% accuracy isn't a red flag here — it just means the dataset is ideal for classification, and models can easily distinguish classes like Setosa, Versicolor, and Virginica.
However, in real-world datasets, you'd usually see lower and more varied scores.


This project classifies iris flower species using four popular machine learning models:
- ✅ Logistic Regression
- ✅ K-Nearest Neighbors (KNN)
- ✅ Decision Tree
- ✅ Support Vector Machine (SVM)

Each model was evaluated using **confusion matrix**, **classification report**, and **F1-score bar chart** for deeper performance insights.

## 📊 What’s Inside

- **📁 Dataset**: Iris dataset from UCI (includes sepal & petal length/width)
- **📌 Preprocessing**: 
  - Feature scaling with `StandardScaler`
  - Train-test split using `train_test_split`  
- **📈 Visualizations**:
  - Scatter plot of Sepal Length vs Width by Species
  - Heatmap of feature correlation
- **🧠 Models**:
  - Trained & compared: Logistic Regression, KNN, Decision Tree, SVM
  - All models achieved high accuracy due to the clean and separable dataset
- **🧮 Evaluation**:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1)
  - Bar chart for F1-scores

## 💾 Model Saving
All trained models and the scaler were saved using Python's `pickle` module for future use without retraining.

## ▶️ Try It Yourself
Open the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xW_LP7eqA25Dg9DMJW3YCdpxdTuNfTif)
