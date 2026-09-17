📱 Smartphone Usage Analysis Dashboard

📊 Project Overview
Smartphone Usage Analysis Dashboard is a Microsoft Power BI data visualization project designed to analyze smartphone usage patterns and their relationship with lifestyle, productivity, sleep, stress, and smartphone addiction.
The report transforms smartphone-usage data into interactive dashboards and visual reports that help users explore patterns across age groups, gender, addiction level, stress level, screen time, gaming, social media usage, sleep, notifications, and academic/work impact.

🎯 Objectives
Analyze daily and weekend smartphone screen time.
Understand smartphone usage across different age groups and genders.
Examine relationships between smartphone addiction and usage behavior.
Analyze social media and gaming usage.
Explore sleep hours in relation to smartphone usage.
Examine stress levels and their distribution.
Analyze the impact of smartphone usage on academic/work activities.
Identify factors associated with high screen-time and addiction status.
Provide interactive filtering for deeper analysis.

🛠️ Tools & Technologies
Tool / Technology
Purpose
Microsoft Power BI
Data visualization and dashboard development
Power BI Data Model
Data analysis and report calculations
DAX / Power BI aggregations
Measures and analytical calculations
Power BI Visuals
Charts, cards, slicers, decomposition tree, and key influencers

📁 Dataset
The Power BI report uses a dataset/table named:
smartphone_usage
The analysis includes fields such as:
user_id
age
gender
Age Group
daily_screen_time_hours
weekend_screen_time
sleep_hours
gaming_hours
social_media_hours
work_study_hours
app_opens_per_day
notifications_per_day
stress_level
addiction_level
addicted_label
Addicted Status
High Screen Time user
User Count
academic_work_impact
transaction_id

📑 Report Pages
The PBIX file contains multiple report pages for different analytical perspectives.
1. Dashboard
The main dashboard provides a high-level overview using:
KPI cards
Smartphone usage comparisons
Sleep analysis
Screen-time analysis
Addiction-level analysis
Stress-related analysis
Age-group distribution
Transaction/user analysis
Interactive slicers

2. Report 1 – Detailed Analysis
This page focuses on detailed relationships between smartphone usage and user characteristics.
Visuals include:
Decomposition Tree
Line charts
Clustered bar charts
KPI cards
Gender slicer
Age Group slicer
Addiction Level slicer
The analysis covers:
Weekend screen time
Social media hours
App opens per day
Notifications per day
Academic/work impact
Work/study hours
Addiction level by gender
Addiction level by age group

4. Report 1 – User Metrics
A metric-focused page containing cards for:
Average/summary age
Sleep hours
App opens per day
Gaming hours
Addiction status
Work/study hours
Social media hours
Notifications per day
Weekend screen time
Daily screen time
User count

4. Page 2 – Behavioral Analysis
This page provides deeper behavioral analysis through:
Average sleep hours by age group
Work/study hours
Social media hours by addiction level
Average age
Stress-level distribution
High-screen-time user distribution
Key Drivers analysis
Gaming hours
Gender and stress-level filtering
The Key Drivers visual helps explore factors associated with the selected analytical outcome using variables such as screen time, social media hours, gaming hours, notifications, weekend screen time, age group, and addiction status.

5. Report 2 – Usage & Addiction Analysis
This page explores:
Addiction level by users
Addicted vs. non-addicted users
Gaming and social media usage
Screen time vs. sleep hours
Screen time by age group
Screen time by gender
Gender, age-group, and addiction-level filtering
A scatter chart is included to visually examine the relationship between daily screen time and sleep hours.

📈 Key Visualizations
The report uses a variety of Power BI visuals:
📌 Cards – KPI and summary metrics
📊 Clustered Bar Charts – category comparisons
📊 Clustered Column Charts – usage comparisons
📈 Line Charts – trends/comparisons across age groups
🥧 Pie/Donut Charts – distribution analysis
🔍 Scatter Chart – relationship between screen time and sleep
🌳 Decomposition Tree – hierarchical analysis
🎯 Key Drivers Visual – factor exploration
🔽 Slicers – interactive filtering

🔎 Analysis Areas
Smartphone Screen Time
Analysis of daily and weekend screen-time behavior across users, genders, and age groups.
Smartphone Addiction
Exploration of addiction levels and addicted-user classifications in relation to smartphone usage patterns.
Social Media & Gaming
Comparison of time spent on social media and gaming across addiction levels and user groups.
Sleep
Analysis of sleep hours and its relationship with smartphone screen time and age groups.
Stress
Visualization of stress-level distributions and their relationship with smartphone usage.
Productivity
Analysis of work/study hours and academic/work impact in relation to smartphone usage behavior.
User Engagement
Analysis of app opens, notifications, and other usage indicators.

🎛️ Interactive Features
The report contains interactive slicers that allow users to filter the analysis by dimensions such as:
Gender
Age Group
Addiction Level
Stress Level
Addicted Status
Selecting a filter dynamically updates the related visuals on the report page.

📂 Repository Structure
A recommended GitHub repository structure is:
smartphone-usage-analysis/
│
├── README.md
├── smartphone.pbix
│
└── assets/
    └── screenshots/
        ├── dashboard.png
        ├── report1.png
        └── report2.png


▶️ How to Open the Project
Download or clone this repository.
Install Microsoft Power BI Desktop.
Open smartphone.pbix.
Allow Power BI to load the report and data model.
Navigate through the report pages.
Use the available slicers to interact with the visualizations.
