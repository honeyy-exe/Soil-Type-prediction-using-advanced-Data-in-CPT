# 🌍 Soil Type Classification using Machine Learning

## 📌 Overview
This project focuses on classifying soil types using Cone Penetration Test (CPT) data and machine learning techniques. A LightGBM classifier is used to predict soil classes based on geotechnical parameters.

---

## 📊 Dataset
The dataset includes the following features:
- Depth (m)
- Cone Penetration Resistance (qc)
- Sleeve Friction
- Friction Ratio
- Bulk Density
- Effective Vertical Stress
- Pore Water Pressure
- Normalized Cone Resistance
- Void Ratio
- Soil Class (Target)

---

## ⚙️ Methodology

### 🔹 Data Preprocessing
- Handled missing values using median imputation
- Removed duplicate and redundant features
- Cleaned column names
- Encoded categorical target variable

### 🔹 Exploratory Data Analysis
- Generated correlation heatmap
- Identified relationships between geotechnical parameters
- Detected feature redundancy

### 🔹 Model Training
- Used LightGBM Classifier
- Train-test split: 80-20
- Model trained on processed numerical features

---

## 📈 Results

- **Accuracy:** 97%
- Strong classification performance across all soil classes
- Minimal misclassification between similar soil types

### 📊 Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🧠 Key Insights
- Cone penetration resistance (qc) is a highly influential feature
- Friction ratio plays a crucial role in distinguishing soil types
- Some features showed high correlation and were removed to reduce redundancy

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- LightGBM

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Deployment as a web application
- Integration with real-time CPT data

---

## 📌 Conclusion
The model successfully classifies soil types with high accuracy, demonstrating the effectiveness of machine learning in geotechnical applications.

---

## 👩‍💻 Author
Your Name
