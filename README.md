# SQL Course Projects

This repository contains projects and exercises completed as part of the **Analyze Data with SQL** Skill Path on Codecademy.  
It documents my progress in learning SQL for data analysis, database management, and query optimization.  

## 📂 Repository Structure
- **Project 1 – Create a Table**: practice with table creation, data insertion, updating, altering schema, and deletion.  
- **Project 2 – New York Restaurants**: data exploration and analysis using filtering, sorting, and conditional logic.
- **Project 3 – RPA Fraud Detection**: detecting suspicious transactions using filtering, pattern matching, and anomaly checks.
- **Project 4 – RPA Customer Segmentation**: generating marketing segments based on user attributes, campaigns, and tests.
- **Project 5 – Davie’s Burgers Subway Ad**: analyzing restaurant orders to uncover fun and creative insights for advertising.
- **Project 6 – Trends in Startups**: exploring startup data with aggregation, grouping, filtering, and ordering.
- **Project 7 – The Metropolitan Museum of Art**: analyzing artwork data to find counts, categories, origins, and material patterns.
- **Project 8 – Hacker News Trends**: analyzing Hacker News posts to uncover user behavior, content sources, and posting patterns.
- **Project 9 – Cryptocurrency Exchange**: analyzing digital currency transactions to understand trading activity and trends.
- **Project 10 – Lyft Trip Data**: joining multiple tables to analyze trips, riders, and autonomous cars.
- **Project 11 – Welp**: joining places with reviews, building 2020 review logs, and spotting below-average “difficult” reviewers.
- **Project 12 - Multiple Tables with Reddit**: combining users, posts, and subreddits data to analyze popularity and engagement.
- **Project 13 – VR Startup Company**: staffing analysis, project selection stats, developer headcount needs, and personality-compatibility checks.
- **Project 14 – Codeflix Churn Rate**: analyzing subscription cancellations to measure churn across marketing segments. 
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

### Project 5: Davie’s Burgers Subway Ad

In this project, I explored the **orders** data for Davie’s Burgers to uncover fun, ad-worthy insights for a subway campaign.  
The focus was on finding memorable facts (best-selling items, peak hours, quirky combos) that could inspire a catchy tagline.

**Skills Practiced:**
- Aggregations and ranking (`COUNT`, `SUM`, `AVG`, `GROUP BY`, `ORDER BY`, `LIMIT`)
- Time bucketing and date functions (hour/day-of-week extraction)
- Text/pattern work for item names and modifiers
- Basic segmentation (by hour, weekday, item category)
- (Optional) pairs/combos analysis and simple window functions

### Project 6: Trends in Startups

In this project, I explored a dataset of startups to calculate key statistics and practice SQL aggregations.  
The table contained information such as company name, category, location, number of employees, valuation, amount raised, and founding year.

**Skills Practiced:**
- Aggregate functions (`COUNT`, `SUM`, `MAX`, `MIN`, `AVG`, `ROUND`)  
- Grouping and filtering with `GROUP BY` and `HAVING`  
- Sorting results with `ORDER BY`  
- Applying conditions within aggregate queries

### Project 7: The Metropolitan Museum of Art

In this project, I explored artwork data from the Metropolitan Museum of Art.  
The goal was to practice filtering, grouping, and aggregating data to uncover insights about the collection.

**Skills Practiced:**
- Aggregate functions (`COUNT`, `MIN`)  
- String matching with `LIKE`  
- Grouping and filtering (`GROUP BY`, `HAVING`)  
- Ordering and limiting results (`ORDER BY`, `LIMIT`)  
- Conditional grouping using `CASE`

### Project 8: Hacker News Trends

In this project, I analyzed a dataset of Hacker News stories (`hacker_news` table) to uncover insights into user activity, posting behavior, and content trends.  

**Skills Practiced:**
- Aggregate functions with `GROUP BY` and `HAVING`  
- Conditional logic with `CASE`  
- Filtering and string matching (`LIKE`)  
- Working with dates and times using `strftime()`  
- Sorting, limiting results, and rounding (`ROUND`)  

### Project 9: Cryptocurrency Exchange

In this project, I analyzed transaction data from **Fiddy Cent**, a cryptocurrency exchange.  
The dataset (`transactions` table) included both money-in and money-out flows across currencies like Bitcoin, Bitcoin Cash, Ethereum, and Litecoin.   

**Skills Practiced:**
- Aggregate functions (`SUM`, `COUNT`, `MAX`, `AVG`, `ROUND`)  
- Filtering data with `WHERE`  
- Grouping and summarizing with `GROUP BY`  
- Using aliases (`AS`) for clearer output  
### Project 10: Lyft Trip Data

In this project, I worked with three related tables — `trips`, `riders`, and `cars` — to practice joining data and answering business questions for Lyft.  

**Skills Practiced:**
- Table joins (`LEFT JOIN`, `INNER JOIN`, `CROSS JOIN`)  
- Combining datasets with `UNION`  
- Filtering with `WHERE` and comparisons  
- Aggregate functions (`AVG`, `COUNT`)  
- Sorting and limiting results (`ORDER BY ... LIMIT`)

### Project 11: Welp

In this project, I analyzed a local-reviews dataset by combining **places** with **reviews** to answer practical product questions.  
I explored price filters, built a log of **2020 reviews** using a CTE, searched special instructions/notes for fun marketing snippets, and identified “difficult reviewers” with below-average ratings.

**Skills Practiced:**
- Table joins (`LEFT JOIN`, `INNER JOIN`)  
- Common Table Expressions (`WITH`)  
- Date handling with `strftime('%Y', ...)`  
- Aggregations and grouping (`COUNT`, `AVG`, `GROUP BY`, `HAVING`)  
- Filtering with subqueries/CTEs (e.g., **below global average** ratings)  
- Text search and pattern matching (`LIKE '%...%'`)  
- Column aliases and basic readability improvements (`AS`)  

### Project 12: Multiple Tables with Reddit

In this project, I analyzed fictional Reddit data using three tables: users, posts, and subreddits.
The tasks covered everything from exploring the schema to combining data across tables with joins, stacking tables, and writing more advanced queries with `WITH`.

**Skills Practiced:**

- Exploring relational databases and identifying primary/foreign keys
- Aggregation (`COUNT`, `AVG`, `MAX`)
- `LEFT JOIN` and `INNER JOIN` for combining tables
- Stacking tables with `UNION`
- Common Table Expressions (`WITH`) for temporary queries
- Filtering and ordering results for insights (e.g., most popular posts, highest scoring subreddit posts, average scores by subreddit)

### Project 13: VR Startup Company

In this project, I analyzed employee and project data for **Codecademy Virtual Reality (CVR), Inc.** to ensure projects can be staffed efficiently.  
Each project requires a Project Manager, Team Lead, Designer, DBA, and **at least two Developers**. I explored who hasn’t chosen a project, which projects lack staff, which projects attract the most employees, and whether we have enough developers.  
As a bonus, I used Myers–Briggs personality rules to surface the most common personality, see which projects they prefer, and compute—per employee—the number of incompatible co-workers.

**Skills Practiced:**
- Table exploration and schema reasoning  
- Joins for staffing insights (`INNER JOIN`, `LEFT JOIN`)  
- Anti-joins with subqueries (`NOT IN`)  
- Aggregations and grouping (`COUNT`, `GROUP BY`, `HAVING`, `ORDER BY`)  
- Headcount math with scalar subqueries (e.g., developer slots per project)  
- Conditional logic with `CASE` and subqueries to apply compatibility rules

### Project 14: Codeflix Churn Rate

In this project, I analyzed subscription data for **Codeflix**, a streaming startup that wanted to measure early churn rates across different marketing segments.  
The dataset (`subscriptions` table) contained the following fields:
- `id` – subscription ID  
- `subscription_start` – start date of the subscription  
- `subscription_end` – end date of the subscription (nullable if still active)  
- `segment` – acquisition channel (two groups: 87 and 30)  

The goal was to calculate monthly churn rates during the first three months of 2017, compare them across the two segments, and determine which group had lower churn.

**Skills Practiced:**
- Data exploration (`SELECT ... LIMIT`, `DISTINCT`)  
- Date range analysis with `MIN` and `MAX`  
- Building a temporary months table  
- `CROSS JOIN` to combine subscriptions with each month  
- Using `CASE WHEN` to flag active and canceled subscriptions by segment  
- Aggregating with `SUM` to calculate totals per month  
- Computing churn rates (`canceled ÷ active`)  
- Comparing churn trends across segments over time
