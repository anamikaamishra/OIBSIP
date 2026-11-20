Task 3 – Data Cleaning | Oasis Infobyte Internship

Project Overview
This project focuses on cleaning and preparing the Titanic dataset using Python, Pandas, and NumPy. The objective is to identify missing values, remove duplicates, standardize data, detect outliers, correct data types, and create a clean dataset ready for analysis.

Internship Details
- **Organization:** Oasis Infobyte
- **Track:** Data Science
- **Task:** Task 3 – Cleaning Data
- **Intern Name:** Anamika Mishra

Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Visual Studio Code

Dataset Information
The Titanic dataset contains passenger information, including:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

Original Dataset: 891 rows and 12 columns.

Data Cleaning Steps

1. Data Quality Report
- Checked missing values in each column.
- Checked duplicate rows.
- Inspected data types.
- Checked minimum and maximum values of Age and Fare.
- Checked negative values.

2. Missing Value Handling
- Age: Filled missing values using median.
- Cabin: Removed because approximately 77.10% of its values were missing.
- Embarked: Filled missing values using mode.
- Other columns did not require missing value treatment.

3. Duplicate Removal
- Identified duplicate rows.
- Duplicate rows found: 0.
- No rows were removed because no duplicates were present.

4. Data Standardization
- Standardized Sex values using title case.
- Standardized Embarked values using uppercase.
- Removed extra spaces from Name and Ticket columns.

5. Outlier Detection
Used the IQR (Interquartile Range) method.

- Age outliers detected: 66.
- Fare outliers detected: 116.
- Decision: Retained outliers because they may represent valid passenger information.

6. Data Type Correction
- Converted PassengerId from integer to string.
- Age and Fare retained as float.
- Survived, Pclass, SibSp, and Parch retained as integers.
- Text columns retained as strings.

Final Output
The cleaned dataset was saved as:

`Titanic_Cleaned.csv`

Final Dataset Shape: 891 rows × 11 columns.

All remaining columns have zero missing values.

Project Files
- `Task_3_Data_Cleaning.ipynb` – Jupyter Notebook containing the cleaning process.
- `Titanic-Dataset.csv` – Original dataset.
- `Titanic_Cleaned.csv` – Cleaned dataset.
- `README.md` – Project documentation.

Conclusion
Successfully performed data cleaning on the Titanic dataset by handling missing values, checking duplicates, standardizing text, detecting outliers, and correcting data types. The final dataset is clean and ready for further data analysis.

Author
Name: Anamika Mishra  
Organization: Oasis Infobyte  
Internship Track: Data Science  
Project: Task 3 – Data Cleaning

