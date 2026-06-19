## Data-Analysis-Challenge:
This repository contains a comprehensive data cleaning project focused on transforming raw, inconsistent course enrollment data into a structured and analyzable format. Developed as a key milestone in my Data Analysis certification journey.

## 🛠️ Challenges & Solutions
During the data cleaning process, I addressed several data quality issues to ensure accurate analysis:

* **Handling Mixed Data Types:** The 'Enrollment_Date' column contained inconsistent formats. I utilized `pandas` date parsing with the `mixed` argument to standardize all entries into a uniform datetime format.
* **Feature Engineering:** The 'Course_Details' column was too dense, containing both the course name and its difficulty level. I split this into two separate, cleaner columns ('Course_Name' and 'Level').
* **Dealing with Missing Values:** The 'Rating' column had missing values. Instead of removing those rows, I imputed them with the column mean to preserve the dataset's size and integrity.
* **Data Deduplication:** I performed a thorough check for duplicate rows and removed them to prevent bias in the analysis results.
* **Text Standardization:** I normalized the 'Course_Type' column by converting all text to lowercase, which resolved inconsistencies caused by varied casing (e.g., 'Live Bootcamp' vs 'lIVE bOOTCAMP').

## 🛠️ Tools & Libraries
* **Python**
* **Pandas** (Data manipulation and cleaning)
* **Jupyter Notebook**

* ## 📝 How to use
1. Clone this repository.
2. Open the `Data_Analysis_Challenge.ipynb` file in your Jupyter environment.
