# ORDERS_DATA_PROJECT

🔍 Step-by-Step Process for HR Data Analysis in Power BI
✅ Step 1: Load the Data
Open the .pbix file in Power BI Desktop.

Click on Transform Data to explore tables (e.g., Employee details, Salary, Departments, Attrition).

✅ Step 2: Clean and Prepare the Data
Remove null/missing values.

Format dates and numeric columns.

Create necessary calculated columns or measures using DAX:

Example: Tenure = DATEDIFF(HireDate, TODAY(), YEAR)

Example: Attrition Rate = DIVIDE(COUNT(EmployeeID where Attrition = "Yes"), Total Employees)

✅ Step 3: Create Relationships
Ensure relationships exist between key tables:

Employee ↔ Department

Employee ↔ Salary

Employee ↔ Performance

✅ Step 4: Build Visualizations
Suggested charts:

📊 Bar Chart: Employee count by department

📈 Line Chart: Attrition trend over time

📍 Pie Chart: Gender distribution

🌐 Map (if locations available): Office/branch headcount

📉 Heatmap/Table: Attrition by age group, tenure, or performance

✅ Step 5: Add Key Metrics (DAX Measures)
Total Employees

Avg. Salary

Avg. Age

Attrition Rate

Gender Ratio

Department-wise headcount

✅ Step 6: Create an Interactive Dashboard
Use slicers for:

Department

Gender

Location

Job Level

Add tooltips to provide deeper drill-down insights

📌 Key Points to Focus On
When analyzing HR data:

Attrition (Resignation) Patterns:

Who is leaving (department, job role)?

When are they leaving (tenure)?

Why might they be leaving (low performance, low salary)?

Workforce Composition:

Age & gender distribution

Department-wise strength

Contract vs. permanent staff

Compensation Analysis:

Salary by department/job level

Salary vs performance correlation

Salary vs attrition relationship

Performance Trends:

High performers retention

Department-wise performance

📊 Common Key Insights (Based on HR Data Trends)
(Note: These are examples. Please confirm based on your actual report)

🔺 Attrition Rate is highest in the Sales department with low average salary and short tenure.

👩‍💼 Female employees constitute 45% of the workforce but have higher attrition in mid-level roles.

🧓 Employees aged 30–40 are the most stable and have the highest performance scores.

💸 Higher-performing employees tend to earn significantly more, especially in IT & Finance roles.

🕒 Employees with <2 years of experience show 2x attrition rate compared to those >5 years.


