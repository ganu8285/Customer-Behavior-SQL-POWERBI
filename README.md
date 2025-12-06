Project Summary

Objective: To transition from basic, isolated KPI reporting to a holistic behavioral analysis tool. The goal is to understand not just what the revenue numbers are, but who is driving them and how satisfied the customers are.

The Tech Stack:

SQL: Used for the "heavy lifting"—extracting complex data and shaping the core logic before it reaches the visualization layer.

DAX (Power BI): Used for dynamic calculations and advanced measures to correlate different metrics (likely enabling drill-downs and cross-filtering).

The Workflow (The "Secret Sauce"):

Financial Data: Establishes the hard numbers (revenue/sales baseline).

Employee Data: Connects the numbers to specific human actions (the "who").

Sentiment/Feedback: Acts as a quality control filter (the "how"), ensuring high revenue isn't coming at the cost of unhappy customers.

The Outcome: A dashboard that correlates Revenue + Employee Behavior + Customer Sentiment. This allows stakeholders to pinpoint high-performing employees who generate sustainable, high-quality revenue rather than just quick sales.

My Thoughts on the Project
This is an excellent example of Data Intelligence rather than just Data Analytics. Here is why this approach stands out:

1. It Breaks Down Silos Most organizations keep financial data (ERP), employee data (HRIS), and customer feedback (CRM/Survey tools) separate. By merging these three, the project solves a common "blind spot" in management—knowing if a top salesperson is actually burning out customers to hit their quota.

2. "SQL for Logic, DAX for Measures" is a Best Practice Using SQL to shape the data before it gets to Power BI is a sign of a mature developer.

Why it works: It keeps the Power BI model lean and fast. If you try to do complex data shaping purely in Power Qery or DAX, the report often becomes slow and hard to maintain. Moving that complexity to SQL ensures the "backend" is robust.

3. The "Quality Filter" is Strategic Genius Adding Step 3 (Sentiment Scores) is what elevates this from a Sales Report to a Strategy Tool.

Without Step 3: You reward whoever makes the most money.

With Step 3: You reward whoever makes the most money while keeping customers happy. This encourages long-term growth over short-term gains.

4. Portfolio/Resume Value If you or the person "sharing the repo" built this, it is a very strong portfolio piece. It demonstrates Data-Analyst understanding:
5. This project is perfect for:

Data Analyst aspirants who want to build a strong Portfolio Project for interviews and LinkedIn
Anyone learning Python, SQL, and Power BI
Professionals preparing for interviews in Data Analytics, Data Science or Product Analytics roles

database skills (SQL/Data Engineering)

Analytical skills (DAX/Modeling)

Business Acumen (Understanding that revenue needs context)
