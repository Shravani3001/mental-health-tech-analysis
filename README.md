# Mental Health in Tech – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a mental health survey dataset collected from employees in the tech industry.

The goal is to understand how **personal factors, workplace environment, and organizational support systems** influence mental health awareness and treatment-seeking behavior.

---

## 🎯 Objectives

* Analyze factors influencing **mental health treatment**
* Understand the role of **workplace support systems**
* Identify patterns in **employee behavior and perceptions**
* Provide insights for improving **organizational mental health policies**

---

## ❗ Problem Statement

Many employees in the tech industry experience mental health issues but **do not seek treatment** due to:

* Lack of awareness
* Workplace stigma
* Limited organizational support

This project aims to uncover the reasons behind this gap using data-driven insights.

---

## 📂 Dataset Description

The dataset contains survey responses from employees across different companies and countries.

### 🔢 Dataset Size

* **Rows:** 1243
* **Columns:** 24

---

## 📊 Features Overview

### 👤 Demographic Variables

* Age
* Gender
* Country

### 🧬 Personal Background

* self_employed
* family_history

### 🧠 Mental Health Indicators

* treatment
* work_interfere

### 🏢 Workplace Support

* benefits
* care_options
* wellness_program
* seek_help
* anonymity

### 🤝 Workplace Culture

* coworkers
* supervisor
* mental_health_interview

### ⚖️ Perception Variables

* mental_vs_physical
* mental_health_consequence
* phys_health_consequence

---

## ⚙️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🧹 Data Cleaning & Preprocessing

The dataset required extensive cleaning before analysis:

### ✔ Steps Performed

1. **Removed unnecessary columns**

   * Dropped `Timestamp` and `comments` (irrelevant/unstructured)

2. **Handled Missing Values**

   * `self_employed` → filled with mode
   * `work_interfere` → filled with "Don't know"
   * Dropped `state` (many missing values)

3. **Cleaned Age**

   * Removed unrealistic values (kept range: 18–60)

4. **Standardized Gender**

   * Converted multiple formats into:

     * Male
     * Female
     * Other

5. **Removed duplicates**

6. **Reset index**

---

## 📉 Missing Values Analysis

* High missing values found in:

  * `comments`
  * `state`
  * `work_interfere`

* Visualized using:

  * Bar chart
  * Heatmap

---

## 📊 Exploratory Data Analysis (EDA)

The analysis was divided into:

### 🔹 Univariate Analysis

* Distribution of Age, Gender, Treatment
* Workplace support availability

---

### 🔹 Bivariate Analysis

Key relationships explored:

* **Care Options vs Treatment**
* **Family History vs Treatment**
* **Gender vs Treatment**
* **Work Interference vs Treatment**
* **Benefits vs Seek Help**

---

### 🔹 Multivariate Analysis

Advanced insights using multiple variables:

* **Gender + Treatment + Work Interference**
* **Company Size + Benefits + Treatment**
* **Seek Help + Care Options + Benefits**
* **Mental vs Physical + Treatment + Work Interference**

---

## 🔍 Key Insights

### 📌 1. Workplace Support Drives Treatment

Employees with access to:

* Benefits
* Care options
  are **more likely to seek treatment**

---

### 📌 2. Reactive Behavior Pattern

Most employees seek help **only when mental health starts affecting work**

---

### 📌 3. Awareness Gap

Even when benefits exist, employees often:

* Are unaware of them
* Do not utilize them

---

### 📌 4. Company Size Matters

* Larger companies → better support → higher treatment rates
* Smaller companies → limited awareness and resources

---

### 📌 5. Family History Influence

Employees with family history are:

* More aware
* More likely to seek treatment

---

## 💼 Business Impact

### ✅ Positive Impact

* Helps organizations design **better mental health policies**
* Encourages **proactive support systems**
* Improves **employee productivity and well-being**

---

### ⚠️ Negative Insights

* Lack of awareness reduces effectiveness of benefits
* Employees delay treatment → leads to productivity loss
* Smaller companies lag in mental health support

---

## 📈 Conclusion

This analysis highlights that:

* Mental health behavior is influenced by both **individual and organizational factors**
* Employees tend to seek help **only when problems escalate**
* Organizations must shift from **reactive → proactive mental health strategies**

---

## 🚀 Future Improvements

* Apply **Machine Learning models** for prediction
* Perform **sentiment analysis** on comments (if cleaned)
* Build a **dashboard (Power BI / Tableau)** for visualization
* Integrate **AIOps insights** for real-time monitoring

---

## 📁 Project Structure

```bash
mental-health-tech-analysis/
├── survey.csv
│
├── mental-health-eda.ipynb
│
├── README.md
```

---

## Acknowledgements

* Dataset: Mental Health in Tech Survey
* Inspired by real-world workplace mental health challenges

---

## Author

**Shravani K**

