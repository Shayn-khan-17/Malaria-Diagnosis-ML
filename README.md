# 🦠 Malaria Diagnosis Using Machine Learning

A machine learning project for classifying malaria cell images using traditional supervised learning algorithms.

This project explores the application of **Logistic Regression** and **Support Vector Machine (SVM)** algorithms to the classification of malaria cell images. The goal is to investigate how classical machine learning techniques can be applied to medical image classification.

---

## 📌 Project Overview

Malaria diagnosis traditionally involves examining blood-smear samples under a microscope to identify infected cells.

In this project, a **malaria cell image dataset** is used to develop machine learning-based classification models.

The workflow includes:

```text
Malaria Cell Images
        ↓
Image Preprocessing
        ↓
Feature Extraction / Representation
        ↓
Train-Test Split
        ↓
Machine Learning Models
        ↓
Prediction & Evaluation
```

Two machine learning approaches are explored:

* **Logistic Regression**
* **Support Vector Machine (SVM)**

---

## 🎯 Objectives

The main objectives of this project are:

* Apply machine learning techniques to malaria cell classification.
* Explore preprocessing of microscopic cell images.
* Train Logistic Regression and SVM classifiers.
* Compare the performance of different machine learning approaches.
* Understand the applicability of classical ML algorithms to medical image analysis.

---

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression is a supervised classification algorithm that estimates the probability of an input belonging to a particular class.

In this project, it is used as a baseline machine learning classifier for malaria cell classification.

**Advantages:**

* Simple and efficient
* Easy to interpret
* Fast to train
* Useful as a baseline classification model

---

### 2. Support Vector Machine (SVM)

Support Vector Machine is a supervised learning algorithm that finds an optimal decision boundary between different classes.

SVM can be particularly useful when the input feature space is high-dimensional.

In this project, SVM is used to classify malaria cell images based on their extracted feature representations.

**Advantages:**

* Effective in high-dimensional feature spaces
* Works well with relatively small datasets
* Can model complex decision boundaries using kernels

---

## 📂 Repository Structure

```text
Malaria-Diagnosis-ML/
│
├── logistic.ipynb
├── random.ipynb
└── README.md
```

### `logistic.ipynb`

Contains the implementation of the **Logistic Regression** approach for malaria cell classification.

### `random.ipynb`

Contains the machine learning experiment involving the **Support Vector Machine (SVM)** classifier.

> The notebook names can be renamed later to more descriptive names such as `logistic_regression.ipynb` and `svm.ipynb` to make the repository easier to understand.

---

## 📊 Dataset

The project uses a **malaria cell image dataset** for binary classification.

The dataset contains microscopic cell images representing different malaria-related classes.

The dataset is **not included in this repository**. You should download the dataset separately and update the dataset path inside the notebooks.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Machine Learning
* Computer Vision
* Medical Image Analysis

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Shayn-khan-17/Malaria-Diagnosis-ML.git
cd Malaria-Diagnosis-ML
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Linux/macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open either:

```text
logistic.ipynb
random.ipynb
```

---

## 🔬 Machine Learning Pipeline

The project follows a standard machine learning workflow:

### Step 1 — Data Collection

A malaria cell image dataset is used as the source of training and testing data.

### Step 2 — Data Preprocessing

The images are prepared for machine learning by converting them into suitable numerical representations.

Typical preprocessing operations include:

* Image resizing
* Normalization
* Label encoding
* Feature preparation

### Step 3 — Feature Representation

Machine learning algorithms such as Logistic Regression and SVM require numerical feature representations.

The processed images are therefore represented as numerical feature vectors before training.

### Step 4 — Model Training

The prepared dataset is used to train:

```text
Logistic Regression
        +
      SVM
```

### Step 5 — Evaluation

The trained models can be evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📈 Model Comparison

| Model               | Type                    | Purpose                                             |
| ------------------- | ----------------------- | --------------------------------------------------- |
| Logistic Regression | Linear Classifier       | Baseline classification                             |
| SVM                 | Margin-based Classifier | Classification using an optimized decision boundary |

The notebooks can be used to compare how these two algorithms perform on the malaria cell classification task.

---

## 🔍 Machine Learning vs Deep Learning

This project is part of a broader exploration of malaria diagnosis using different AI approaches.

### Machine Learning

This repository uses:

```text
Image
  ↓
Preprocessing
  ↓
Feature Representation
  ↓
Logistic Regression / SVM
  ↓
Prediction
```

### Deep Learning

The companion deep learning project uses neural network architectures such as CNN, CNN-LSTM, and Bi-LSTM to learn representations from images.

This makes the two projects useful for comparing **traditional machine learning approaches with deep learning approaches** for medical image classification.

---

## 🚀 Future Improvements

Possible improvements include:

* [ ] Add more classical ML algorithms such as Random Forest, KNN, and Decision Tree
* [ ] Perform systematic feature extraction
* [ ] Apply PCA for dimensionality reduction
* [ ] Perform hyperparameter optimization
* [ ] Add cross-validation
* [ ] Add confusion matrices
* [ ] Add ROC curves and AUC scores
* [ ] Compare precision, recall, and F1-score
* [ ] Create a complete model comparison table
* [ ] Compare classical ML models against CNN-based models
* [ ] Deploy the best model as a web application

---

## ⚠️ Medical Disclaimer

This project is intended **for educational and research purposes only**.

The predictions produced by these machine learning models should **not be considered a medical diagnosis**. Real-world malaria diagnosis should be performed using appropriate clinical and laboratory procedures by qualified healthcare professionals.

---

## 👨‍💻 Author

**Shayan Khan**

Computer Science Student
Machine Learning | Deep Learning | Computer Vision | Medical Image Analysis

### GitHub

[Shayn-khan-17](https://github.com/Shayn-khan-17)

---

## ⭐ Support

If you find this project useful for learning or research, consider giving the repository a ⭐.

---

## 📄 License

No license is currently specified for this repository. If you want others to freely use, modify, and distribute the project, consider adding an open-source license such as the MIT License.
