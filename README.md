# 📚 Library Book Borrowing Analysis using SQL & Power BI

This project involves data exploration using SQL and visualization with Power BI to uncover patterns and insights from a library transaction dataset. It focuses on understanding user behavior (students vs faculty), popular genres, borrowing trends, reading durations, and seasonal patterns.

---

## 📂 Dataset Source

The dataset used for this project was sourced from Kaggle:  
🔗 [Library Transaction Dataset – Kaggle](https://www.kaggle.com/datasets/ziya07/library-transaction-dataset)

It contains records of borrowing activity in a library, suitable for both SQL-based analysis and business intelligence dashboards.

---

## 🗂️ Dataset Overview

The dataset (`mytable`) includes the following key fields:

- `user_id`: Unique ID of the borrower
- `user_role`: Role of the user (e.g., Student or Faculty)
- `book_category`: Genre/category of the borrowed book
- `borrow_date`: Date when the book was borrowed
- `return_date`: Date when the book was returned

---

## 🔍 SQL Explorations & Insights

### 1. 👤 Top 10 Unique Book Borrowers  
Identified the most active library users based on the number of books borrowed.

---

### 2. 🧑‍🎓 Borrowing Comparison: Students vs Faculty  
Compared the borrowing frequency of students and faculty to analyze usage behavior.

---

### 3. 📖 Most Read Genres  
Discovered which book categories are most preferred by readers (e.g., ART being the most read).

---

### 4. 📅 Borrowing Trends Over Months  
Analyzed monthly borrowing trends to observe patterns during exam periods and holidays.

---

### 5. ⏳ Average Reading Time by Book Category  
Calculated average duration from borrow to return for each book genre to gauge reading habits.

---

### 6. 🧑‍🏫 Reading Time: Students vs Faculty  
Compared average reading duration by user role to understand which group holds books longer.

---

### 7. 📈 Borrowing Trends Over Years  
Visualized year-wise borrowing data to track whether library usage is increasing or declining.

---

### 8. 📘 Book Preferences by Role  
Mapped out book category preferences separately for students and faculty.

---

### 9. 📆 Seasonal Borrowing Patterns  
Identified peak months of borrowing activity, correlating with exams and breaks.

---
---

## 📊 Power BI Dashboard

A comprehensive dashboard was created in **Power BI** to visually represent key insights:

### Included Visualizations:
- 📅 **Monthly Borrowing Trends** (Line/Area chart)
- 🧑‍🏫 **User Role Borrowing Breakdown** (Pie/Donut chart)
- 📘 **Top Book Categories** (Column chart)
- 👤 **Top 10 Borrowers** (Bar chart)
- 📆 **Borrowing Heatmap by Month** (Matrix or Heatmap visuals)
- ⏳ **Average Reading Time by Role & Category** (Combo or clustered visuals)

> The dashboard makes it easy for stakeholders to quickly understand library activity trends and user preferences.

---

## 🧰 Tools Used

- **MySQL** for querying and data analysis
- **Power BI** for interactive data visualization
- IDE: **MySQL Workbench**

---

## 📌 Author

**Achuth Akilesh**  
Product Designer & Data Analyst  
🌐 [Portfolio Website](https://madebyachuth.framer.website/)

---
