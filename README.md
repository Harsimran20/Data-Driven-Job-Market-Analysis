# 📊 Job Market Data Analyzer

> A Python-based data analysis project that extracts **real-world insights** from job market data to help job seekers understand **in-demand skills, salary trends, and hiring locations**.

---

## 🚀 Project Overview

Job seekers often rely on assumptions rather than data when deciding:

* Which skills to learn
* Which roles pay the most
* Which locations offer the best opportunities

This project analyzes **real job listings data** to provide **data-driven answers** using Python, Pandas, and NumPy.

---

## 🎯 Key Objectives

* Identify **most in-demand skills**
* Analyze **salary trends by job role**
* Discover **top hiring locations**
* Understand **experience-level distribution**
* Build a **reusable data analysis pipeline**

---

## 🧠 Who Is This For?

* Students and entry-level professionals
* Career switchers
* Data analyst / data science aspirants
* Anyone exploring the job market with data

---

## 🗂 Dataset

* **Source:** Kaggle – Job Market Insights Dataset
* **Data Includes:**

  * Job titles
  * Locations
  * Salary information
  * Skills
  * Experience levels

> The dataset represents real-world, messy data — cleaned and processed within this project.

---

## 🛠 Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Regex
* **Tools:**

  * Jupyter Notebook / Python Script
  * Git & GitHub

---

## 🏗 Project Structure

```
job-market-data-analyzer/
│
├── data/
│   ├── raw/
│   │   └── job_descriptions.csv
│   └── processed/
│       └── cleaned_jobs.csv
│
├── main.py
├── requirements.txt
└── README.md
```

---

## 🔍 Features & Analysis

### ✔ Data Cleaning

* Removed duplicates
* Handled missing values
* Standardized column names

### ✔ Skill Demand Analysis

* Extracted skills from job listings
* Ranked skills by demand

### ✔ Salary Analysis

* Normalized salary text using regex
* Computed average salaries by job role

### ✔ Location Analysis

* Identified top hiring locations

### ✔ Experience Level Insights

* Distribution of job postings by experience level

---

## 📈 Sample Insights

* **Python and SQL** are among the most demanded skills
* **Senior-level roles** command higher average salaries
* **Major metropolitan cities** dominate job postings
* Certain skills show a **salary premium**

*(Exact results depend on dataset version)*

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Analysis

```bash
python main.py
```

---

## 🧪 Example Output

```
TOP IN-DEMAND SKILLS
python      1200
sql         980
excel       850

TOP PAYING JOB ROLES
Data Engineer    120000
ML Engineer      115000
```

---

## 📌 Why This Project Matters

This project demonstrates:

* Real-world data cleaning skills
* Strong Pandas and NumPy usage
* Business-focused analytical thinking
* Clean, modular Python coding
* End-to-end project ownership

---

## 🚧 Future Enhancements

* 📊 Interactive dashboards using Streamlit
* 📉 Skill-based salary premium analysis
* 📄 Resume-to-job skill gap analysis
* ⏱ Automated weekly job market reports

---
