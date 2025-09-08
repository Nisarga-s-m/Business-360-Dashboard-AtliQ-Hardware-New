Business Insights 360 – Power BI Project
Project Overview

AtliQ Hardware has been expanding rapidly in recent years. To stay ahead of competitors and move towards data-driven decision-making, the company decided to implement Power BI dashboards for the first time. The goal of this project was to empower stakeholders across finance, sales, marketing, and supply chain with actionable insights that go beyond intuition or basic spreadsheets.

I carried out this project as part of the Codebasics Power BI course. The project simulates a real-world corporate setup where data teams work closely with business leaders to define objectives, design dashboards, and provide value-driven analytics.


🔗 Course Link

Tech Stack

SQL – Data extraction & queries

Power BI Desktop – Dashboard development

Excel – Data cleaning & validation

DAX & DAX Studio – Measures, calculations, and report optimization

Key Learnings & Power BI Techniques

Asking the right business questions before starting a project

Data modeling using fact and dimension tables

Creating calculated columns, measures, KPIs, and date tables

Handling errors (e.g., preventing divide-by-zero)

Using dynamic titles, bookmarks, and page navigation buttons

Conditional formatting to highlight trends and anomalies

Publishing dashboards to Power BI Service

Setting up auto-refresh via Gateway

Managing workspaces, permissions, and app deployment

Business Glossary

During the project, I also gained exposure to common business and financial terms used in analytics, including:

Gross Price, Net Sales, Net Profit, Gross Margin

Pre-Invoice & Post-Invoice Deductions

COGS (Cost of Goods Sold)

YTD (Year-to-Date) & YTG (Year-to-Go)

Distribution Channels: Retailers, Direct, Distributors

Dataset & Modeling

The dataset was provided in MySQL and imported into Power BI for reporting. It followed a typical data warehouse design with fact and dimension tables.

Dimension Tables:

Customers (75 customers, 27 markets, multiple platforms & channels)

Markets (regions & subzones like APAC, EU, LATAM, etc.)

Products (14 categories across PCs, Accessories, Networking, Storage, etc.)

Fact Tables:

Forecasted monthly sales (customer demand planning)

Actual monthly sales (delivered sales quantity)

Freight cost, Gross price, Manufacturing cost, Pre- and Post-invoice deductions

The project followed the Snowflake schema for data modeling, ensuring optimal performance and scalability.

Business Problem

AtliQ Hardware recently suffered losses after opening stores in the US based purely on surveys, intuition, and Excel-based analysis. Competitors, however, had strong analytics teams that guided their expansion strategies more effectively.

This project highlighted how robust BI dashboards can support:

Smarter decisions on where to expand and invest

Improved customer satisfaction and forecasting

Better alignment between finance, sales, and supply chain

Project Kickoff & Stakeholder Alignment

Before dashboard development, it was crucial to clarify expectations with stakeholders:

What are the main objectives of this project?

How will success be measured?

Who are the end-users and how will they use the dashboard?

What are the hopes and fears around this implementation?

What resources, data, and design preferences need to be considered?

This ensured that the final deliverable addressed both business goals and technical feasibility.

GitHub & Versioning

Used Git LFS (Large File Storage) to manage large Power BI files

Configured file tracking for .pbix files and other large assets

Documented changes clearly for version control

Outcome

The final Power BI report combined insights from sales, finance, marketing, and supply chain, allowing AtliQ Hardware to make better data-driven decisions. By simulating a real corporate use case, this project helped me master Power BI end-to-end workflows—from raw data extraction to interactive dashboard delivery.
