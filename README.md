# 📊 HR Analytics Dashboard using Power BI

## 🔗 Objective
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights to improve workforce retention. This dashboard enables HR teams to analyze employee attrition trends and make data-driven decisions.

---

## 🌟 Project Highlights

- **Deep Dive into HR Data**: Uncovered valuable insights through detailed analysis.
- **Interactive Dashboards**: Designed intuitive and visually appealing dashboards using Power BI.
- **Strategic Insights**: Provided actionable recommendations to improve retention strategies.

---

## 🚀 Steps Followed

### 1. **Data Gathering**
   - Imported raw `.csv` HR data into Power BI.
   - Transformed and cleaned the data using Power Query Editor.

### 2. **Data Cleaning**
   - Removed empty columns, duplicates, and errors.
   - Renamed columns for clarity and consistency.
   - Auto-detected and validated data types for each column.

### 3. **Data Processing**
   - Created a new column `AttritionCount` using conditional column logic:
     - **Condition**: If `Attrition = 'Yes'`, then `1`, else `0`.
   - Generated key metrics with DAX formulas:
     - **Attrition Rate**: `(SUM([AttritionCount]) / SUM([EmployeeCount])) * 100`.

### 4. **Data Analysis**
   - Built diverse visualizations including bar charts, pie charts, KPIs, and matrix tables.
   - Designed interactive dashboards for HR analytics.

---

## 📋 Key Dashboard Questions

1. **Total Employee Count**: How many employees does the organization have?
2. **Average Metrics**: What are the average age and salary of employees?
3. **Gender-based Attrition**: How does attrition compare between males and females?
4. **Department Insights**: Which department has the most employees and the highest attrition rate?
5. **Education Field Analysis**: Which field of education has the most employees?
6. **Business Travel Trends**: Which type of business travel is most common?
7. **Age Group Attrition**: What is the attrition rate across different age groups?

---

## 📈 Visualizations and Tools Used

- **Calculated Fields**: Attrition Rate, Active Employees.
- **Charts**:
  - Bar and Clustered Charts.
  - Donut and Pie Charts.
- **KPI Indicators**: Key performance metrics for HR insights.
- **Matrix Table**: Job satisfaction ratings.
- **Slicers and Filters**: Interactive data filtering by education field, department, and more.

---

## 🔍 Key Insights

Here are the key insights from your HR Analytics Dashboard:

1. **Attrition Rate**: 16.1% of the workforce (237 out of 1470 employees) has left the organization.

2. **Attrition by Education**: Highest in **Life Sciences** (38%).

3. **Attrition by Age**: Most attrition in the **26-35** age group (116 employees).

4. **Attrition by Gender**: Higher attrition among **males** (140) than **females** (79).

5. **Attrition by Salary**: Most attrition is in the **Upto 5k salary slab** (163 employees).

6. **Attrition by Job Role**: **Laboratory Technicians (62)** and **Sales Executives (57)** have the highest attrition.

7. **Attrition by Years at Company**: Highest attrition is among **new hires** (0 years) with 59 employees leaving.

---

## 💡 Lessons Learned

- Power BI tools and functionalities like:
  - DAX queries for metrics calculation.
  - Advanced filtering and data slicing.
  - Interactive visualization techniques.
 
## download data from

[data](https://github.com/vandanaakula/HR_AnalyticsDashboard_project/blob/main/HR_Analytics%20(1).csv)

## Author
This project was carried out by AKULA VENKATA SAI VANDANA.

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/vandana-akula-371695250/) for feedback, suggestions, or collaboration opportunities.


