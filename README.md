# 💼 Data Science Salary Analysis – Python Project

## 📊 Overview  
This Python-based data science project explores salary trends in the data science industry. By analyzing real-world salary data, it identifies how compensation varies by **year**, **company size**, **remote work ratio**, and **experience level**. The project utilizes visualizations and grouped metrics to help interpret trends and support data-driven decision-making.

---

## 🎯 Project Objective  
To perform **exploratory data analysis (EDA)** on a dataset of data science salaries in order to:

- Understand average salary growth over time  
- Compare salary distributions by company size  
- Analyze the influence of experience level and remote ratio  
- Create visual insights using Python's data science stack

---

## 🔄 Process

### 1. Data Import & Setup  
- Imported core libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- Configured plot styling and display settings  

### 2. Data Cleaning  
- Loaded dataset from `data_science.csv`  
- Removed irrelevant columns: `Unnamed: 0`, `salary`, `salary_currency`  
- Ensured consistency and correctness in column types

### 3. Yearly Salary Aggregation  
- Grouped data by `work_year`  
- Calculated the average `salary_in_usd` for each year  
- Converted results to thousands (K USD) for readability

### 4. Company Size Analysis  
- Segmented the dataset into Small (S), Medium (M), and Large (L) companies  
- Calculated mean salaries per company size group  
- Compared group trends through a bar chart

### 5. Data Visualization  
- Created bar plots using `seaborn` and `matplotlib`  
- Visualized:
  - **Average salary by year**  
  - **Average salary by company size**

---

## 🗃️ Data Details

### Dataset Fields Used  
- `work_year` – The year of the job  
- `company_size` – Company size category (S, M, L)  
- `remote_ratio` – Degree of remote work (0%, 50%, 100%)  
- `experience_level` – Job seniority (EN, MI, SE, EX)  
- `salary_in_usd` – Normalized annual salary in USD

---

## 📈 Analysis Highlights

### 📊 Salary by Year  
- Salaries in data science have shown a consistent increase  
- Most recent years report significantly higher average compensation

### 🏢 Salary by Company Size  
- Large companies tend to offer higher average salaries  
- Small and medium companies still show competitive compensation

### 👔 Seniority & Remote Work  
- Executive and senior roles dominate the top salary ranges  
- Jobs with full remote work are increasingly common

---

## 💡 Key Insights

- 💰 Salaries have steadily increased over the past few years  
- 🏢 Company size is a strong indicator of salary differences  
- 🧠 Seniority level correlates with higher earnings  
- 🌍 Remote jobs are widely available and well-paid

---

## 📌 Recommendations

1. **Consider Company Size**  
   Professionals aiming for higher pay may target larger organizations.

2. **Leverage Remote Opportunities**  
   Remote roles offer flexibility and competitive salaries — ideal for global talent.

3. **Promote Senior Development**  
   Companies should invest in mid-level employees to nurture future senior talent.

4. **Monitor Yearly Trends**  
   Staying updated on yearly salary benchmarks helps with better negotiations.

---

## ✅ Conclusion  
This project demonstrates essential data science skills in:

- ✅ Data cleaning and wrangling with `pandas`  
- ✅ Grouping and aggregation for trend discovery  
- ✅ Insightful visualizations using `matplotlib` and `seaborn`  
- ✅ Communicating findings through structured storytelling

The analysis equips both individuals and organizations with valuable knowledge of salary dynamics in the growing data science domain.

---

## 🛠️ Tools Used  
- Python 3.x  
- Jupyter Notebook  
- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  

---

## 📎 Files Included  
- `data_science.ipynb` – Main notebook with code, analysis, and plots  
- `data_science.csv` – Dataset used *(optional in repo)*

---
