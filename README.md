## Overview

This project analyzes men’s shirt sales performance across multiple brands using an end-to-end business intelligence workflow powered by Azure SQL Database and Power BI. It delivers deep insights into brand performance, pricing strategy, discount behavior, and profitability to help retail managers make data-driven decisions.

## Tech Stack

Database: Azure SQL Database

ETL / Data Prep: Power Query (Power BI)

Data Modeling: Star Schema with Fact and Dimension tables

Visualization: Power BI Desktop

Storage & Hosting: Azure Cloud

Data Source: Raw sales and product data (brand, category, price, discount, profit, quantity)


## Key Performance Indicators (KPIs)

![Dashboard Preview](https://i.ibb.co/S4Mznff9/menshirt-page-0002.jpg)

Top 5 Brands by Highest Discount – highlights discount-driven sales performers

Top 5 Brands by Highest Variety – tracks assortment richness by SKU count

Top 5 Brands by Highest Sale Price – focuses on premium positioning

Top 5 Brands by Highest Profit % – measures margin efficiency

Bottom 5 Brands by Profit % – flags underperformers

Each KPI is dynamically calculated through DAX measures such as:


## How to Use

Import the .pbix file into Power BI Desktop.

Connect to your Azure SQL Database using valid credentials.

Enable data refresh and customize filters (brand, category, season).

Publish to Power BI Service for team collaboration.

## Future Enhancements

Add predictive modeling for sales forecasting using Azure Machine Learning.

Include region-level sales segmentation and channel-wise analysis.

Automate Azure SQL to Power BI pipeline via Data Factory.
