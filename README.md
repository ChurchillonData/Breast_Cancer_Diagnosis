#  Breast Cancer Diagnosis using Logistic Regression

This project presents a machine learning solution for classifying breast cancer tumors (benign or malignant) using the **Breast Cancer Wisconsin Diagnostic Dataset**. The model is built using **Logistic Regression**, with key emphasis on performance evaluation and feature interpretation for medical decision support.

## 📊 Dataset
- **Features**: 30 numeric features derived from digitized images of fine needle aspirate (FNA) of breast masses
- **Target**: Binary classification — `M` (Malignant) or `B` (Benign)

## 🔧 Tools & Libraries

- Python  
- pandas, numpy  
- seaborn, matplotlib
- Logistic regression
- scikit-learn

## ⚙️ Project Workflow

1. **Data Loading & Preprocessing**  
   - Handled missing values  
   - Encoded categorical variables  
   - Standardized numerical features

2. **Exploratory Data Analysis (EDA)**  
   - Feature distribution and correlation heatmaps  
   - Class imbalance checks  
   - Outlier analysis

3. **Model Development**  
   - Applied Logistic Regression for binary classification  
   - Evaluated model using accuracy, precision, recall, F1-score, and ROC-AUC

4. **Results & Interpretation**  
   - Identified top features contributing to tumor classification  
   - Visualized confusion matrix and ROC curve

## ✅ Results

- Achieved high classification accuracy (insert your score here)
- ROC-AUC score: (insert ROC value)
- Model demonstrated strong generalizability and interpretability, making it suitable for healthcare diagnostic use cases.

## 📌 Key Learning Outcomes

- Applied supervised learning to a real-world healthcare dataset  
- Practiced model interpretability in a clinical context  
- Understood ethical implications of ML in medical decision-making

## 📁 Files

- `Breast_Cancer_Wisconsin_Diagnosis_using_Logistic_Regression.ipynb`: Main project notebook  
- `README.md`: Project documentation  
- `requirements.txt` (optional): List of dependencies for reproducibility

## 🧠 Future Improvements

- Explore tree-based models (e.g. Random Forest, XGBoost) for performance comparison  
- Address class imbalance using SMOTE or class weights  
- Deploy model as a Flask web API for real-time diagnosis



