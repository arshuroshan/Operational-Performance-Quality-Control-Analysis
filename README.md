# Task Defect Performance Analysis in XYZ Company

This project presents a comprehensive operational performance and quality control analysis for XYZ Company, focusing on task execution efficiency, defect rates, and error trends. The goal is to generate actionable insights to support data-driven decisions for improving productivity, quality, and managerial oversight.

## 📁 Project Files

- **📄 Documentation (PDF):** Detailed problem statement, dataset features, analysis scope, and DAX formulas.
- **📊 Presentation (PDF):** High-level insights, visualizations, and executive summary.
- **🎯 Presentation (PPTX):** Editable PowerPoint version of the report.

## 📁 Project Structure
📊 Operational-Performance-Quality-Control-Analysis/
- ├── README.md
- ├── Dataset.xlsx                            # Quality Control Analysis Dataset.xlsx
- ├── Final_Report.pdf                        # Quality Control Analysis Final Dashboard.pdf
- ├── Analysis_PPT.pdf                        # Operational Performance and Quality Control Analysis_PPT.pdf
- ├── Analysis_Documentation.pdf              # Operational Performance and Quality Control Analysis_doc.pdf
- ├── Dashboard.pbix                          # Quality Control Analysis.pbix
- ├── Dashboard_Template.pbit                 # Quality Control Analysis Final.pbit
- ├── Dashboard_Overview.png
- ├── Dashboard_Details.png
- ├── Overall_Analysis.png


## 🎯 Problem Statement

As a Data Analyst, the task is to analyze a dataset containing:

- Task performance records
- Defects and errors per task
- Employee, manager, auditor, and department metadata

XYZ Company operates across multiple departments, and quality inconsistencies prompted a deep-dive into operational performance.

## 🔍 Analysis Objectives

1. **Task Performance Analysis**  
   Identify trends in task frequency, completion rates, and departmental distribution.

2. **Defect & Error Analysis**  
   Analyze which task types are more defect/error-prone and assess their impact on overall performance.

3. **Employee Productivity**  
   Evaluate individual employee output and identify top and low performers.

4. **Managerial Oversight**  
   Examine how managers influence task quality and respond to performance issues.

5. **Departmental Efficiency**  
   Compare departments on metrics like task throughput, defect rates, and sample analysis.

6. **Auditor Performance**  
   Assess the thoroughness and consistency of defect/error detection among auditors.

7. **Location-Based Trends**  
   Discover performance variations across office locations (e.g., China, US, UK, Australia).

## 📊 Key Findings

- **Overall Quality Score:** 84.63%
- **Top Department:** Sales (83.94%)
- **Top Location:** China (86.76%)
- **Top Employee:** Anthony Noah (93.72%)
- **Highest Defect Rate Month:** March (23.81%)
- **Highest Error Rate Month:** December (26.53%)

## 🧮 DAX Formulas Used

- `Defect % = SUM(Defects) / SUM(Sample)`
- `Error % = SUM(Errors) / SUM(Sample)`
- `Quality Score = 1 - Defect %`  
*(Only shown when data is available)*

For full DAX expressions, see the **PDF document** in the `docs/` folder.

## 🛠 Tools & Technologies

- **Power BI** for visualization
- **DAX** for calculations
- **Excel / CSV** (dataset assumed)
- **Python or SQL** (optional for further enhancement)

---

## 👨‍💼 Author

**Arshad Roshan**  
📍 Kerala, India  
🎓 BTech in Computer Science | Data Science Certified  
📬 https://www.linkedin.com/in/arshadroshan/

---

## ⭐️ Support

If you find this project helpful, please consider giving it a ⭐️ on GitHub.  
Feel free to fork, clone, or contribute suggestions for improvements!
