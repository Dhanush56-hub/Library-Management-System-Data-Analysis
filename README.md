# 📚 Library Management System Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing Library Management System data using Python. The main objective is to understand book borrowing patterns, member activity, popular genres, library branch performance, overdue returns, and fine collection.

The dataset contains information about books, members, borrowing transactions, issue dates, due dates, return dates, and fines.

Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn were used to clean, analyze, and visualize the data. The analysis helps identify meaningful business insights and provide recommendations to improve library services.

## 🎯 Project Objectives

- Load and understand the library management dataset.
- Identify and handle missing values.
- Remove duplicate records.
- Correct inconsistent text values.
- Convert date and numeric columns into appropriate formats.
- Analyze borrowing patterns across different genres and books.
- Identify the most active library branches and membership types.
- Analyze monthly borrowing trends.
- Understand overdue returns and fine collection.
- Create visualizations to present the findings.
- Generate business insights and recommendations.

## 📂 Project Structure

```text
Library-Management-System-Data-Analysis/
│
├── Charts/
│
├── library_management_dataset_5000_records.csv
│
├── cleaned_library_data.csv
│
├── library.ipynb
│
├── Library_Management_System_Report_Matched_Format.docx
│
├── Library_Management_System_Report_Matched_Format.pdf
│
└── README.md
```

## 📊 Dataset Description

- **Dataset Name:** library_management_dataset_5000_records.csv
- **Original Records:** 5,010
- **Duplicate Records Removed:** 10
- **Final Cleaned Records:** 5,000
- **Number of Columns:** 12

### Dataset Columns

| Column Name | Description |
|---|---|
| Transaction_ID | Unique transaction identification number |
| Member_ID | Unique library member ID |
| Book_ID | Unique book identification number |
| Book_Title | Title of the book |
| Author | Name of the book author |
| Genre | Book genre |
| Branch | Library branch |
| Membership_Type | Type of membership |
| Issue_Date | Date the book was issued |
| Due_Date | Book return due date |
| Return_Date | Actual book return date |
| Fine_Amount | Fine amount recorded |

## 🛠️ Tools and Technologies Used

| Tool / Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations and data classification |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Writing and executing Python code |
| Visual Studio Code | Development environment |

## 🧹 Data Cleaning

The following data cleaning operations were performed:

1. Checked missing values using `isnull().sum()`.
2. Filled missing values in Membership_Type and Genre with `Unknown`.
3. Identified and removed 10 duplicate records.
4. Corrected inconsistent branch names.
5. Corrected inconsistent genre names.
6. Converted Issue_Date, Due_Date, and Return_Date into datetime format.
7. Converted Fine_Amount into numeric format.
8. Replaced negative fine values with zero.
9. Filled missing fine values with zero.
10. Created a Borrowing_Duration column using Issue_Date and Return_Date.

The missing Return_Date and Borrowing_Duration values for books that had not yet been returned were retained.

After cleaning, the dataset contained 5,000 records and was exported as `cleaned_library_data.csv`.

## 🔍 Exploratory Data Analysis (EDA)

The following analysis tasks were performed:

1. Total Book Borrowing Analysis
2. Genre-Wise Borrowing Analysis
3. Branch-Wise Borrowing Analysis
4. Monthly Borrowing Analysis
5. Membership Type Analysis
6. Book Return Status Analysis
7. Fine Collection Analysis
8. Top 10 Most Borrowed Books Analysis

## 📈 Data Visualization

Eight visualizations were created using Matplotlib and Seaborn.

1. Genre-Wise Borrowing – Bar Chart
2. Top 10 Most Borrowed Books – Horizontal Bar Chart
3. Branch-Wise Book Circulation – Bar Chart
4. Monthly Borrowing Trend – Line Chart
5. Membership Type Distribution – Pie Chart
6. Book Return Status – Donut Chart
7. Distribution of Overdue Days – Histogram
8. Fine Collection by Branch – Bar Chart

## 💡 Key Business Insights

Based on the analysis, the following insights were identified:

1. **Most Popular Genre:** Self-Help was the most popular genre, with 915 borrowings.

2. **Highest Performing Branch:** Central Library recorded the highest borrowing activity, with 1,623 transactions.

3. **Most Active Membership Type:** Student members recorded the highest activity, with 2,891 transactions.

4. **Most Borrowed Book:** The Silent Patient was the most borrowed book, with 366 borrowings.

5. **Overdue Returns:** A total of 2,312 returned books were overdue.

6. **Total Fine Collection:** The total fine amount recorded was ₹69,660.

7. **Highest Borrowing Month:** August 2024 recorded the highest borrowing activity, with 250 transactions.

## 📌 Business Recommendations

1. **Reduce Late Returns:** Send reminders to members before the book due date.

2. **Add More Popular Books:** Maintain extra copies of frequently borrowed books.

3. **Promote Other Genres:** Encourage readers to explore different book genres.

4. **Improve Library Services:** Improve facilities and services in branches with lower borrowing activity.

5. **Encourage Student Reading:** Organize reading programs and book clubs for students.

6. **Monitor Overdue Books:** Regularly check overdue books and follow up with members.

7. **Improve Book Availability:** Maintain proper stock of books based on member demand.

8. **Encourage Digital Services:** Introduce online book reservations and renewals to make library services easier.

## 🎓 Conclusion

This project provided practical experience in data cleaning, data analysis, exploratory data analysis, and data visualization using Python.

The analysis helped identify popular book genres, frequently borrowed books, active library branches, membership activity, overdue returns, and fine collection.

Overall, the project demonstrates how Python and data analytics can be used to understand library operations, identify useful business insights, and support better decision-making.

---

**Project:** Library Management System Data Analysis  
**Author:** Dhanush K  
**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook  
**Repository:** [GitHub Project Repository](https://github.com/Dhanush56-hub/Library-Management-System-Data-Analysis)
