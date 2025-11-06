# 🩺 IoMT Healthcare Risk Prediction (Excel + Python)

Analyzed **IoMT healthcare data** to identify key factors influencing patient health risk levels using **Excel** and **Python**.  
Performed data cleaning, EDA, and predictive modeling to classify patients as **Healthy**, **At Risk**, or **Critical** based on vital signs and medical history.  
Developed an **interactive Excel dashboard** to visualize patient health distribution, vital trends, and KPI summaries.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoftexcel)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Modeling-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

![](intro_img.png)

---

## 📘 Overview  
The **IoMT Healthcare Monitoring and Security Dataset** represents real-world **Internet of Medical Things (IoMT)** environments where patient data is collected through interconnected medical sensors.  
This project focuses on **predicting patient health status** and analyzing the physiological and behavioral factors contributing to health risk levels.  

It combines **Excel-based data analysis and dashboarding** with **Python-based machine learning modeling**, offering both analytical and visual insights into patient health dynamics.

---

## 📊 Dataset  

- **Source:** IoMT Healthcare Monitoring and Security Dataset  
- **Records:** 2,500 patient entries  
- **Objective:** Classify patients as **Healthy**, **At Risk**, or **Critical** based on vital signs, medical history, and treatment patterns.  

| Feature | Description |
|----------|--------------|
| **Patient_ID** | Unique identifier assigned to each patient record |
| **Patient_Age** | Age of the patient (18–90 years) |
| **Vital_Signs_Abnormality** | Overall condition of vital signs — Normal / Slightly Abnormal / Highly Abnormal |
| **Previous_Diagnosis** | Previously diagnosed condition: Diabetes, Hypertension, Cardiac Issue, etc. |
| **Medication_Usage** | Medication intake level — None / Occasional / Regular / High Dependency |
| **Treatment_History** | Past medical treatment — No Treatment / Routine Checkup / Medication / Surgery / Therapy |
| **Heart_Rate_BPM** | Heart rate in beats per minute (50–110 BPM) |
| **Blood_Pressure_mmHg** | Blood pressure reading in Systolic/Diastolic format (e.g., 120/80 mmHg) |
| **Oxygen_Saturation_%** | Oxygen saturation level in blood (90–100%) |
| **Body_Temperature_C** | Body temperature in Celsius (36.0–39.0°C) |
| **Blood_Glucose_mg/dL** | Blood glucose level (70–200 mg/dL) |
| **Health_Status (Target)** | Health classification: Healthy / At Risk / Critical |

---

## 🧰 Tools & Technologies  

| Category | Tools Used |
|-----------|-------------|
| **Programming Language** | Python |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn |
| **Visualization & Dashboard** | Microsoft Excel |
| **Presentation** | Microsoft PowerPoint |
| **IDE** | Jupyter Notebook / Google Colab |

---

## 🔍 Project Workflow  

### 1️⃣ Data Importing  
- Imported dataset using `pandas`.  
- Reviewed structure, data types, and missing values.  

### 2️⃣ Data Preprocessing  
- Cleaned and formatted both numeric and categorical variables.  
- Handled missing or invalid values.  
- Standardized vital signs and combined systolic/diastolic BP readings.  
- Encoded categorical columns and normalized numeric features.  

### 3️⃣ Exploratory Data Analysis (EDA)  
- Performed descriptive analysis and statistical summaries in **Excel**.  
- Created pivot tables to compare vitals across health categories.  
- Used charts (bar, box, line) to analyze vital sign distribution.  
- Identified key indicators influencing health risk.  

### 4️⃣ Feature Engineering & Selection  
- Selected relevant variables using correlation analysis.  
- Created derived metrics (e.g., BP ratio, abnormality index).  
- Removed redundant or non-informative fields.  

### 5️⃣ Model Development  
- Split data into training and test sets.  
- Implemented models: **Logistic Regression**, **Random Forest**, and **XGBoost**.  
- Evaluated with metrics such as **Accuracy**, **F1-score**, and **ROC-AUC**.  

### 6️⃣ Hyperparameter Tuning  
- Optimized model performance using **RandomizedSearchCV**.  
- Finalized the model with the best generalization score.  

### 7️⃣ Excel Dashboard  
- Imported cleaned dataset into Excel.  
- Designed an **interactive dashboard** featuring:  
  - Patient distribution by health status  
  - KPI cards for key vitals (BP, Glucose, SpO₂, Temp, BPM)  
  - Health risk trends by age and medication usage  
  - Conditional formatting for visual risk alerts  
- Integrated slicers for dynamic filtering (by status, diagnosis, medication, etc.).  

---

## 📈 Results & Insights  

- Achieved **high prediction accuracy** for health risk classification.  
- **Top predictive factors:** Blood Pressure, Oxygen Saturation, and Blood Glucose.  
- **Age and medication** strongly influence overall patient risk.  
- The Excel dashboard provides **instant visual insights** for identifying high-risk patients and abnormal vitals.

---

## 📊 Excel Dashboard Preview   
![Dashboard Screenshot](dashboard1.jpg)
![Dashboard Screenshot](dashboard2.jpg)
![Dashboard Screenshot](dashboard3.jpg)

---

## 🚀 Key Insights  

- **Blood Pressure:** Patients with elevated BP show higher risk categories.  
- **Oxygen Saturation:** Levels <94% indicate potential critical conditions.  
- **Temperature:** Fever (>38°C) or low body temp (<36°C) correspond with poor health status.  
- **Blood Glucose:** Readings above 180 mg/dL are common in “Critical” category.  
- **Medication Usage:** Regular or high medication dependency correlates with higher risk.  
- **Age:** Patients above 60 show greater chances of being “At Risk” or “Critical”.  

**Final Insight:**  
The combined **Excel + Python workflow** effectively identifies patient health risks and supports **data-driven preventive healthcare** through IoMT analytics.

---

## 🧩 Project Highlights  

- End-to-end data analytics workflow (Excel + Python)  
- Machine learning classification for health risk prediction  
- Interactive Excel dashboard for patient monitoring  
- Actionable insights for healthcare analytics and IoMT research  

---

## 📄 Files Included  

| File | Description |
|------|--------------|
| `IoMT_Healthcare_Risk_Prediction.ipynb` | Jupyter Notebook containing data preprocessing, EDA, and modeling |
| `IoMT_Healthcare_Data.xlsx` | Cleaned and processed dataset |
| `IoMT_Healthcare_Dashboard.xlsx` | Excel dashboard with slicers and KPIs |
| `Capstone_Presentation.pptx` | Final project presentation |

---

## 🏁 Conclusion  

The project demonstrates how **data-driven IoMT analytics** can improve early risk detection and patient monitoring.  
By integrating **Python’s analytical power** with **Excel’s visualization capabilities**, it bridges technical modeling with actionable business insights in healthcare informatics.

---
