# student-performance-and-attendance-analysis
# Student Performance and Attendance Analysis

## 1. Project Information

**Project Name:** Student Performance and Attendance Analysis  
**Developed By:** Aman Pal  
**Admission Number:** 2026B01010586  
**Technology Used:** Python  
**Libraries Used:** Pandas, NumPy  
**Dataset Size:** 200 Students  
**Project Type:** Academic Data Analytics Project

---

## 2. Project Overview

The Student Performance and Attendance Analysis project is developed using Python to manage and analyze student academic data.

The project generates a dataset of 200 students containing attendance, assignment marks, internal marks, final marks, and study hours.

It also performs basic data cleaning operations, checks missing values, identifies duplicate records, and saves both raw and cleaned datasets in CSV format.

## 3. Objectives

- To create a dataset of 200 students.
- To store student academic information.
- To check missing values in the dataset.
- To identify duplicate records.
- To clean the dataset.
- To save raw and cleaned data in CSV files.
- To understand basic data analytics using Python.

## 4. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data handling and analysis |
| NumPy | Numerical data generation |
| CSV | Data storage |
| VS Code | Development environment |

## 5. Dataset Description

The project contains 200 student records with the following columns:

| Column Name | Description |
|---|---|
| Student_ID | Unique student identification number |
| Student_Name | Student name |
| Attendance | Attendance percentage |
| Assignment_Marks | Assignment marks |
| Internal_Marks | Internal examination marks |
| Final_Marks | Final examination marks |
| Study_Hours | Daily study hours |

## 6. Software Development Life Cycle (SDLC)

### Phase 1: Planning

The main purpose of this project is to analyze student performance and attendance using Python.

The project requirements were identified, including dataset creation, data cleaning, and CSV file generation.

### Phase 2: Requirement Analysis

**Hardware Requirements:**
- Computer or Laptop
- Minimum 4 GB RAM
- Basic storage space

**Software Requirements:**
- Windows Operating System
- Python 3.x
- VS Code or Jupyter Notebook
- Pandas Library
- NumPy Library

### Phase 3: System Design

The system follows a simple data analytics workflow:

1. Import Python libraries.
2. Generate student dataset.
3. Convert data into a Pandas DataFrame.
4. Save the raw dataset.
5. Check missing values.
6. Identify duplicate records.
7. Remove duplicate records.
8. Save the cleaned dataset.
9. Display final output.

### Phase 4: Development / Implementation

The project is implemented using Python.

**Main functions performed:**

- `np.random.randint()` – Generates random student data.
- `pd.DataFrame()` – Creates the dataset.
- `to_csv()` – Saves data into CSV files.
- `isnull().sum()` – Checks missing values.
- `duplicated().sum()` – Counts duplicate records.
- `drop_duplicates()` – Removes duplicate records.
- `head()` – Displays the first 10 records.

### Phase 5: Testing

The following tests are performed:

| Test Case | Expected Result |
|---|---|
| Dataset creation | 200 records generated |
| Missing value check | No missing values |
| Duplicate check | Duplicate count displayed |
| Data cleaning | Duplicate records removed |
| CSV generation | Raw CSV file created |
| CSV generation | Cleaned CSV file created |

### Phase 6: Deployment

The project can be executed on any computer with Python and the required libraries installed.

The generated CSV files can be opened using Microsoft Excel, Google Sheets, or Python.

### Phase 7: Maintenance

Future improvements can include:

- Student performance graphs.
- Attendance analysis.
- Average marks calculation.
- Grade calculation.
- Performance comparison.
- Identification of students requiring academic support.

## 7. Project Workflow

**Input → Data Generation → DataFrame Creation → Data Cleaning → CSV Storage → Final Output**

## 8. Output Files

The project generates two CSV files:

1. `Raw_Student_Data.csv` – Contains the original generated dataset.
2. `Cleaned_Student_Data.csv` – Contains the cleaned dataset after duplicate removal.

## 9. How to Run the Project

**Step 1:** Install Python 3.x.

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy
```

**Step 3:** Open the project folder in VS Code.

**Step 4:** Run the Python file.

```bash
python student_analysis.py
```

**Step 5:** Check the generated CSV files in the project folder.

## 10. Expected Output

```text
RAW DATASET
Total Records: 200

Missing Values:
Student_ID         0
Student_Name       0
Attendance         0
Assignment_Marks   0
Internal_Marks     0
Final_Marks        0
Study_Hours        0

Duplicate Records:
0

FINAL OUTPUT
Total Students: 200
Raw Dataset Saved Successfully!
Cleaned Dataset Saved Successfully!
Project Completed!
```

*Note: The dataset is randomly generated, and the output above represents the expected result with the given random seed.*

## 11. Limitations

- Student data is randomly generated.
- Real student records are not used.
- Advanced statistical analysis is not included.
- Graphical visualization is not included in the current version.

## 12. Future Scope

The project can be upgraded by adding data visualization, performance prediction, grade classification, attendance reports, and an interactive dashboard.

## 13. Conclusion

The Student Performance and Attendance Analysis project demonstrates the basic use of Python, Pandas, and NumPy for data generation and data cleaning.

It provides practical knowledge of dataset creation, missing value checking, duplicate identification, and CSV file handling.

This project helped develop an understanding of the basic data analytics process.

---

**Project Developed By:** Aman Pal  
**Admission Number:** 2026B01010586  
**Project Title:** Student Performance and Attendance Analysis
