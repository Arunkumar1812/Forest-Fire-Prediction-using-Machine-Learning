# 🔥 Forest Fire Prediction using Machine Learning

## 📌 Project Overview

This project predicts the occurrence of forest fires using meteorological data from the UCI Forest Fires dataset. It demonstrates an end-to-end Machine Learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, hyperparameter tuning, and model evaluation.

The goal is to classify whether a forest fire is likely to occur based on weather conditions such as temperature, humidity, wind, and rainfall.

---

## 🎯 Problem Statement

Forest fires can have severe environmental and economic impacts. Predicting fire occurrence using meteorological data can help support early detection and prevention efforts.

This project aims to build a Binary Classification model that predicts the likelihood of a forest fire using historical weather data.

**Problem Type:** Binary Classification

---

## 📂 Dataset

- **Dataset:** UCI Forest Fires Dataset
- **Dataset Type:** Tabular Dataset
- **Target Variable:** Forest Fire Occurrence (Binary)

### Features

- X
- Y
- Month
- Day
- FFMC
- DMC
- DC
- ISI
- Temperature
- Relative Humidity (RH)
- Wind
- Rain
- Burned Area

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📋 Project Workflow

### 1. Data Collection
- Imported required Python libraries.
- Loaded the UCI Forest Fires dataset.

### 2. Data Cleaning
- Checked for missing values.
- Removed duplicate records.
- Corrected inconsistent data.
- Applied Z-score Outlier Detection.

### 3. Exploratory Data Analysis (EDA)
- Statistical summary
- Feature distribution
- Correlation analysis
- Weather pattern visualization
- Target class analysis

### 4. Feature Engineering
- Created a Binary Classification target.
- Selected important weather features.
- Applied Feature Scaling.

### 5. Model Building
Implemented the following Machine Learning model:

- Random Forest Classifier

### 6. Hyperparameter Tuning
Optimized the model using **RandomizedSearchCV**.

Parameters tuned include:
- n_estimators
- max_depth
- min_samples_split
- min_samples_leaf
- max_features

### 7. Model Evaluation
Performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

- Feature Distribution
- Correlation Heatmap
- Temperature vs Fire Occurrence
- Humidity vs Fire Occurrence
- Wind Analysis
- Rainfall Analysis
- Feature Importance

---

## 📈 Key Insights

- Temperature is the strongest indicator of forest fire occurrence.
- Relative Humidity significantly affects fire risk.
- Wind speed contributes to fire spread.
- Rainfall generally reduces the probability of fire occurrence.
- Hyperparameter tuning improved the prediction performance.

---

## 🤖 Machine Learning Model

| Model | Purpose |
|--------|----------|
| Random Forest Classifier | Binary Classification |

---

## 📁 Project Structure

```text
Forest-Fire-Prediction/
│
├── Dataset/
│   └── forestfires.csv
│
├── Notebook/
│   └── Forest_Fire_Prediction.ipynb
│
├── Images/
│   └── visualizations
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🚀 Future Improvements

- Compare multiple classification algorithms.
- Deploy the model using Streamlit or Flask.
- Perform advanced Feature Engineering.
- Handle class imbalance using SMOTE.
- Integrate live weather data for real-time predictions.

---

## 🎓 Learning Outcomes

This project helped strengthen my understanding of:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Classification
- Hyperparameter Tuning
- Model Evaluation
- End-to-End Machine Learning Pipeline

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be used to predict forest fire occurrence using meteorological data. By leveraging weather features and an optimized Random Forest Classifier, the model provides valuable insights that can support wildfire prevention and decision-making.

---

## 👨‍💻 Author

**Arun Kumar T**

- GitHub: *(Add your GitHub profile link here)*
- LinkedIn: *(Add your LinkedIn profile link here)*

---

⭐ If you found this project useful, don't forget to **Star** the repository!
