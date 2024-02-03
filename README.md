# Online Book Management App

## ETL Process and Data Analytics with SQL and Power BI

## Overview

I recently developed an Online Book Management App that seamlessly integrates data from various sources, undergoes Extract, Transform, Load (ETL) processes, and utilizes Power BI for advanced data analytics and visualization. This project is a testament to the power of ETL and data analytics in driving meaningful insights for decision-makers.

## ETL Process

### 1. Data Import
- The journey begins with the extraction of raw data from diverse sources, including book sales, author details, publisher information, and book categories.

### 2. Data Cleaning and Transformation
- Leveraging SQL Server Management Studio (SSMS), I meticulously cleaned and transformed the raw data into a Star Schema, a robust structure for data warehousing.
- Fact Table (`tb_books`): Capturing book-specific details such as title, author_id, category_id, price, publisher_id, publish_year, publish_month, and publish_year_month.
- Dimension Tables (`tb_author`, `tb_publisher`, `tb_category`): Housing detailed information about authors, publishers, and book categories.

## Data Analytics and Visualization

### 1. Star Schema
- The data is organized in a Star Schema, ensuring efficiency in querying and enabling quick access to insightful information.

### 2. Power BI Integration
- Transformed data seamlessly imported into Power BI, a powerful tool for interactive and visually appealing reports and dashboards.

### 3. Key Insights
- **Profit by Publisher:** A detailed view of profits generated by each publisher, aiding in strategic business decisions and partnerships.
- **Profit by Author:** Insights into individual author contributions to profits, helping in recognizing and rewarding top-performing authors.
- **Profit by Category:** Understanding profitability across different book categories, facilitating targeted marketing and inventory management.

### 4. Dynamic Visualizations
- Implemented bar charts, column charts, and pie charts to represent trends and distributions.
- Utilized interactive filters to empower users to dynamically explore data based on categories, authors, and publishers.

## Conclusion

This Online Book Management App showcases the seamless integration of ETL processes and data analytics with Power BI. By providing clear insights into profits by publisher, author, and category, the application empowers stakeholders with actionable intelligence, making it a valuable asset in the realm of online book management.

Explore the live demo and visualizations on GitHub: [GitHub Repository Link]

\#DataAnalytics #PowerBI #ETL #OnlineBookManagement #DataVisualization
