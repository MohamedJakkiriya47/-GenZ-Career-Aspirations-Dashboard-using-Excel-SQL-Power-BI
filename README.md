Gen-Z Career Aspiration Analysis (SQL | Excel | Power BI)
Project Overview

This project analyzes Gen-Z career aspirations, learning preferences, and workplace expectations using survey data collected from respondents across multiple countries.

The goal of the analysis is to understand:

What careers Gen-Z prefers

What factors influence their career choices

Their preferred learning styles

Their expectations from managers

Their preferred work environments

Salary expectations over time

These insights help organizations, recruiters, and educators design future-ready workplace strategies and career programs aligned with Gen-Z expectations.

Dataset Overview

Dataset: Gen-Z Career Aspirations Survey

Total Participants: 3,934
Male Respondents: 2,333
Female Respondents: 1,597
Countries Represented: 12
Unique Pin Codes: 2,085

Dataset Features

The dataset contains the following fields:

Career Aspirations

Career Influencing Factors

Preferred Work Environment

Learning Style Preferences

Manager Type Preference

Expected Salary

Gender

Country

Tools Used

SQL (MySQL) – Data aggregation and analysis

Excel – Data cleaning and exploratory analysis

Power BI – Dashboard visualization and reporting

Data Analysis Workflow

Data cleaning and formatting in Excel

SQL queries to analyze survey responses

Building dashboards in Power BI

Extracting insights and recommendations

SQL Analysis
1. Career Aspirations by Industry
SELECT Career_aspirations,
COUNT(Career_aspirations) AS count
FROM gen_z
GROUP BY Career_aspirations
ORDER BY COUNT(Career_aspirations) DESC;

Insight

Creative and design careers show the highest interest among respondents.

Operations and business management roles are also highly preferred.

Technical roles such as AI and Data Analytics are gaining popularity.

2. Career Influencing Factors
SELECT Career_influencing_factors,
COUNT(Career_influencing_factors) AS count
FROM gen_z
GROUP BY Career_influencing_factors
ORDER BY COUNT(Career_influencing_factors) DESC;

Insight

Parents and family influence career decisions the most.

Social media and peer networks also play an important role.

3. Preferred Work Environment
SELECT Preferred_work_environment,
COUNT(Preferred_work_environment) AS count
FROM gen_z
GROUP BY Preferred_work_environment
ORDER BY COUNT(Preferred_work_environment) DESC;

Insight

Hybrid work environments are the most preferred.

Remote work is also popular among Gen-Z respondents.

Fully in-office work environments are less preferred.

4. Salary Expectations by Career
SELECT Career_aspirations,
AVG(Expected_salary) AS average_salary
FROM gen_z
GROUP BY Career_aspirations
ORDER BY average_salary DESC;

Insight

Technology and AI careers show the highest expected salaries.

Creative and education careers show moderate salary expectations.

Excel Dashboard Insights

The Excel dashboard focuses on learning preferences, team collaboration preferences, and salary expectations.

Work Setup Preference

1,919 respondents prefer working in teams of 5–6 members

1,626 respondents prefer teams of 2–3 members

735 respondents prefer working alone

This indicates that Gen-Z strongly prefers small collaborative teams.

Learning Preferences

2,521 respondents prefer self-paced learning

Hands-on learning such as trial projects is also highly preferred.

This suggests that Gen-Z values flexible and practical learning methods.

Ideal Manager Type

Most respondents prefer managers who:

Clearly explain expectations

Set goals and help employees achieve them

Provide mentorship and guidance

Managers who set unrealistic expectations received very low support.

Salary Expectations Trend

Average salary expectations increased between 2022 and 2024, followed by a slight decline in 2025.

Possible reasons include:

Economic uncertainty

Changing job market expectations

Increased awareness of market salaries

Excel Dashboard Preview



Total Participants

Preferred Work Setup

Preferred Learning Environment

Ideal Manager Type

Average Salary Trend

Power BI Dashboard

The Power BI dashboard analyzes manager expectations, career drivers, and mission alignment trends among Gen-Z respondents.

Key Metrics

Total Survey Responses: 39K

Countries Represented: 12

Average 3-Year Salary Expectation: ₹38K

Average 5-Year Salary Expectation: ₹108K

Manager Aspirations Dashboard

This dashboard focuses on Gen-Z expectations from managers and career influences.

Key Insights

The most preferred manager type is “Explains Expectations and Supports Goals.”

Goal-oriented leadership styles are more valued than strict authority.

Parents and close networks strongly influence career decisions.

Manager Dashboard Preview

📌 ADD SCREENSHOT 2 HERE

Insert the Manager Aspirations Power BI dashboard screenshot here.

Example:

![Manager Aspirations Dashboard](images/manager_dashboard.png)
Mission Alignment Dashboard

This dashboard explores whether Gen-Z career goals align with company missions and workplace values.

Key Insights

The Design / Creative sector shows the highest misalignment between career aspirations and company missions.

Operations and Business Management also show noticeable gaps.

Hybrid and remote work trends peaked in 2023, indicating strong demand for flexible work models.

Mission Alignment Dashboard Preview

📌 ADD SCREENSHOT 3 HERE

Insert the Mission Alignment Power BI dashboard screenshot here.

Example:

![Mission Alignment Dashboard](images/mission_dashboard.png)
Key Insights
Career Aspirations

Creative and business roles attract the most interest among Gen-Z respondents.

Manager Expectations

Gen-Z prefers managers who provide:

Clear expectations

Goal-oriented leadership

Mentorship support

Work Environment Preferences

Hybrid and remote work models are strongly preferred, especially in:

Technology

Creative industries

Business roles

Career Influencing Factors

Top factors influencing career decisions include:

Parents

Social media

Friends and peer networks

Recommendations
For Organizations

Build collaborative work environments

Promote mentorship-based management

Provide flexible work options

For Educators

Offer self-paced learning programs

Integrate project-based learning

For Recruiters

Align job roles with Gen-Z workplace expectations

Promote purpose-driven company culture

Use digital platforms to attract young talent
