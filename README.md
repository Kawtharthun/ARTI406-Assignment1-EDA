# Dataset Description

## Dataset Name
Jobs and Salaries in Data Science

## Dataset Source
- **Platform:** Kaggle
- **URL:** https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data
- **File:** jobs_in_data.csv

---

## Number of Rows and Columns
- **Original dataset:** 9,355 rows × 12 columns
- **After cleaning (duplicates removed, redundant columns dropped):** 5,341 rows × 10 columns

---

## Description of Features (Columns)

| Column | Description |
|---|---|
| `work_year` | The year the salary was reported (2020–2023) |
| `job_title` | The specific job title of the employee (e.g., Data Engineer, ML Engineer) |
| `job_category` | A broader grouping of the job role (e.g., Data Science, Data Engineering, ML & AI) |
| `salary_currency` | The currency in which the salary was originally reported |
| `salary` | The salary in the employee's local currency |
| `salary_in_usd` | The salary converted to US Dollars (USD) for standardized comparison |
| `employee_residence` | The country where the employee lives |
| `experience_level` | Career stage: Entry-level, Mid-level, Senior, or Executive |
| `employment_type` | Type of employment: Full-time, Part-time, Contract, or Freelance |
| `work_setting` | Whether the role is Remote, Hybrid, or In-person |
| `company_location` | The country where the company is based |
| `company_size` | Size of the company: S (Small), M (Medium), or L (Large) |

---

## Purpose of Using This Dataset

This dataset was selected for the following reasons:

1. **Relevance to the field:** As AI and data science students, understanding salary trends across roles, experience levels, and work settings is directly applicable to our future careers.

2. **Rich for EDA:** The dataset includes a mix of numerical columns (salary, work year) and categorical columns (experience level, job category, work setting, company size), which allows for diverse and meaningful visualizations.

3. **Real-world data quality:** The dataset contains duplicate entries and redundant columns, making it a realistic dataset for practicing data cleaning techniques.

4. **Trend analysis:** With data spanning from 2020 to 2023, the dataset allows for time-based analysis of salary growth and the shift toward remote work — both important industry trends.

5. **Foundation for modeling:** After EDA and cleaning, this dataset can serve as a strong foundation for future machine learning assignments involving salary prediction.
