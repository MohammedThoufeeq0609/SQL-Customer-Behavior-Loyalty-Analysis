# SQL Customer Behavior & Loyalty Program Analysis

## Project Overview

This project is a detailed **Customer Behavior Case Study** conducted using **SQL Server**. The primary objective was to analyze the transactional data of an online delivery platform to uncover key insights into customer engagement, purchasing habits, and the specific impact of the **"Gold Membership" loyalty program**.

The final analysis provides data-driven answers to crucial business questions, helping the client make an informed decision on expanding their loyalty program and delivering a more personalized customer experience.

## Key Analytical Objectives

The analysis focused on answering strategic business questions through complex SQL queries:

1.  **Spending and Ordering:** Determine the total amount spent and the frequency of visits for each customer.
2.  **Top Products:** Identify the most popular and highest-selling menu items.
3.  **Loyalty Program Impact:** Quantify the difference in spending and ordering frequency **before and after** customers joined the Gold Membership program.
4.  **First Order Analysis:** Find the first product purchased by a customer after they became a Gold Member, a critical metric for marketing segmentation.
5.  **Ranking:** Use advanced window functions to rank customer transactions based on order date.

## Technical Implementation

* **Database:** MS-SQL Server (or your specified RDBMS).
* **Language:** Advanced SQL (DQL).
* **Key Methodologies:**
    * **Data Modeling (Implicit):** Queries rely on relationships between five core tables: `Sales`, `Product`, `Users`, `User_name`, and `Golduser_Signup`.
    * **Advanced Joins:** Utilized `INNER JOIN`, `LEFT JOIN`, and self-joins for multi-table data aggregation.
    * **Window Functions:** Employed functions like `RANK()` and `ROW_NUMBER()` to identify top customers and rank transactions.
    * **Time-Series Analysis:** Used date comparisons (`<`, `>=`) to isolate pre- and post-membership spending.

## Core Business Insights

The SQL analysis confirmed the business value of the loyalty program:

* **Gold Member ROI:** Gold members demonstrably order **more frequently and spend more** after signing up, validating the program's effectiveness in increasing Customer Lifetime Value (CLV).
* **Customer Segmentation:** Identifying the specific products purchased just before and after joining the program creates an opportunity for highly **targeted marketing** to non-members.
