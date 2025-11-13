# HR Analytics Dashboard | Power BI

*An end-to-end HR Analytics Dashboard in Power BI to analyze employee attendance, leave patterns, and workforce trends.*

<!-- Add Table of Contents here -->
<h2>Table of Contents</h2>
<ul>
  <li><a href="#project-overview">Project Overview</a></li>
  <li><a href="#objective">Objective</a></li>
  <li><a href="#dataset">Dataset</a></li>
  <li><a href="#data-cleaning--transformation-power-query">Data Cleaning & Transformation (Power Query)</a></li>
  <li><a href="#data-modeling">Data Modeling</a></li>
  <li><a href="#dax-calculations">DAX Calculations</a></li>
  <li><a href="#dashboard-design">Dashboard Design</a></li>
  <li><a href="#tools--technologies">Tools & Technologies</a></li>
  <li><a href="#key-learnings--achievements">Key Learnings / Achievements</a></li>
  <li><a href="#project-structure">Project Structure</a></li>
  <li><a href="#dashboard-preview">Dashboard Preview</a></li>
  <li><a href="#how-to-use">How to Use</a></li>
  <li><a href="#credits">Credits</a></li>
  <li><a href="#feedback">Feedback</a></li>
  <li><a href="#tags">Tags</a></li>
</ul>

---


## Project Overview
This project is inspired by **Codebasics' HR Analytics** guided project.  
It helps HR teams analyze employee attendance, leave behavior, and work preferences — enabling **data-driven workforce decisions** and improved productivity insights.

*This showcases my ability to design data models, build HR KPIs, and visualize insights in Power BI — aligning with data analyst and BI reporting roles.*

---

## Objective
To analyze employee presence, work-from-home, and leave data, helping HR identify trends and take **data-backed decisions** to optimize attendance policies.

---

## Dataset
The dataset includes **employee attendance data (May–July)** with the following fields:  
- Employee ID & Department  
- Attendance date  
- Work mode (Office / WFH)  
- Leave type (SL, PL, etc.)  
- Presence status  

**Note:** Data cleaning and transformation were performed entirely in **Power Query** inside Power BI.

---

## Data Cleaning & Transformation (Power Query)
Steps performed:  
1. Used the first row as headers  
2. Removed unnecessary top rows  
3. Unpivoted columns to normalize data  
4. Created a **Power Query Function** for data transformation  
5. **Invoked the function** across monthly files to automate repetitive steps  
6. Managed parameters for dynamic file paths  
7. Changed data types for consistency  

✅ This approach ensures **scalable, reusable, and efficient data preparation** — a key practice in enterprise BI workflows.

---

## Data Modeling
- Established relationships between fact and dimension tables  
- Created a **Measures Table** for all DAX calculations  
- Followed a **star schema** for scalability and performance  

---

## DAX Calculations
Key measures created:  
- `Presence %`  
- `Sick Leave %`  
- `Work From Home %`  
- `Total Working Days`  
- `Average Attendance`  

**Pro Tip:** Keeping all DAX measures in a dedicated “_Measures” table improves readability and dashboard performance.

---

## Dashboard Design
Power BI visuals used:  
- **Cards:** Summary of key HR metrics  
- **Line Chart:** Attendance trends over time  
- **Table:** Employee-level details  
- **Slicers:** Month, department, employee  

✅ Designed for **clean, HR-friendly insights and executive decision-making**.

---

## Tools & Technologies
- **Power BI Desktop**  
- **Power Query (M Language)**  
- **DAX**  
- **Excel** (raw dataset)

---

## Key Learnings / Achievements
- Automated repetitive HR data cleaning using **Power Query Functions & Invocations**  
- Built reusable DAX measures for HR KPIs, improving **dashboard efficiency**  
- Designed interactive visuals for **executive-level insights**  
- Developed an **end-to-end BI workflow** (Power Query → DAX → Visualization)

---

## Project Structure

HR_Analytics_Project_PowerBi/
├── Dataset/
│ └── Attendance-Sheet-2022-2023.xlsx
├── Reports/
│ └── HR_Analytics_Dashboard.pbix
├── Dashboard/
│ └── main_dashboard.png
└── README.md

***
---

## Dashboard Preview
![HR Analytics Dashboard](Dashboard/main_dashboard.png)

---

## How to Use
1. Open `HR_Analytics_Dashboard.pbix` in Power BI Desktop  
2. Load the dataset from `Dataset/Attendance-Sheet-2022-2023.xlsx`  
3. Explore KPIs using slicers for month, department, or employee  


---

## Credits
Project inspired by **[Codebasics](https://codebasics.io/)**  
Special thanks to **Dhaval Patel** & **Hemanand Vadivel** for structured learning resources.

---

## Feedback
Connect with me on [LinkedIn](https://www.linkedin.com/in/priyanka-o-2a58b6273) for suggestions or collaboration.  

---

**Tags:** Power BI, HR Analytics, Power Query, Function Invocation, Data Visualization, DAX, Business Intelligence, Dashboard Design
