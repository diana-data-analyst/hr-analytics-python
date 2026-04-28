# 🧑‍💼 HR Analytics: Employee Attrition Analysis

Python project analyzing HR data to identify key factors driving employee attrition.

## 📌 Project Goal

Answer real business questions using Python:
- Which departments have the highest attrition rate?
- Does salary affect employee retention?
- What is the main driver of attrition?

## 🗄️ Dataset

Synthetic dataset of 250 employees with the following features:

| Column | Description |
|--------|-------------|
| `employee_id` | Unique employee identifier |
| `department` | Department (6 departments) |
| `position` | Job position (18 positions) |
| `age` | Employee age (22–55) |
| `years_at_company` | Years of experience at company |
| `salary` | Monthly salary ($) |
| `city` | City of work |
| `satisfaction_score` | Job satisfaction (1–5) |
| `performance_score` | Performance rating (1–5) |
| `attrition` | Left company: 1 = Yes, 0 = No |

## 🔍 Analysis Overview

### 📊 Basic Analysis
- Employees distribution by department
- Salary distribution across the company
- Average salary by department and position

### 📈 Advanced Analysis
- Attrition rate by department
- Attrition rate by satisfaction score
- Salary comparison: Stayed vs Left employees

### 🔥 Correlation Analysis
- Heatmap of correlations between all numeric variables

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| Total Employees | 250 |
| Attrition Rate | 30% |
| Highest Attrition Dept | Engineering (43%) |
| Lowest Attrition Dept | Finance (26%) |
| Main Attrition Driver | Satisfaction Score |
| Avg Salary | ~$3,000 |
| Best Paid Position | HR Director |

## 💡 Conclusions
- **Satisfaction score** is the strongest predictor of attrition (correlation -0.6)
- Employees with satisfaction score 1 leave in **71% of cases**
- **Engineering** has the highest attrition despite competitive salaries
- **Salary alone** does not predict attrition (correlation only -0.07)

## 🛠️ Tools & Skills

- **Language:** Python 3
- **Libraries:** pandas, matplotlib, seaborn, numpy
- **Environment:** Jupyter Notebook (VS Code)
- **Concepts:** EDA, data visualization, correlation analysis, groupby aggregations

## 👤 Author

**diana-data-analyst** | [GitHub](https://github.com/diana-data-analyst)
