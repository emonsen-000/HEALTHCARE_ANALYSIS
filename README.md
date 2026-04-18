# 🏥 Healthcare Data Analysis Project

## 📌 Overview

This project focuses on analyzing a healthcare dataset to uncover patterns related to patient demographics, medical conditions, hospital performance, billing trends, and treatment outcomes.

The goal of this analysis is to move beyond simple data exploration and extract meaningful insights that can help understand patient distribution, healthcare trends, and operational aspects of hospitals.

---

## 🎯 Objectives

* Understand patient distribution across different demographics (age, gender, blood type)
* Analyze trends in medical conditions and admission types
* Explore hospital and insurance provider patterns
* Investigate billing behavior and anomalies
* Identify relationships between features such as length of stay and billing

---

## 🗂️ Dataset Features

The dataset includes the following key columns:

* Patient Information: Name, Age, Gender, Blood Type
* Medical Data: Medical Condition, Medication, Test Results
* Admission Details: Admission Type, Date of Admission, Discharge Date
* Hospital Information: Hospital, Doctor, Insurance Provider
* Financial Data: Billing Amount

---

## ⚙️ Data Preprocessing

The following steps were performed:

* Converted date columns to proper datetime format
* Cleaned inconsistent text data (names, hospital entries)
* Removed duplicates
* Created new features:

  * Admission Year & Month
  * Discharge Year & Month
  * Length of Stay
  * Age Groups

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Demographic Analysis

* Majority of patients are **Senior Citizens (~51.7%)**
* Gender distribution is almost balanced
* Blood type distribution is nearly uniform across all categories

---

### 🔹 Medical Condition Analysis

* Arthritis and Diabetes have the highest patient counts
* All conditions have relatively high representation (9000+ patients each)
* Obesity shows notable spikes in certain years

---

### 🔹 Admission Insights

* Most patients are admitted under **Elective type**
* Urgent and Emergency admissions follow
* Average Length of Stay is consistent (~15–16 days across categories)

---

### 🔹 Yearly Trends

* Significant rise in patient numbers in **2020 (~57%)**
* Gradual stabilization afterward
* Sharp decline observed in **2024 (~60–70%)**

---

### 🔹 Insurance Analysis

* Patient distribution across insurance providers is relatively balanced
* **Cigna** has the highest number of patients, though not overwhelmingly dominant

---

### 🔹 Hospital & Billing Analysis

* Average billing amount remains consistent (~$25,000) across years
* Some hospitals show **negative net billing**, possibly due to refunds or adjustments
* **Johnson Inc** recorded the highest yearly earning (~$360,000 in 2023)

---

### 🔹 Medical Outcome Insights

* Test Results interpreted as diagnostic outcomes during/after treatment
* Higher proportion of **abnormal results** observed in:

  * Arthritis
  * Cancer
  * Diabetes
  * Obesity

---

### 🔹 Medication Patterns

* Common medication usage per condition:

  * Arthritis → Aspirin
  * Hypertension → Ibuprofen
  * Cancer → Lipitor
  * Asthma → Paracetamol
  * Obesity → Penicillin

---

## 🔍 Key Observations

* Healthcare costs do not show strong linear correlation with length of stay
* Patient distribution is fairly balanced across multiple categories
* Certain trends (like 2020 spike) suggest external or systemic influences
* Presence of negative billing highlights real-world financial complexities
* Dataset shows structured patterns rather than purely random variation

---

## 📈 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 Future Improvements

* Add deeper statistical analysis (correlation by segments, hypothesis testing)
* Improve visualization storytelling and design
* Build predictive models (e.g., cost prediction, patient risk analysis)
* Include interactive dashboards (Power BI / Tableau)

---

## 📌 Conclusion

This project demonstrates the process of transforming raw healthcare data into meaningful insights. While many patterns appear balanced, deeper analysis reveals structural behaviors, hidden trends, and important anomalies that reflect real-world healthcare dynamics.

---

## 🙌 Author

**Emon Sen**
B.Sc. Engineering (CSE) Student
Aspiring Data Analyst

---
