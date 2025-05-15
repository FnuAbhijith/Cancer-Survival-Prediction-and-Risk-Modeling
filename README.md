
# 🧬 Cancer Survival Prediction and Risk Modeling

This project predicts **cancer severity** and **patient survival probability** using machine learning classification and survival analysis. It leverages patient data from global cancer records between 2015–2024.


## 🎯 Objective

Build an end-to-end pipeline to:

- Classify patients as high or low severity based on clinical features.
- Predict survival duration using Cox Proportional Hazards Model.
- Support early risk detection for oncological decision-making.



## 📊 Models & Techniques Used

| Model                   | Purpose                            | Evaluation Metric              |
|-------------------------|-------------------------------------|--------------------------------|
| Logistic Regression     | Binary classification (severity)    | Accuracy, ROC-AUC              |
| Random Forest Classifier| Feature selection & classification  | Accuracy, Confusion Matrix     |
| Cox Proportional Hazards| Survival time prediction            | Concordance Index (C-index)    |


## 🧪 Dataset Summary

- **Source:** Kaggle  
- **Link:** [Global Cancer Patients (2015–2024)] (https://www.kaggle.com/datasets/zahidmughal2343/global-cancer-patients-2015-2024)
- **Records:** ~25,000 entries
- **Features:** Age, Gender, Country, Cancer Type, Stage, Survival Time, Status
- **Targets:**
  - `Severity` (for classification)
  - `Survival_Time`, `Event_Observed` (for Cox regression)
 

## 📌 Results Summary

| Model                   | Accuracy | ROC-AUC | C-Index |
|-------------------------|----------|---------|---------|
| Logistic Regression     | 0.91     | 0.93    | —       |
| Random Forest Classifier| 0.94     | 0.96    | —       |
| Cox Proportional Hazards| —        | —       | 0.87    |


## 🧠 Skills Demonstrated

- Binary Classification  
- Survival Analysis (Cox Regression)  
- Handling Imbalanced Medical Data  
- Model Evaluation: ROC-AUC, Confusion Matrix, Concordance Index  
- End-to-End Pipeline Deployment in Jupyter  


## 🚀 How to Run This Project

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/Cancer-Survival-Prediction-and-Risk-Modeling.git
cd Cancer-Survival-Prediction-and-Risk-Modeling

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Launch the notebook
jupyter notebook


