# 📊 Healthcare Data Analysis & Patient Insights (EDA)

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a Healthcare Dataset sourced from Kaggle using Python. The objective is to analyze patient demographics, medical conditions, billing trends, and admission patterns to uncover meaningful insights for healthcare operations.

---

## 🛠️ Tech Stack & Libraries
- Language: Python
- Environment: Google Colab
- Data Processing: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Dataset Acquisition: Kagglehub (prasad22/healthcare-dataset)

---

## 🔄 Project Workflow
1. Data Ingestion: Sourced dataset dynamically using kagglehub.
2. Data Understanding & Cleaning: Checked shape, datatypes, missing values, and removed duplicate records.
3. Data Preprocessing: Converted Date of Admission and Discharge Date into datetime format.
4. Feature Engineering: Built a custom Age_Status column (Adult, Senior, Senior Citizen) and extracted Month from admission dates.
5. Exploratory Data Analysis: Created statistical plots (Count Plots, Line Charts, Bar Plots, Pie Charts) to analyze key patterns.

---

## 📊 Key Analysis & Visualizations
- Medical Conditions by Age Status: Seaborn count plots to visualize disease distribution across age brackets.
- Monthly Patient Trends: Line chart analyzing admission spikes per month.
- Admission Type vs. Billing Amount: Bar plots evaluating costs based on medical conditions and emergency/regular admissions.
- Demographic Breakdown: Pie charts representing Gender and Age Status proportions.

---

## 💡 Key Summary Insights
1. Senior Citizens suffer from the highest number of medical conditions and diseases compared to other age brackets.
2. May recorded the highest number of patient admissions throughout the year.

---

## 💻 How to Run
1. Open EDAProject.ipynb in Google Colab or Jupyter Notebook.
2. Install required dependencies:
   ```bash
   pip install kagglehub pandas numpy matplotlib seaborn
