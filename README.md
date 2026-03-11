# 🔍 LinkedIn Jobs Market — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a dataset of **122,130 LinkedIn job postings** from the United States. The goal is to uncover trends in the job market — including in-demand roles, top hiring companies, salary patterns, skills demand, and job engagement metrics.

---

## 🎯 Objectives

- Identify the most in-demand job titles and roles
- Discover which companies and locations are hiring the most
- Analyze salary distributions across experience levels
- Understand remote vs onsite work trends
- Find the most frequently required skills
- Measure job engagement through views and application rates

---

## 📁 Dataset

- **Source:** [LinkedIn Job Postings — Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)
- **Size:** 122,130 job postings
- **Columns:** 31 original features (cleaned to 21)
- **Region:** United States

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Development environment |

---

## 📊 Analysis Sections

1. Importing Libraries
2. Loading Dataset
3. Dataset Overview
4. Data Cleaning
5. Top Job Titles Analysis
6. Top Hiring Companies
7. Top Hiring Locations
8. Experience Level Distribution
9. Work Type Distribution
10. Remote Work Analysis
11. Salary Analysis
12. Salary by Experience Level
13. Most In-Demand Skills Analysis
14. Job Views & Applications Analysis
15. Key Insights & Conclusions

---

## 💡 Key Insights

### 💼 Job Market
- **Sales Manager**, **Customer Service Representative** and **Project Manager** are the top 3 most in-demand roles
- **Mid-Senior level** roles dominate the market — entry level is competitive but growing
- **79.9%** of all job postings are Full-time positions

### 📍 Location & Remote Work
- Only **12.1%** of jobs allow remote work — physical presence is still the norm in the US job market

### 💰 Salary
- Average normalized salary is approximately **$40,000 annually**
- **Executive level** roles command the highest salaries
- Only **5% of postings** include salary data — a significant dataset limitation

### 🛠️ Skills
- **Management**, **Communication** and **Sales** are the top 3 most mentioned skills
- **Excel** is the most in-demand technical tool
- The dataset is dominated by non-tech roles — soft skills outweigh technical skills

### 📈 Job Engagement
- Average **apply rate is 15.56%** — roughly 1 in 6 viewers apply to a job
- Most jobs receive between **5–20 views**, indicating niche and targeted postings

---

## ⚠️ Limitations

- Only ~5% of job postings include salary information
- The `skills_desc` column is not standardized — skill extraction is approximate
- Dataset does not explicitly categorize Hybrid work type
- Data is US-centric and may not reflect global trends

---

## 📂 Project Structure

```
linkedin-jobs-eda/
│
├── linkedin_jobs_eda.ipynb   # Main notebook
├── job_postings.csv          # Dataset (download from Kaggle)
├── README.md                 # Project documentation
│
└── charts/
    ├── top_job_titles.png
    ├── top_companies.png
    ├── top_locations.png
    ├── experience_level.png
    ├── work_type.png
    ├── remote_vs_onsite.png
    ├── salary_distribution.png
    ├── salary_by_experience.png
    ├── top_skills.png
    └── job_engagement.png
```

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/yourusername/linkedin-jobs-eda.git
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings) and place `job_postings.csv` in the project folder

4. Open the notebook
```bash
jupyter notebook linkedin_jobs_eda.ipynb
```

---

## 👤 Author

**Aryansingh Bais**  
Aspiring Data Scientist | Python | Pandas | EDA | Power BI

🔗 [LinkedIn](https://www.linkedin.com/in/aryansinghbais8) | 🐙 [GitHub](https://github.com/Aryansingh-B/LinkedIn-Jobs-EDA)

---

## ⭐ If you found this project useful, please give it a star!
```
