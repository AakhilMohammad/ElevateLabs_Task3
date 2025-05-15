# ElevateLabs_Task3
# Task 3: SQL for Data Analysis - Process Documentation

## Role: Data Analyst Intern
This task involved analyzing an e-commerce dataset using SQL. Below is a step-by-step summary of the process followed to complete the task.

---

## Dataset Used
- **File Name:** `clean_data.csv`
- **Description:** Contains customer behavioral data including time on app, time on website, membership length, and yearly amount spent.

## Tools Used
- Database:MySQL (Workbench)
- Language:SQL
- Editor:MySQL Workbench / CLI
- Platform:Local System

 Step-by-Step Process

### 1. Data Preparation
- Cleaned the `data.csv` file to ensure it's comma-separated and structured properly.
- Saved the final version as `clean_data.csv`.

### 2. Table Creation
Created a new table `clean_data` in MySQL to match the CSV structure.

```sql
CREATE TABLE clean_data (
    Email VARCHAR(255),
    Address TEXT,
    Avatar VARCHAR(100),
    Time_on_App FLOAT,
    Time_on_Website FLOAT,
    Length_of_Membership FLOAT,
    Yearly_Amount_Spent FLOAT
);
