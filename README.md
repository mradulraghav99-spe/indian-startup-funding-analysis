# Indian Startup Funding Analysis

## Project Overview

This project analyzes startup funding data in India to identify funding
patterns, trends, industries, cities, investment types, startups, and
investors.

The analysis was performed using Python and Pandas, followed by
visualizations to understand important patterns in the dataset.

## Objectives

- Analyze startup funding trends over the years
- Identify industries receiving the highest funding
- Analyze startup funding by city
- Understand different investment types
- Identify highly funded startups
- Analyze frequently occurring investors
- Generate meaningful business insights from the data

## Dataset

The dataset contains information about Indian startup funding, including:

- Startup Name
- Industry Vertical
- SubVertical
- City Location
- Investors Name
- Investment Type
- Amount in USD
- Date

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI *(dashboard will be added later)*

## Data Cleaning

The following data-cleaning steps were performed:

- Removed the Remarks column because of a high percentage of missing values
- Standardized column names
- Converted the date column into datetime format
- Extracted year and month from the date
- Cleaned funding amounts and converted them to numeric values
- Handled missing categorical values
- Standardized inconsistent city names
- Standardized inconsistent investor names
- Removed duplicate records where applicable

## Business Questions

1. How has startup funding changed over the years?
2. How many funding deals occurred each year?
3. Which industries received the most startup funding?
4. Which cities received the most startup funding?
5. What are the most common investment types?
6. Which startups received the highest total funding?
7. Which investors participated in the most deals?

## Key Insights

- Startup funding varied considerably across the years.
- Funding activity was concentrated in a smaller number of industries.
- Major startup hubs accounted for a significant portion of recorded funding.
- Some investment types occurred more frequently than others.
- Funding was unevenly distributed among startups.
- Some investors appeared in multiple funding deals.

## Future Work

A Power BI dashboard will be added to this project to provide an
interactive visual representation of the analysis.

## Project Structure

```text
indian-startup-funding-analysis/
│
├── data/
├── notebook/
├── README.md
└── dashboard/        # To be added later
