<img width="1187" height="631" alt="dashboard photo" src="https://github.com/user-attachments/assets/9dc421f4-df7e-4887-a314-e13bf6e2c3d5" />

**📊 HR Analytics Dashboard | Power BI**

📌 Project Overview
This project presents an interactive HR Analytics Dashboard built using Power BI to transform raw HR data into meaningful business insights.
The dashboard helps HR professionals monitor workforce performance, analyze employee attrition, and identify trends that support data-driven decision-making.

🎯 Business Problem
Managing HR data through spreadsheets makes it difficult to answer important business questions such as:

Which department has the highest attrition?
Which salary range experiences the highest employee turnover?
Which age group is most likely to leave the company?
Does job satisfaction affect attrition?
How does employee experience relate to retention?

This dashboard answers these questions through interactive visualizations and dynamic filtering.

📷 Dashboard Preview
The dashboard provides HR managers with a complete overview of employee performance, workforce demographics, and attrition trends.

🔍 Key Insights
Using this dashboard, HR managers can quickly discover:

Departments with the highest employee attrition.
Salary ranges where turnover is more frequent.
Job roles experiencing higher employee loss.
The relationship between job satisfaction and employee attrition.
Workforce distribution by age and gender.
Employee experience across the organization.

📊 Key Performance Indicators
👥 Total Employees
✅ Active Employees
🚪 Attrition Count
📉 Attrition Rate
🎂 Average Age
💼 Average Experience
📈 Dashboard Features
Interactive Dashboard
KPI Cards
Dynamic Filters (Slicers)
Department Analysis
Salary Analysis
Job Role Analysis
Gender Distribution
Age Group Analysis
Experience Analysis
Employee Attrition Analysis
⚙️ Dashboard Interactivity

Users can interact with the dashboard by filtering data based on departments and age groups. All KPIs and charts update dynamically, making data exploration faster and more effective.


💡 DAX Measure Example
Attrition Rate % =
DIVIDE(
    SUM('HR_Analytics-4'[AttritionCount]),
    SUM('HR_Analytics-4'[EmployeeCount]),
    0
)

📈 Business Impact
This dashboard enables HR teams to:
Monitor employee turnover.
Improve employee retention strategies.
Analyze workforce demographics.
Identify high-risk departments.
Make faster, data-driven business decisions.

📚 Skills Demonstrated
Data Cleaning
Power Query
DAX
KPI Design
Dashboard Development
Data Visualization
Business Intelligence

🚀 Future Improvements
SQL Server Integration
Automatic Data Refresh
Drill-through Pages
Forecasting Attrition
Predictive Analytics
Power BI Service Deployment

📂 Repository Structure
HR-Analytics-Dashboard-PowerBI
│
├── Dashboard.pbix
├── HR_Analytics.xlsx
├── Demo.mp4
├── README.md
└── Images
    ├── banner.png
    └── dashboard.png

🎥 Dashboard Demo
The repository includes a short demo video showcasing the interactive features of the dashboard.


**Author : Shimaa Emad**
