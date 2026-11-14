# Healthcare-Data-Cleaning-task1
Healthcare data cleaning, profiling, validation and quality assessment using Microsoft Excel Power Query.
Patients and Departments Data Cleaning Report
1. Project Overview
This project involved preparing healthcare datasets for revenue cycle and medical billing performance analysis using Microsoft Excel Power Query.
The objective was to assess data quality ,clean the Patients and Departments datasets. Check duplicate records, missing identifiers, inconsistent categories, invalid values, and formatting issues. Standardize categorical fields where necessary and prepare reliable datasets for subsequent analytical work
2. Dataset Overview
Dataset	Records	Columns
Patients	650	4
Departments	8	3
Total	658	7

3. Data Cleaning Methodology
The following Power Query techniques were used:
•	Column Quality profiling to identify missing values and errors.
•	Column Distribution to assess distinct and unique values.
•	Data-type transformations to enforce appropriate column formats.
•	Trim to remove leading and trailing whitespace.
•	Clean to remove non-printable characters.
•	Categorical validation to inspect consistency.
4. Patients Dataset — Findings
The Patients dataset contained 650 records with four attributes: PatientID, AgeGroup, Gender and InsuranceType.
Validation results:
•	650 distinct and unique PatientIDs.
•	No missing values detected.
•	No Power Query errors detected.
•	PatientID converted to Whole Number (Int64).
•	Other columns maintained as Text.
•	Five age groups, three gender categories and four insurance categories identified.
•	Trim and Clean transformations applied.
Outcome: The dataset passed the documented quality checks and was prepared as Patients_Clean.
5. Departments Dataset — Findings
The Departments dataset contained eight records with three attributes: DepartmentID, DepartmentName and DepartmentCategory.
Validation results:
•	Eight unique DepartmentIDs.
•	Eight distinct department names.
•	No missing values detected.
•	No Power Query errors detected.
•	DepartmentID converted to Whole Number (Int64).
•	DepartmentName and DepartmentCategory maintained as Text.
•	Five department categories identified.
•	Trim and Clean transformations applied.
Outcome: The dataset passed the documented quality checks and was prepared for loading as Departments_Clean.
6. Data Quality Conclusions
Both datasets demonstrated strong initial data quality, with complete fields and unique primary identifiers.
No duplicate identifiers, missing values or transformation errors were detected in the reviewed Power Query outputs.
The cleaning process standardised data types and text formatting while retaining the original record counts.
7. What Is Done
1.	Preserve the original datasets separately from the cleaned queries.
2.	Retain Power Query Applied Steps for reproducibility.
3.	Validate patient and department relationships with subsequent datasets.
4.	Check referential integrity before building the analytical data model.
5.	Maintain a cleaning log and screenshots as portfolio evidence.
8. Final Deliverables
•	Patients_Clean
•	Departments_Clean
•	Data Cleaning Log
•	Data Quality Assessment Report
•	Power Query transformation evidence
Project status: Patients and Departments cleaning completed; ready for subsequent data modelling and analysis.

