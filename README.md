# Student Performance Dashboard – Academic & Behavioral Insights

##  Overview

This Power BI dashboard analyzes student academic performance and behavioral patterns in a single interactive report. It helps identify performance trends, attendance issues, behavior indicators, and overall student progress using clear visualizations and KPIs.

The dashboard is designed to make student data easier to understand for teachers, academic coordinators, and school management.

---

##  Dashboard Pages

---
# Academic
<img width="1707" height="970" alt="Screenshot 2026-06-29 at 11 36 04 AM" src="https://github.com/user-attachments/assets/9cba6537-329b-4aac-86cd-ed5260da64f2" />



###  Academic Dashboard
- Total Students
- Average Marks
- Pass Percentage
- Subject-wise Performance
- Grade Distribution
- Student Performance Trend
- Interactive Filters
  
---
# Behavior
<img width="1699" height="968" alt="Screenshot 2026-06-29 at 11 36 45 AM" src="https://github.com/user-attachments/assets/699b766a-665a-498b-9f3b-c9e9c1603a2f" />




###  Behavior Dashboard
- Attendance Analysis
- Discipline Records
- Student Behavior Overview
- Behavioral Trend Analysis
- Performance vs Attendance Comparison
---
# Student Profile
<img width="1710" height="968" alt="Screenshot 2026-06-29 at 11 37 28 AM" src="https://github.com/user-attachments/assets/1f57ec37-9b53-40a5-9905-b882b6834bad" />


###  Student Profile
- Individual Student Details
- Academic Performance
- Attendance Summary
- Behavior Summary
- Overall Performance Snapshot

---
# Tooltips
<img width="1702" height="975" alt="Screenshot 2026-06-29 at 11 38 00 AM" src="https://github.com/user-attachments/assets/6e9ae48d-a00c-44f6-82e4-b76c4c492ea8" />



###  Tooltips Dashboard
Custom tooltip pages are included to provide additional details when hovering over charts.

---

##  Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Data Modeling

---
##  Data Modeling
<img width="1362" height="787" alt="Screenshot 2026-06-26 at 10 55 22 AM" src="https://github.com/user-attachments/assets/3b62aee3-141b-4a4a-9d35-d12ea5e2dcd1" />


The project follows a Star Schema data model to improve performance and simplify analysis.

- Students (Dimension)
- Scores (Fact)
- Attendance (Fact)
- Behavior (Fact)
  
---

##  Features

- Interactive Dashboard
  
  # Drill Through
- <img width="173" height="379" alt="Screenshot 2026-06-26 at 11 06 36 AM" src="https://github.com/user-attachments/assets/15e62305-6c78-457a-857e-4656f9c9804b" />

- Custom Tooltips
- Dynamic KPIs
- Slicers & Filters
- Clean Navigation
- Responsive Layout

---
## Power Query Transformations
---
# Student Dimension
<img width="1707" height="888" alt="Screenshot 2026-06-26 at 10 56 42 AM" src="https://github.com/user-attachments/assets/217d7aa5-a7c5-47a2-a3d0-8c715bb7bd69" />

---
# Score Fact 
<img width="1710" height="890" alt="Screenshot 2026-06-26 at 10 57 28 AM" src="https://github.com/user-attachments/assets/6dc02418-4cf1-4108-8499-fc433d9a4ed4" />

---
# Attendence Dimension
<img width="1710" height="896" alt="Screenshot 2026-06-26 at 10 58 16 AM" src="https://github.com/user-attachments/assets/6033bfc5-24b6-43bb-aafc-f2dad1109f94" />

---
# Behavior Calculations
<img width="1701" height="894" alt="Screenshot 2026-06-26 at 10 58 54 AM" src="https://github.com/user-attachments/assets/89c53e44-72cb-4c6a-9d8e-ff7b94e2d119" />





The dataset was transformed and prepared using **Power Query Editor** to ensure clean, consistent, and analysis-ready data.



### Transformations Performed

* Removed duplicate records
* Handled missing values
* Changed data types
* Renamed columns
* Split & merged columns
* Created custom columns
* Applied filters and sorting
* Standardized formatting
* Optimized data before loading

---

##  DAX Measures
<img width="890" height="502" alt="Screenshot 2026-06-29 at 12 01 32 PM" src="https://github.com/user-attachments/assets/cf0f8df9-2fe5-43c5-8bc8-97d58ec69996" />



Custom **DAX Measures** were created to calculate KPIs and provide meaningful business insights for the dashboard.



### Key Measures

* Total Students
* Total Attendance
* Average Marks
* Pass Percentage
* Average Behavior Score
* Excellent Students
* At-Risk Students
* Overall Performance Score
* Attendance Rate
* Academic Performance Index

---

## Measure Table
                                                                Project table
<img width="213" height="246" alt="Screenshot 2026-06-26 at 11 02 58 AM" src="https://github.com/user-attachments/assets/0c8721fd-ec19-4191-9ce4-5c92d427759f" />
<img width="159" height="175" alt="Screenshot 2026-06-26 at 11 04 01 AM" src="https://github.com/user-attachments/assets/0a2cd9fe-c031-4291-81d8-f0a94dd341fc" />
<img width="216" height="364" alt="Screenshot 2026-06-26 at 11 04 56 AM" src="https://github.com/user-attachments/assets/ad09f1bd-5814-491a-b465-c8afc02fb75b" />
<img width="212" height="345" alt="Screenshot 2026-06-26 at 11 05 48 AM" src="https://github.com/user-attachments/assets/ea938c40-a6db-4b8f-8f19-2177a83550bc" />





A dedicated **Measure Table** was created to organize all DAX calculations, improving report readability and maintainability.



---

# 
Student Performance Dashboard Features

* Academic Performance Analysis
* Student Attendance Tracking
* Behavioral Performance Monitoring
* Subject-wise Performance Analysis
* Interactive KPIs & Slicers
* Dynamic Filtering
* Cross-Visual Interaction
* Data-Driven Decision Support

---

# Tools & Technologies

Tool             | Purpose                        
                 |  
Power BI Desktop | Dashboard Development          
Power Query      | Data Cleaning & Transformation 
DAX              | KPI & Measure Calculations     
Data Modeling    | Relationship Management       
Excel            | Data Source                    

---

#  What I Learned

This project helped me gain hands-on experience in:

* Cleaning and transforming student data using Power Query
* Building an efficient data model
* Writing DAX measures for academic KPIs
* Designing an interactive Power BI dashboard
* Creating meaningful visualizations
* Improving report performance
* Converting raw student data into actionable insights

---

# Dashboard Outcome

The dashboard enables educators and administrators to:

* Monitor student academic performance
* Analyze attendance trends
* Evaluate behavioral patterns
* Identify high-performing and at-risk students
* Make informed academic decisions using interactive reports

---








--
