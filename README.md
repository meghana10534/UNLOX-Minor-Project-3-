# UNLOX-Minor-Project-3-
# BingePlay Streaming Analytics

A SQL-based data analytics project focused on analyzing streaming platform data to extract meaningful insights related to user behavior, subscriptions, content performance, viewing patterns, engagement, and potential churn.

## Project Overview

**BingePlay Streaming Analytics** analyzes data from a simulated streaming platform using **MySQL**. The project examines relationships between users, subscription plans, watch sessions, shows, and ratings to answer business-oriented analytical questions.

The analysis demonstrates how SQL can be used to transform raw relational data into actionable insights for streaming platforms.

## Key Objectives

* Analyze active subscriptions and revenue.
* Track monthly user signup trends.
* Understand device-wise viewing behavior.
* Analyze content ratings and distribution.
* Compare original and acquired content performance.
* Identify binge-watching patterns.
* Detect inactive users who signed up but never watched content.
* Analyze Premium and Family plan usage.
* Track subscription upgrade behavior.
* Identify cliffhanger comeback patterns.
* Measure consecutive-week user engagement.
* Detect potential churn signals.

## Key Analyses

| No. | Analysis                                  |
| --- | ----------------------------------------- |
| 1   | Active subscription and revenue analysis  |
| 2   | Monthly user signup trends                |
| 3   | Device-wise viewing analytics             |
| 4   | Rating distribution analysis              |
| 5   | Originals vs. acquired content comparison |
| 6   | Binge day detection                       |
| 7   | Users who signed up but never watched     |
| 8   | Premium and Family plan usage analysis    |
| 9   | User upgrade behavior analysis            |
| 10  | Cliffhanger comeback analysis             |
| 11  | Consecutive week engagement tracking      |
| 12  | Churn signal detection                    |

## Technologies Used

* **MySQL**
* **MySQL Workbench**
* **SQL**
* **Relational Databases**
* **Data Analytics**

## SQL Concepts Demonstrated

This project applies several important SQL concepts, including:

* `SELECT`, `WHERE`, and `ORDER BY`
* `GROUP BY` and `HAVING`
* Aggregate Functions
* `INNER JOIN` and `LEFT JOIN`
* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Date and Time Functions
* Conditional Expressions
* Data Filtering and Analysis

## Database Components

The project works with streaming platform data related to:

* **Users** – User profiles and signup information
* **Subscriptions** – Subscription plans and payment details
* **Shows** – Content information and categories
* **Watch Sessions** – Viewing activity and engagement
* **Ratings** – User ratings and content feedback

## Project Structure

```text id="vz7mzz"
BingePlay-Streaming-Analytics/
│
├── dataset/
│   └── bingeplay_dataset.sql
│
├── queries/
│   ├── q1.sql
│   ├── q2.sql
│   ├── q3.sql
│   ├── ...
│   └── q12.sql
│
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open **MySQL Workbench**.
3. Create the required database.
4. Import and execute the dataset SQL file.
5. Run the SQL queries included in the project.
6. Review the generated results and insights.

## Learning Outcomes

Through this project, I gained practical experience in:

* Writing analytical SQL queries
* Working with relational databases
* Joining and analyzing multiple tables
* Using aggregate functions for business analysis
* Applying subqueries and CTEs
* Using window functions for advanced analysis
* Identifying user engagement patterns
* Analyzing subscription behavior
* Detecting potential churn indicators
* Extracting meaningful business insights from data

## Future Enhancements

* Develop an interactive analytics dashboard.
* Integrate the database with **Power BI** or **Tableau**.
* Add data visualization using **Python**.
* Build machine learning models for churn prediction.
* Implement recommendation and content performance analysis.
* Extend the project with real-time streaming analytics.

## Conclusion

This project demonstrates the practical application of **SQL and MySQL for data analytics** in a streaming platform environment. By analyzing user activity, subscriptions, watch sessions, content, and ratings, the project provides insights into engagement, revenue, content performance, and potential churn.

---

### Author

**B.Tech – Computer Science and Engineering (Data Science)**
**Minor Project 3 – BingePlay Streaming Analytics**

### License

This project is intended for **academic and learning purposes**.
