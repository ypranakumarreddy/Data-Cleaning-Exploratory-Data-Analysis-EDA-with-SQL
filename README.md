# 📊 Exploratory Data Analysis (EDA) with SQL
This project uses SQL to perform in-depth exploratory data analysis on a dataset of company layoffs. The goal was to uncover trends, patterns, and key insights about layoffs across companies, industries, countries, and time periods.

# 🧠 Objective
Explore and analyze layoff data to understand the scale and impact across different dimensions.
Identify trends over time, by company, industry, and country.
Practice advanced SQL techniques for real-world data analysis.
# 📊 Dataset
Source: Layoff dataset
Period: March 2020 – March 2023
Features: Company, Industry, Country, Date, Total Laid Off, Percentage Laid Off, Funds Raised, Stage
# 🧪 Workflow
Started with basic queries to find max layoffs, companies with 100% layoffs, and largest single-day layoffs.
Explored layoffs by company, industry, and country using GROUP BY and aggregation.
Analyzed time trends: calculated monthly and yearly layoffs, and created rolling totals using window functions.
Used CTEs and ranking functions to identify top companies with the most layoffs per year.
Interpreted results to understand the impact of COVID-19 and economic shifts on layoffs.
# 📈 Results
Identified major companies (e.g., Google, Meta, Amazon) with the largest layoffs.
Found that the U.S. had the highest number of layoffs, with significant spikes in 2022 and early 2023.
Revealed industry trends: consumer and retail sectors were hit hardest.
Built advanced SQL queries using CTEs, window functions, and ranking for deep insights.
# 📁 Files Included
Exploratory_Data_Analysis.sql — All SQL scripts for EDA.
# 🚀 Future Improvements
Visualize results in BI tools (e.g., Tableau, Power BI).
Integrate with company size data for richer percentage analysis.
Automate EDA reporting with stored procedures.
