| **TITLE OF THE PROJECT** | **Explainable Classification Models for Medical Diagnosis Prediction** | |
| --- | --- | | --- |
| **S. No.** | **University ID** | **Name** |
| 1 | 2420090058 | Saraf Abhinav |
| 2 | 2420090104 | Jai Vardhan |
| 3 | 2420030418 | Srimaan |
| 4 | 2420030776 | Ananya |
| Name of the Guide | | Dr. K Swapnka |

**Abstract**

In the medical field, timely and accurate diagnosis is critical for patient survival and effective treatment planning. While machine learning (ML) models have demonstrated exceptional predictive capabilities in healthcare analytics, their clinical adoption is heavily hindered by the "black-box" nature of complex algorithms. Physicians cannot blindly trust an algorithm's diagnosis without understanding the underlying physiological and clinical features driving that decision. This project introduces a comprehensive framework leveraging Explainable Artificial Intelligence (XAI) to build transparent, high-performing classification models for medical diagnosis prediction. The research utilizes three distinct benchmark datasets—covering cardiovascular health, metabolic disorders, and oncology—to validate the framework across varying physiological conditions. The pipeline begins with rigorous data preprocessing to handle missing clinical records, encode categorical patient histories, and scale vital sign features. Following this, a robust Exploratory Data Analysis (EDA) phase uncovers hidden distributions, symptom correlations, and critical anomalies within the patient data. For predictive modeling, state-of-the-art algorithms including Logistic Regression, Decision Trees, Random Forests, XGBoost, and CatBoost are trained and rigorously evaluated using clinical-grade metrics like ROC-AUC, precision (to minimize false positives in diagnoses), and recall (to minimize false negatives). To bridge the gap between model accuracy and clinical interpretability, the framework integrates SHAP and LIME. These XAI techniques decode both global model behavior and local, patientspecific predictions, explicitly highlighting which symptoms, vital signs, or lab results most heavily influenced a specific diagnosis. The final deliverable includes an interactive visualization dashboard, providing a comparative analysis of the models and offering medical professionals an intuitive, trustworthy, and evidence-based diagnostic support tool.

**Approach:**

**Data Analytics**

**EDA → EDA Flow Diagram:**

- **Clinical Data Ingestion**
- **Patient Cohort Demographics Overview**
- **Medical Record Integrity & Data Quality Check**
- **Descriptive Biostatistics & Distribution Analysis**
- **Missing Laboratory Value Assessment**
- **Duplicate Patient Entry Resolution**
- **Physiological Outlier & Anomaly Detection**
- **Univariate Analysis of Key Biomarkers**
- **Bivariate Analysis (Clinical Features vs. Disease Target)**
- **Multivariate Health Risk Profiling**
- **Symptom & Feature Cross-Correlation**
- **Clinical Feature Engineering (e.g., BMI calculation, Risk Scores)**
- **Diagnostic Predictor Selection**

**Machine Learning Models The exploratory phase will utilize a minimum of 10 to 12 advanced multi-dimensional analytical methods to uncover hidden clinical patterns. This ensures a rigorous, mathematically sound foundation before any diagnostic model training begins, which is critical in a healthcare context.**

**Preprocessing**

- **Imputation of Missing Clinical Records**
- **Encoding of Categorical Medical Terminology**
- **Standardization of Vital Signs & Lab Values**

**ML Models**

- **Decision Tree (Transparent Baseline)**
- **Random Forest (Ensemble Approach)**
- **XGBoost (High-Performance Gradient Boosting)**
- **Logistic Regression (Traditional Clinical Benchmark)**

**Explainability**

- **SHAP (Global population-level feature importance)**
- **LIME (Local, patient-specific diagnostic reasoning)**

**Visualization**

- **Clinical Correlation Heatmaps**
- **Risk Factor Distribution Boxplots**
- **XAI Summary Plots (Beeswarm, Waterfall)**
- **Interactive Clinical Decision Support Dashboard**

**Comparative Analysis _Compare_**

- **Decision Tree**
- **Random Forest**
- **XGBoost**
- **CatBoost**

**_Metrics_**

- **Accuracy**
- **Precision (Positive Predictive Value)**
- **Recall (Sensitivity/True Positive Rate)**
- **F1-Score**
- **ROC-AUC (Area Under the Receiver Operating Characteristic Curve)**

**Recommended Research Pipeline:**

1. **Sourcing Clinical Benchmark Datasets**
2. **Medical Data Scrubbing & Handling Missingness**
3. **Exploratory Clinical Data Analysis**
4. **Biomarker Feature Engineering**
5. **Dimensionality Reduction & Predictor Selection**
6. **Stratified Train-Test Splitting (Preserving Class Balances)**
7. **Model Training (Logistic Regression, Decision Tree, Random Forest, XGBoost, CatBoost)**
8. **Diagnostic Performance Evaluation**
9. **Integration of Explainable AI (SHAP + LIME)**
10. **Development of Clinical UI/Dashboard for Physicians**
11. **Model Interpretability & Accuracy Comparison**