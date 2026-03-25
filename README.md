This repository contains practical exercises and mini-projects
focused on Data Analytics and Data Engineering fundamentals.

Topics covered:
- Python (Pandas)
- SQL
- Data Analysis
- API data ingestion
- Business metrics analysis

### Projects 1 through 5

In these initial projects, the focus was on consolidating the fundamentals of data analysis using Python and Pandas. Essential techniques such as JSON file and tabular dataset manipulation, data cleaning and transformation, feature creation, and aggregation operations were explored.

Furthermore, basic data visualization concepts with Matplotlib were introduced, allowing the construction of simple graphs for interpretation and communication of insights.

These projects establish the necessary foundation for more advanced analyses, emphasizing organization, clarity, and best practices in data handling.

## Project 6 Cryptocurrency Analysis with Real API
Pipeline for consuming and analyzing crypto market data in real time. Integrates the CoinGecko public API via requests, transforms the JSON response into a pandas DataFrame with key metrics (market cap, volume, 24-hour variation), and answers questions such as: which coins lead in capitalization, which have the highest trading volume, and which registered the highest appreciation on the day. Concludes with visualizations in matplotlib (horizontal and vertical bar charts). Project focused on ingestion via REST API, selective column cleaning, and basic exploratory analysis.

## Projects 7 and 8 — SQL + Python with Superstore Dataset

Project 7

SQL + Python pipeline on the Superstore dataset (Kaggle). Loads data via Kaggle Hub, persists in an SQLite database with SQLite3, and answers four business questions via pure SQL queries: best selling product, highest-revenue category, monthly revenue, and average order value. The results are brought into pandas DataFrames and visualized with matplotlib. First practical contact with the Python ↔ SQL combination in analysis pipelines.

Project 8

Direct evolution of Project 7: the same Superstore dataset is normalized into three relational tables (orders, customers, products) and persisted in SQLite. The focus is on queries with INNER JOIN and LEFT JOIN between multiple tables to answer more complex analytical questions: revenue by category, profit by segment, best-selling products by quantity, revenue by region, and region × category cross-tabulation. Introduces basic relational modeling and the use of multiple joins within a Python pipeline.

### Project 9 — Customer Analytics: Segmentation and Revenue Concentration - Analytics

Pipeline for analyzing customer behavior on the Superstore dataset. The data is normalized into three tables in SQLite (customers, orders, products), and from there, the work is entirely analytical: creating SQL views with metrics per customer (total revenue, number of orders, average ticket, profit), segmentation into three levels: Gold, Silver, and Bronze, based on revenue quantiles, and Pareto  concentration analysis (25% of Gold customers account for ~65% of revenue). The project goes beyond code: it includes a layer of actionable insights with real business recommendations, such as a loyalty program for Gold customers, margin review for Silver, and an upsell strategy in Office Supplies. Visualizations with scatter plots (revenue × profit), stacked bars (category mix per segment), and analysis of database structure vs. margin. This project marks the transition from a technical pipeline to decision-driven analytics.