# Breast Cancer Prediction using Machine Learning

## Project Overview
This project focuses on building an end-to-end Machine Learning pipeline to classify breast tumors as **malignant** or **benign** using the Wisconsin Breast Cancer Dataset. The workflow includes data preprocessing, exploratory data analysis (EDA), model training, hyperparameter tuning, and performance evaluation using multiple classification metrics.

The objective of the project is to develop a robust predictive model that can assist in early cancer diagnosis by identifying patterns in cell nuclei measurements.

---

## Dataset
- **Dataset:** Wisconsin Breast Cancer Dataset
- **Source:** Scikit-learn Built-in Dataset
- **Samples:** 569
- **Features:** 30 numerical features
- **Target Classes:**
  - Malignant (1)
  - Benign (0)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- UMAP
- Joblib

---

## Project Workflow

### 1. Data Exploration & Visualization
- Performed Exploratory Data Analysis (EDA)
- Analyzed feature distributions using histograms and boxplots
- Conducted correlation analysis to identify important features
- Used UMAP for dimensionality reduction and cluster visualization

### 2. Data Preprocessing
- Handled missing values using `SimpleImputer`
- Applied feature scaling using `StandardScaler`
- Built preprocessing pipelines using Scikit-learn

### 3. Model Building
Implemented and compared multiple classification models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 4. Model Evaluation
Evaluated models using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Cross Validation

### 5. Hyperparameter Tuning
- Used `GridSearchCV` with 5-fold cross-validation
- Tuned Random Forest parameters for optimal performance

---

## Results
- **Best Model:** Random Forest Classifier
- **Test Accuracy:** ~97.4%
- **ROC-AUC Score:** ~0.996

The model demonstrated excellent classification performance with very high separability between malignant and benign tumor classes.

---

## Key Insights
- Feature scaling significantly improved model stability.
- Cross-validation helped detect overfitting in Decision Trees.
- Random Forest achieved the best generalization performance.
- Important predictive features included:
  - Worst Radius
  - Worst Perimeter
  - Worst Concave Points

---


