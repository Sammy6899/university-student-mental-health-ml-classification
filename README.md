# University Student Mental Health Analysis & Depression Classification

An end-to-end machine learning study analyzing the impact of academic pressure, CGPA, demographic factors, and stress levels on university students' mental health.

## 📌 Project Overview
This project uses survey data from university students to explore factors contributing to academic anxiety, stress, and depression. Multiple supervised classification models are trained to predict depression severity levels, alongside unsupervised clustering and dimensionality reduction (PCA) to discover underlying behavioral patterns.

## 📊 Dataset Highlights
- **Samples**: 1,977 student responses
- **Features**: 37 columns (demographics, GPA, academic year, and Likert-scale questions assessing anxiety, stress, and depressive symptoms)
- **Target**: `Depression Label` (No Depression, Minimal, Mild, Moderate, Moderately Severe, Severe)

## 🛠️ Tech Stack & Libraries
- **Language**: Python 3.x
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`
  - *Preprocessing*: `ColumnTransformer`, `StandardScaler`, `OneHotEncoder`, `SimpleImputer`
  - *Models*: Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN), Multi-Layer Perceptron (MLP)
  - *Unsupervised*: K-Means Clustering, PCA

## 🚀 Workflow
1. **Exploratory Data Analysis (EDA)**: Analyzed feature distributions, missing values, and depression class frequencies.
2. **Preprocessing Pipeline**: Handled categorical and continuous features systematically using Scikit-Learn pipelines to prevent data leakage.
3. **Model Training & Comparison**: Evaluated multiple classifiers using Accuracy, Precision, Recall, F1-score, and Confusion Matrices.
4. **Clustering & PCA**: Projected high-dimensional survey responses onto 2D/3D components to inspect latent student groupings.

## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/Sammy6899/student-mental-health-ml.git](https://github.com/Sammy6899/student-mental-health-ml.git)
   cd student-mental-health-ml

## 👤 Author & Acknowledgments

- **Developer:** Samiha Tasnim Orthi, Sumaiya Zaman
- **Course:** CSE422 - Machine Learning
