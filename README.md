# Data Professionals Survey — Power BI Dashboard

A multi-page interactive Power BI report analyzing a survey of data professionals worldwide — covering compensation, job satisfaction, career paths, and demographics. Built on the Alex Freberg dataset (2022).

---

## Project Structure

```
data-professionals-survey-powerbi/
│
├── Data_Professionals_Survey.pbix   # Full Power BI report (4 pages)
├── screenshots/
│   ├── 01_overview.png
│   ├── 02_compensation.png
│   ├── 03_satisfaction.png
│   └── 04_demographics.png
└── README.md
```

> To view the full interactive report, open the `.pbix` file in **Power BI Desktop** (free download from Microsoft).

---

## Project Overview

This report answers key questions for anyone considering or already working in the data field:
- What does a typical data professional look like?
- How much do different roles earn, and what drives salary differences?
- How happy are data professionals with their jobs?
- What is the easiest (or hardest) path into data?

---

## Report Pages

### Page 1 — Overview
**Who are data professionals?**

| Visual | Type | Insight |
|---|---|---|
| Job Title Breakdown | Bar chart | Distribution across Analyst, Engineer, Scientist, etc. |
| Favorite Programming Language | Donut chart | Python vs R vs other languages |
| Respondents by Country | Treemap | Geographic distribution of survey participants |
| KPI Cards | Card visuals | Total respondents, avg age, avg salary, avg experience |

---

### Page 2 — Compensation
**How much do data professionals earn?**

| Visual | Type | Insight |
|---|---|---|
| Average Salary by Job Title | Bar chart | Which roles pay the most |
| Salary Distribution | Column chart | How Much Do Data Professionals Earn? |
| Average Salary by Country | Bar chart | Geographic salary differences |
| Education Level vs Salary | Bar chart | Does Education Level Pay Off? |
| Age vs Salary | Scatter chart | Does Experience Drive Higher Salary? |
| Slicers | Filters | Filter by country and job title |

---

### Page 3 — Satisfaction & Work Sentiment
**How do data professionals feel about their jobs?**

| Visual | Type | Insight |
|---|---|---|
| Happiness by Job Title | Bar chart | Which Role Feels Best? |
| Breaking Into Data | Donut chart | How Hard Was It to Break Into Data? |
| Job Search Priorities | Bar chart | If Looking Today — What Matters Most? |
| Difficulty by Job Title | Bar chart | Which roles were hardest to land? |
| Avg Work-Life Balance Score | Card | Satisfaction rating |
| Avg Salary Satisfaction Score | Card | Pay satisfaction rating |
| Slicer | Filter | Filter by job title |

---

### Page 4 — Demographics & Career Paths
**Who are the people behind the data?**

| Visual | Type | Insight |
|---|---|---|
| Age Distribution | Column chart | Age spread across the data field |
| Salary Growth with Age | Bar chart | Does Salary Grow With Age? |
| Career Switchers | Donut chart | Career Switchers vs. Direct Path |
| KPI Cards | Card visuals | Avg age, gender split, experience, education |

---

## Tools & Techniques

**Tool:** Microsoft Power BI Desktop

**Techniques applied:**
- Data cleaning and transformation in **Power Query** (M language)
- **DAX** calculated columns and measures for KPIs
- Custom visual types: Radar Chart, Advance Card, Map, Date Picker
- Theme: Frontier (built-in Power BI theme)
- Cross-page filtering with slicers
- Conditional formatting on salary visuals

**Custom Visuals Used:**
- Advance Card — enhanced KPI display
- Radar Chart — multi-axis satisfaction comparison
- Map — geographic distribution
- Date Picker — time-based filtering

---

## Dataset

- **Source:** [Alex Freberg (Alex The Analyst)](https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx) — Data Professionals Survey
- **Collected:** 2022
- **Respondents:** ~630 data professionals
- **Fields include:** Job title, country, salary, age, education, programming language preference, career satisfaction, difficulty breaking into data, career switcher status

---

## Key Insights

- **Python dominates** as the most popular programming language across all data roles
- **Data Scientists** earn the highest average salaries, followed by Data Engineers
- **The United States** has the highest concentration of respondents and highest salaries
- **Breaking into data is rated moderately difficult** — most respondents found it neither easy nor very hard
- **Better Salary** is the most important factor when job searching
- A significant portion of respondents are **career switchers**, suggesting the data field is accessible across backgrounds
- **Salary satisfaction is lower than work-life balance satisfaction** — data professionals are more content with their hours than their pay

---

## Author

**Khaoula** — Data Science & Intelligent Systems 
📌 Specialization: NLP, Machine Learning, Data Analysis  
🔗 [Tableau Public](https://public.tableau.com/app/profile/khaoula.ghimouze/vizzes) | [Hugging Face](https://huggingface.co/khaoula-ghz)
