# SQL Course Projects

This repository contains projects and exercises completed as part of the **Analyze Data with SQL** Skill Path on Codecademy.  
It documents my progress in learning SQL for data analysis, database management, and query optimization.  

## 📂 Repository Structure
- **Project 1 – Create a Table**: practice with table creation, data insertion, updating, altering schema, and deletion.  
- **Project 2 – New York Restaurants**: data exploration and analysis using filtering, sorting, and conditional logic.
- **Project 3 – RPA Fraud Detection**: detecting suspicious transactions using filtering, pattern matching, and anomaly checks.
- **Project 4 – RPA Customer Segmentation**: generating marketing segments based on user attributes, campaigns, and tests. 
- **Upcoming Projects**: more case studies and exercises will be added as I advance through the course.  

## 🚀 Projects

### Project 1: Create a Table
In this project, I created a simple **friends** table and practiced basic SQL operations such as creating tables, inserting data, updating records, altering tables, and deleting rows.  

**Skills Practiced:**
- `CREATE TABLE`, `INSERT INTO`, `SELECT`  
- `UPDATE`, `ALTER TABLE`, `DELETE`

### Project 2: New York Restaurants
In this project, I analyzed a dataset of New York City restaurants stored in a table called **nomnom**.  
The goal was to practice writing SQL queries to explore the data and answer specific business questions.  

**Skills Practiced:**
- `SELECT DISTINCT`  
- Filtering with `WHERE` (including `AND`, `OR`, `LIKE`)  
- Handling missing values (`IS NULL`)  
- Sorting and limiting results (`ORDER BY ... LIMIT`)  
- Using `CASE` for conditional logic in queries

### Project 3: RPA Fraud Detection

In this project, I analyzed a dataset of credit card transactions (`transaction_data`) to help the finance department identify potentially fraudulent activity.  
The main goal was to practice filtering, pattern matching, and working with real-world fraud detection scenarios.  

**Skills Practiced:**
- Data exploration (`SELECT * ... LIMIT`)  
- Conditional filtering with `WHERE`  
- Pattern matching with `LIKE` and wildcards  
- Filtering by domain (email checks with `LIKE '%@temp_email.com'`)  
- Identifying anomalies in data (ZIP codes, IP ranges)

### Project 4: RPA Customer Segmentation

In this project, I worked with a dataset of users (`users` table) to generate marketing segments for the company.  
Segments are subsets of users that meet different conditions and can be used for targeted campaigns.  


**Skills Practiced:**
- Date filtering with `BETWEEN` and comparison operators  
- Working with `created_at` timestamps  
- Using `LIKE` for pattern matching  
- Segmenting data with multiple conditions  
- Table modification (`ALTER TABLE`) and updating records (`UPDATE ... SET`)  
- Calculating derived values (age at signup) using `strftime()`  
