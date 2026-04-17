#  Image Classification Using Random Forest

## 📌 Overview

This project implements an image classification system using the Random Forest algorithm. The goal is to classify images into different categories by applying classical machine learning techniques.

The workflow covers data preprocessing, model training, evaluation, and prediction on new images. A comparison with Support Vector Machine (SVM) is also included.

---

## 📂 Dataset

The dataset consists of images organized into folders, where each folder represents a class label.

* Source: Provided dataset (images.zip)
* Structure:

```
dataset/
   class1/
   class2/
   class3/
```

Each image is processed and converted into numerical format for model training.

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Extracted images from zip file
* Resized images to 64 × 64 pixels
* Normalized pixel values (0–1 range)
* Flattened images into feature vectors

### 2. Model Training

* Algorithm: Random Forest Classifier
* Hyperparameter tuning using GridSearchCV
* Parameters tuned:

  * n_estimators
  * max_depth
  * min_samples_split
  * min_samples_leaf

### 3. Model Evaluation

* Accuracy Score
* Precision, Recall, F1-score
* Confusion Matrix visualization

### 4. Feature Importance

* Extracted feature importance from Random Forest
* Visualized top contributing features

### 5. Prediction

* Implemented a function to classify new images using the trained model

### 6. Bonus

* Implemented Support Vector Machine (SVM) for comparison

---

## 📊 Results

* The Random Forest model achieved good classification performance.
* Hyperparameter tuning improved accuracy.
* Some misclassifications occurred due to similarity between image classes.
* SVM provided comparable results but required more tuning.

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone [https://github.com/ubong11/image_classification_RandomForest.git]
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Upload the dataset (images.zip).

4. Run all cells sequentially.

---


## 🧠 Key Insight

While Random Forest performs reasonably well, it does not capture spatial features in images effectively. Convolutional Neural Networks (CNNs) are more suitable for image classification tasks.

---

## 🔧 Tools & Libraries

* Python
* NumPy
* OpenCV
* Scikit-learn
* Matplotlib
* Seaborn
* Pickle

---

## 👤 Author

Ubong Ufot
GitHub: [https://github.com/ubong11]

---



---
