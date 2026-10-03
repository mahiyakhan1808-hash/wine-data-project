# 🍷 Wine Classification using KNN

## 📌 Project Overview

This project demonstrates a **Wine Classification Machine Learning model** using the **K-Nearest Neighbors (KNN)** algorithm.

The project uses the built-in **Wine dataset** from Scikit-learn. The dataset contains 13 different features that are used to classify wines into different target classes.

## 🎯 Objective

The main objective of this project is to:

* Load the Wine dataset
* Prepare the data for machine learning
* Split the dataset into training and testing sets
* Standardize the features
* Train a K-Nearest Neighbors classifier
* Predict wine classes
* Evaluate the model using a confusion matrix and classification report

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## 📊 Dataset

The project uses the **Wine dataset** available in `sklearn.datasets`.

The dataset contains **13 input features** and a target variable representing the wine class.

## 🔄 Machine Learning Workflow

```text
Wine Dataset
     ↓
DataFrame Creation
     ↓
Feature & Target Selection
     ↓
Train-Test Split
     ↓
Feature Standardization
     ↓
KNN Model Training
     ↓
Prediction
     ↓
Model Evaluation
```

## 🧠 Model Used

### K-Nearest Neighbors (KNN)

The project uses the `KNeighborsClassifier` with:

```python
KNeighborsClassifier(n_neighbors=20)
```

The model is trained using the standardized training data.

## ⚙️ Data Preprocessing

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

using `train_test_split`.

Feature scaling is performed using `StandardScaler` before training the KNN model.

## 📈 Model Evaluation

The model predictions are evaluated using:

### Confusion Matrix

```python
confusion_matrix(y_test, y_pred)
```

### Classification Report

```python
classification_report(y_test, y_pred)
```

These metrics are used to evaluate the classification performance of the model.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/wine-classification.git
```

### 2. Navigate to the Project Folder

```bash
cd wine-classification
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 4. Run the Python File

```bash
python 2_oct_wine_classification.py
```

You can also run the project in **Google Colab** or **Jupyter Notebook**.

## 📁 Project Structure

```text
wine-classification/
│
├── 2_oct_wine_classification.py
├── README.md
└── requirements.txt
```

## 📌 Key Concepts

* Data preprocessing
* Train-test splitting
* Feature scaling
* KNN classification
* Machine learning prediction
* Confusion matrix
* Classification report

## 🔮 Future Improvements

* Try different values of `K`
* Compare KNN with other classification algorithms
* Perform cross-validation
* Add data visualization
* Compare model accuracy using different algorithms

## 👩‍💻 Author

**Mahiya Khan**

### ⭐ If you found this project useful, consider giving the repository a star!
