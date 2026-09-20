# SKY-Gen-Task-no-1
# 📊 Student Performance Data Analysis

### Python | Pandas | NumPy | Matplotlib | Seaborn | Exploratory Data Analysis

---

## 📌 Project Overview

This project presents an end-to-end **Student Performance Data Analysis** workflow using Python.

The objective is to clean, explore, and analyze student-related academic and demographic data to identify patterns associated with academic performance.

The analysis covers **data preprocessing, exploratory data analysis (EDA), statistical summaries, correlation analysis, and data visualization**.

The project demonstrates practical skills required for a **Data Analyst role**, including transforming raw data into structured information and communicating analytical findings through visualizations.

---

## 🎯 Project Objectives

- Perform data quality checks and preprocessing
- Identify and handle missing values and duplicate records
- Analyze demographic and academic characteristics
- Explore relationships between study habits and academic performance
- Analyze the relationship between previous grades and final grades
- Investigate the relationship between academic failures and final performance
- Generate statistical summaries
- Identify correlations between numerical variables
- Create clear and professional data visualizations
- Export cleaned and analysis-ready datasets

---

## 🗂️ Dataset

The dataset contains student demographic, family, educational, lifestyle, and academic information.

### Key Variables

| Category | Variables |
|---|---|
| Student Information | `school`, `sex`, `age`, `address`, `famsize` |
| Family & Education | `Pstatus`, `Medu`, `Fedu`, `Mjob`, `Fjob`, `guardian` |
| Academic Factors | `studytime`, `failures`, `schoolsup`, `famsup`, `paid` |
| Lifestyle | `activities`, `internet`, `romantic`, `freetime`, `goout` |
| Health & Attendance | `health`, `absences` |
| Academic Performance | `G1`, `G2`, `G3` |

Where:

- **G1** = First-period grade
- **G2** = Second-period grade
- **G3** = Final grade

---

## 🛠️ Technology Stack

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical analysis
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization

---

# 🔄 Data Analysis Workflow

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Exploratory Data Analysis
     ↓
Statistical Analysis
     ↓
Correlation Analysis
     ↓
Data Visualization
     ↓
Cleaned Dataset & Analytical Outputs
📊 Exploratory Data Analysis

The project includes multiple visual analyses to understand student performance.

1. Average Grade by Gender

Compares average academic performance across gender groups.

2. Gender Distribution

Shows the distribution of students across gender categories.

3. Final Grade Distribution

Examines the distribution of students' final grades (G3).

4. Final Grade Boxplot

Provides a statistical view of the spread, central tendency, and potential outliers in final grades.

5. G1 vs G3 Analysis

Examines the relationship between first-period grades and final grades.

6. Study Time vs Grade

Explores whether weekly study time is associated with academic performance.

7. Failures vs Grade

Examines the relationship between previous academic failures and final grades.

8. Correlation Analysis

A correlation heatmap was created to identify relationships among numerical variables.

📈 Analytical Areas

The analysis focuses on the following areas:

Academic Performance
Final grade distribution
G1, G2, and G3 relationships
Grade variability
Student Characteristics
Gender
Age
School
Residential area
Family size
Study & Academic Factors
Study time
Previous failures
School support
Family support
Paid classes
Lifestyle Factors
Free time
Social activity
Internet access
Health
Absences
📁 Project Structure
student-performance-data-analysis/
│
├── Student_performance.csv
│
├── student_performance_cleaned.csv
│
├── summary_statistics.csv
│
├── EDA_Correlation_Matrix.csv
│
├── 01_average_grade_by_gender.png
├── 02_gender_distribution.png
├── 03_final_grade_distribution.png
├── 04_final_grade_boxplot.png
├── 05_G1_vs_G3.png
├── 06_studytime_vs_grade.png
├── 07_failures_vs_grade.png
├── 08_correlation_heatmap.png
│
├── Student_Performance_Analysis.ipynb
│
└── README.md
📄 Generated Outputs
Data Files
student_performance_cleaned.csv
summary_statistics.csv
EDA_Correlation_Matrix.csv
Visualization Outputs
Average grade by gender
Gender distribution
Final grade distribution
Final grade boxplot
G1 vs G3 relationship
Study time vs grade
Failures vs grade
Correlation heatmap
💡 Key Analytical Questions

The project investigates questions such as:

What is the distribution of final student grades?
How does academic performance vary across gender groups?
What is the relationship between G1 and G3?
How is study time associated with academic performance?
How are previous academic failures related to final grades?
Which numerical variables have notable correlations with academic performance?
What patterns can be identified from student demographic and academic data?
📌 Results & Insights

The analysis provides a structured view of factors associated with student academic performance.

Key areas examined include:

Previous academic performance
Study time
Academic failures
Absences
Student demographics
Family and educational factors
Lifestyle characteristics

The visualizations and correlation analysis help identify patterns that can be investigated further through statistical modeling or predictive analytics.

Note: Correlation and visual patterns do not by themselves establish causation.
