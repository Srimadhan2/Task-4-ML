Task-4-ML
# 🧠 Binary Classification with Logistic Regression

This project is part of the AI & ML Internship — Task 4: Classification. The goal is to build a **binary classification model using Logistic Regression** on the Breast Cancer Wisconsin dataset.

## 📌 Task Objective

- Use logistic regression to classify tumors as **malignant (M)** or **benign (B)**.
- Evaluate model performance using metrics like **confusion matrix, precision, recall, ROC-AUC**, and visualize the **ROC curve**.
- Experiment with different **classification thresholds** and explain the use of the **sigmoid function**.



## 📂 Dataset Used

**Dataset:** [Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

- 30 numeric features.
- Diagnosis column: 'M' = malignant, 'B' = benign.
- 

## 🧪 Tools & Libraries

- `Pandas` for data manipulation
- `Scikit-learn` for model building and evaluation
- `Matplotlib` & `Seaborn` for visualization
- `LogisticRegression`, `StandardScaler`, and performance metrics from `sklearn`


## 🛠️ Steps Performed

1. **Data Loading & Cleaning**  
   - Removed non-informative columns like `id` and unnamed columns.
   - Encoded `diagnosis` column: 'M' → 1, 'B' → 0.

2. **Feature Standardization**  
   - Applied `StandardScaler` to normalize features.

3. **Model Training**  
   - Trained a `LogisticRegression` model using the training data.

4. **Evaluation Metrics**  
   - Confusion Matrix  
   - Precision & Recall  
   - ROC-AUC Score  
   - ROC Curve plotted using `matplotlib`

5. **Threshold Tuning**  
   - Demonstrated how changing the classification threshold affects predictions.

---

## 📈 Evaluation Results

| Metric           | Value (Example Output) |
|------------------|------------------------|
| Accuracy         | 96.49%                 |
| Precision        |
