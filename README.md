📊 HR Analytics Dashboard – Power BI Project
**Overview**

This project analyzes Human Resources data for a fictitious company called Atlas Labs using Power BI.
The goal is to explore employee data, identify attrition patterns, analyze employee demographics and performance, and provide insights that can help the organization improve employee retention and workforce planning.

The project includes data modeling, exploratory data analysis (EDA), DAX calculations, and interactive dashboard creation.

**Dataset**

The dataset contains HR information about employees of Atlas Labs.

Data includes:
Employee demographics (age, gender, marital status, ethnicity)
Job information (department, job role, hire date)
Salary information
Performance ratings
Satisfaction metrics
Attrition status

The dataset consists of:
1 Fact Table: FactPerformanceRating

4 Dimension Tables:
   DimEmployee
   DimEducationLevel
   DimRatingLevel
   DimSatisfiedLevel

1 Date Table: DimDate
The data model follows a star schema structure for efficient analysis.

**Tools & Technologies**

Power BI – Data modeling and dashboard development
Power Query – Data transformation
DAX (Data Analysis Expressions) – Measures and calculations
CSV Files – Source dataset

**Project Steps**

1. Data Loading
Imported multiple CSV files into Power BI.
Created fact and dimension tables.

2. Data Modeling
Built relationships between tables.
Implemented a star schema model.
Created a Date dimension table for time-based analysis.

3. Exploratory Data Analysis (EDA)
Created measures such as:
Total Employees
Active Employees
Inactive Employees
Attrition Rate
Analyzed hiring trends over time.

4. Demographic Analysis
Examined employees by:
Age groups
Gender
Marital status
Ethnicity
Calculated average salary by ethnicity.

5. Performance Analysis
Built a Performance Tracker to analyze:
Job Satisfaction
Environment Satisfaction
Work-Life Balance
Manager and Self Ratings
Added employee-level filters for detailed analysis.

6. Attrition Analysis
Investigated factors affecting attrition such as:
Department and job role
Business travel frequency
Overtime
Employee tenure

**Dashboard**

The Power BI dashboard includes the following pages:

1️⃣ Overview
Total Employees
Active vs Inactive Employees
Attrition Rate
Hiring trends

2️⃣ Demographics
Employees by Age and Gender
Marital Status distribution
Ethnicity vs Average Salary

3️⃣ Performance Tracker
Employee performance ratings
Job satisfaction trends
Review tracking

4️⃣ Attrition Analysis
Attrition by department and job role
Attrition by travel frequency
Attrition by overtime
Attrition by tenure
Results & Insights

**Key insights from the analysis:**

Atlas Labs has employed over 1,470 employees.
The company currently has more than 1,200 active employees.
The Technology department has the highest number of employees.
The overall employee attrition rate is around 16%.
Most employees are in the 20–29 age group.
Employees who travel frequently show higher attrition rates.
Employees working overtime are more likely to leave the organization.

**Business Recommendations**

Review travel requirements for employees.
Monitor overtime workload to prevent employee burnout.
Implement retention strategies for high-risk groups.

✅ This project demonstrates skills in Power BI, data modeling, DAX, HR analytics, and data storytelling.
