# 🧠 Alzheimer's Disease Exploratory Data Analysis (EDA)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Age Distribution](#age-distribution)
  - [Gender Distribution](#gender-distribution)
  - [Ethnicity Distribution](#ethnicity-distribution)
  - [Age by Education Level](#age-by-education-level)
  - [BMI Distribution by Diabetes Status](#bmi-distribution-by-diabetes-status)
  - [Systolic vs Diastolic Blood Pressure Correlation](#systolic-vs-diastolic-blood-pressure-correlation)
  - [Alzheimer’s Disease Diagnosis](#alzheimers-disease-diagnosis)
  - [Impact of Family History on Alzheimer’s Diagnosis](#impact-of-family-history-on-alzheimers-diagnosis)
  - [Sleep Quality vs Physical Activity](#sleep-quality-vs-physical-activity)
  - [Depression History and Alzheimer’s Diagnosis](#depression-history-and-alzheimers-diagnosis)
  - [Memory Complaints by Education Level](#memory-complaints-by-education-level)
  - [Cholesterol Levels by Smoking Status](#cholesterol-levels-by-smoking-status)
- [Conclusion and Business Insights](#conclusion-and-business-insights)

## Project Overview
This project aims to perform an Exploratory Data Analysis (EDA) on a dataset related to Alzheimer's Disease, with a focus on identifying key trends, correlations, and risk factors. By examining demographics, clinical conditions, and lifestyle habits, we seek to uncover insights that could inform early intervention and prevention strategies for Alzheimer's Disease.

## Dataset Overview
The dataset includes various attributes such as:
- **Age**: Age of the patients.
- **Gender**: Male or Female.
- **Ethnicity**: Ethnic background of patients.
- **Education Level**: Highest level of education attained.
- **BMI**: Body Mass Index.
- **Blood Pressure**: Systolic and diastolic blood pressure readings.
- **Lifestyle Factors**: Smoking, alcohol consumption, physical activity, and sleep quality.
- **Family History**: Family history of Alzheimer’s.
- **Clinical Conditions**: Presence of conditions like diabetes, cardiovascular disease, and depression.
- **Cognitive Health Markers**: Memory complaints and Alzheimer's diagnosis status.

## Data Cleaning and Preparation
1. **Handling Missing Data**: Missing values were handled by either imputing or removing records, based on the proportion of missingness.
2. **Outlier Detection**: Identified outliers for clinical variables (e.g., blood pressure) and dealt with them using appropriate statistical techniques.
3. **Data Type Adjustments**: Ensured that each column had the appropriate data type, converting where necessary.
4. **Feature Engineering**: Created new features like age categories and interaction variables to support deeper analysis.

## Exploratory Data Analysis (EDA)
The analysis aims to answer specific questions and extract meaningful insights from the dataset. Below are the key visualizations and findings:

### Age Distribution
- **Questions Answered**: What is the distribution of age among the patients?
- **Insights**: The majority of patients are aged between 70 and 84, peaking around age 90, indicating a high-risk age group for Alzheimer’s.
- **Conclusion**: Early interventions and screenings should focus on this high-risk age group.

### Gender Distribution
- **Questions Answered**: How are patients distributed by gender?
- **Insights**: The dataset shows almost equal representation between males (49.4%) and females (50.6%).
- **Conclusion**: Gender-specific Alzheimer’s interventions may not be necessary based on this dataset.

### Ethnicity Distribution
- **Questions Answered**: How does ethnicity factor into Alzheimer’s risk?
- **Insights**: A majority (59%) of patients are Caucasian, followed by smaller percentages of African American and Asian patients.
- **Conclusion**: Outreach should ensure inclusivity across different ethnic groups to address any disparities in care.

### Age by Education Level
- **Questions Answered**: How does education level vary across age groups?
- **Insights**: Patients with higher education levels tend to be older, suggesting a possible link between education and longevity.
- **Conclusion**: Higher education may offer cognitive resilience, potentially delaying the onset of Alzheimer's symptoms.

### BMI Distribution by Diabetes Status
- **Questions Answered**: What is the BMI distribution among diabetic and non-diabetic patients?
- **Insights**: Diabetic patients generally have higher BMIs, clustering between 25 and 40.
- **Conclusion**: Addressing obesity through lifestyle changes is important, especially for diabetic patients who are at higher risk for Alzheimer’s.

### Systolic vs Diastolic Blood Pressure Correlation
- **Questions Answered**: How do systolic and diastolic blood pressures correlate?
- **Insights**: A weak correlation suggests that these blood pressure measurements do not vary linearly.
- **Conclusion**: While blood pressure management is important, additional cardiovascular markers may be needed for Alzheimer’s risk prediction.

### Alzheimer’s Disease Diagnosis
- **Questions Answered**: What proportion of the patients are diagnosed with Alzheimer’s?
- **Insights**: Around 35.4% of the dataset has an Alzheimer’s diagnosis.
- **Conclusion**: There is a need for increased awareness and diagnostic efforts to identify those at risk earlier.

### Impact of Family History on Alzheimer’s Diagnosis
- **Questions Answered**: How does family history influence Alzheimer’s diagnosis?
- **Insights**: 33.9% of patients with a family history of Alzheimer’s are diagnosed, compared to 17.8% without.
- **Conclusion**: Family history is a significant risk factor, emphasizing the need for genetic counseling and early screenings.

### Sleep Quality vs Physical Activity
- **Questions Answered**: How does physical activity impact sleep quality?
- **Insights**: Higher physical activity levels are associated with better sleep quality.
- **Conclusion**: Promoting physical activity could improve sleep quality and overall cognitive health.

### Depression History and Alzheimer’s Diagnosis
- **Questions Answered**: How does a history of depression relate to Alzheimer’s diagnosis?
- **Insights**: 70% of patients with a history of depression are diagnosed with Alzheimer’s.
- **Conclusion**: Mental health management is crucial in reducing Alzheimer’s risk, especially for those with depression.

### Memory Complaints by Education Level
- **Questions Answered**: How do memory complaints vary by education level?
- **Insights**: Individuals with lower education levels report more memory complaints.
- **Conclusion**: Cognitive interventions should target individuals with lower education levels.

### Cholesterol Levels by Smoking Status
- **Questions Answered**: What is the relationship between smoking and cholesterol levels?
- **Insights**: Smokers tend to have higher and more variable cholesterol levels.
- **Conclusion**: Smoking cessation should be a key focus to reduce cardiovascular and cognitive risks.

---

## 🔍 **Analysis Summary**

This EDA provides valuable insights into the demographics, lifestyle factors, and clinical conditions of individuals at risk of Alzheimer’s Disease. The findings suggest:
- **Age** and **family history** are critical factors influencing Alzheimer's risk.
- **Education level** and **lifestyle habits** (such as physical activity and BMI) play significant roles in cognitive health.
- The dataset reveals potential gaps in **screening** and **early diagnosis**, emphasizing the importance of **preventive healthcare**.

---

## 🚀 **Conclusion**

The analysis of this dataset highlights several important aspects of Alzheimer’s Disease and its risk factors. Early screening, better awareness, and targeted interventions, particularly in older adults with high-risk factors (such as family history, high BMI, and diabetes), can aid in the prevention and management of Alzheimer’s. This repository offers a foundation for future research, helping guide healthcare providers and policymakers in their approach to Alzheimer’s care.

---

## 🛠 **Technologies Used**
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Data visualization techniques
