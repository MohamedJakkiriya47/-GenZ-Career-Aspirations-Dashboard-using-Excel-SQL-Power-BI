# Gen-Z Career Aspiration Analysis (SQL | Excel | Power BI)

## Project Overview

This project analyzes **Gen-Z career aspirations, learning preferences, and workplace expectations** using survey data collected from respondents across multiple countries.

### The goal of this analysis is to understand

- What careers **Gen-Z prefers**
- What factors **influence their career choices**
- Their **preferred learning styles**
- Their **expectations from managers**
- Their **preferred work environments**
- **Salary expectations over time**

These insights help **organizations, recruiters, and educators design future-ready workplace strategies and career programs aligned with Gen-Z expectations.**

---

# Dataset Overview

**Dataset:** Gen-Z Career Aspirations Survey  

- Total Participants: **3,934**
- Male Respondents: **2,333**
- Female Respondents: **1,597**
- Countries Represented: **12**
- Unique Pin Codes: **2,085**

### Dataset Fields

- Career Aspirations  
- Career Influencing Factors  
- Preferred Work Environment  
- Learning Preferences  
- Manager Type Preference  
- Expected Salary  
- Gender  
- Country  

---

# Tools Used

- **SQL (MySQL)** – Data analysis and aggregation  
- **Excel** – Data cleaning and exploratory analysis  
- **Power BI** – Dashboard visualization  

---

# Data Analysis Workflow

1. Data cleaning and preprocessing using **Excel**
2. Data exploration and aggregation using **SQL queries**
3. Dashboard development using **Power BI**
4. Extracting insights and generating recommendations

---

# SQL Analysis

## Career Aspirations by Industry

```sql
SELECT Career_aspirations,
COUNT(Career_aspirations) AS count
FROM gen_z
GROUP BY Career_aspirations
ORDER BY COUNT(Career_aspirations) DESC;
```

**Insight**

- Creative and design careers show the highest interest.
- Operations and business management roles are also popular.
- Technology and AI careers are gaining popularity.

---

## Career Influencing Factors

```sql
SELECT Career_influencing_factors,
COUNT(Career_influencing_factors) AS count
FROM gen_z
GROUP BY Career_influencing_factors
ORDER BY COUNT(Career_influencing_factors) DESC;
```

**Insight**

- Parents strongly influence career choices.
- Social media and peer networks also impact decision-making.

---

## Preferred Work Environment

```sql
SELECT Preferred_work_environment,
COUNT(Preferred_work_environment) AS count
FROM gen_z
GROUP BY Preferred_work_environment
ORDER BY COUNT(Preferred_work_environment) DESC;
```

**Insight**

- Hybrid work environments are most preferred.
- Remote work is also popular among Gen-Z.
- Fully in-office roles are less preferred.

## Salary Expectations by Career

```sql
SELECT Career_aspirations,
AVG(Expected_salary) AS average_salary
FROM gen_z
GROUP BY Career_aspirations
ORDER BY average_salary DESC;
```

**Insight**

- Technology and AI careers show the highest expected salaries.
- Creative and education careers show moderate salary expectations.

---

# Excel Dashboard Insights

![Excel Dashboard](images/EXCEL.png)

The Excel dashboard focuses on learning preferences, team collaboration trends, and salary expectations.

## Work Setup Preference

- 1,919 respondents prefer working in teams of 5–6 members
- 1,626 respondents prefer teams of 2–3 members
- 735 respondents prefer working alone

This shows Gen-Z prefers collaborative work environments with small teams.

---

## Learning Preferences

- 2,521 respondents prefer self-paced learning
- Hands-on learning such as trial projects is also popular.

This reflects Gen-Z’s preference for flexible and practical learning methods.

---

## Ideal Manager Type

Most respondents prefer managers who

- Clearly explain expectations
- Set goals and help employees achieve them
- Provide mentorship and guidance

Managers who set unrealistic expectations received very low support.

---

## Salary Expectations Trend

Average expected salary increased from 2022 to 2024, followed by a decline in 2025.

Possible reasons include:

- Economic uncertainty
- Market awareness changes
- Adjusted expectations.

---

# Power BI Dashboard

The Power BI dashboard analyzes manager expectations, career drivers, and mission alignment trends among Gen-Z respondents.

## Dashboard Metrics

- Total Survey Responses: 39K
- Countries Represented: 12
- 3-Year Average Salary Expectation: ₹38K
- 5-Year Average Salary Expectation: ₹108K.

---

## Manager Aspirations Dashboard

![Excel Dashboard](images/MANAGER_ASPIRATION.png)

This dashboard visualizes Gen-Z expectations from managers and career influencing factors.

**Key Insights**

- The most preferred manager type is "Explains Expectations and Supports Goals"
- Goal-oriented leadership styles are highly valued
- Parents and social networks strongly influence career decisions.

---

## Mission Alignment Dashboard

![Excel Dashboard](images/MISSION_ASPIRATION.png)

This dashboard analyzes how Gen-Z career aspirations align with company missions and workplace values.

**Key Insights**

- Design / Creative sector shows the highest misalignment
- Operations and business management roles also show gaps
- Hybrid and remote work preferences peaked in 2023.

---

# Key Insights

**Career Aspirations**

Creative and business roles attract the highest interest among Gen-Z respondents, while technology fields like AI and data analytics are growing rapidly.

**Manager Expectations**

Gen-Z prefers managers who

- Provide clear expectations
- Support goal achievement
- Offer mentorship and guidance

**Work Environment Preferences**

Hybrid and remote work environments are strongly preferred, especially in

- Technology
- Creative industries
- Business roles

**Career Influencing Factors**

Top factors influencing career decisions include

- Parents
- Social media
- Friends and peer networks
  
---

# Recommendations

## For Organizations

- Build collaborative work environments
- Promote mentorship-based leadership
- Offer flexible work models such as hybrid and remote work.

## For Educators

- Provide self-paced learning programs
- Integrate project-based learning

## For Recruiters

- Align job roles with Gen-Z expectations
- Highlight mission-driven company culture
- Use digital platforms to engage young talent
