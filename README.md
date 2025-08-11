# TradePulse

### Project Description
This project is a Kenya trade data analytics tool designed to help analysts, researchers, and policymakers explore trends in Kenya’s imports and exports.
It collects trade statistics from the World Integrated Trade Solution (WITS) API, stores them in a local database, and allows filtering, visualization, and export of insights.
The system includes a Python-based data pipeline for fetching, cleaning, and analyzing trade data, with outputs displayed in interactive dashboards and CSV exports.
It aims to provide clear insights into Kenya’s trade performance by country, region, and commodity over time.

### Problem Statement
Kenya’s trade statistics are often available but scattered across multiple platforms and formats, making it challenging for analysts to retrieve, clean, and analyze them efficiently. 
Manual downloads and spreadsheet work are time-consuming and error-prone. 
This tool centralizes the workflow — from data extraction via API, through cleaning and transformation, to visualization — in one Python-based project. 
It reduces repetitive manual work and increases accuracy, making trade trend analysis faster and more accessible.

### Planned Features
•	Automated data retrieval from WITS API (imports, exports, trade balance)
•	Data cleaning and transformation (handling missing values, standardizing country names)
•	Storing cleaned data in a SQL database for querying
•	Basic exploratory data analysis (growth rates, top trade partners, key commodities)
•	Interactive visualizations of trade trends using Plotly or Matplotlib
•	Exportable CSV reports for offline use
•	Option to filter by year, country/region, or commodity group

### Technologies
•	Python core (functions, loops, conditionals, error handling)
•	Requests (to call WITS API)
•	Pandas/Numpy (for data cleaning, aggregation, and transformation)
•	Matplotlib/Seaborn/Plotly (for visualizations)
•	SQLite / MySQL (for storing cleaned trade data)
•	SQL queries (for trend extraction and filtering)
•	Jupyter Notebook (for development and documentation)

### Data Sources
•	API → World Integrated Trade Solution (WITS) API
•	Local files → CSV exports from the API for offline processing

### Success Criteria
The project is considered complete when:
•	Data is successfully retrieved from WITS API for at least 5 years of trade history.
•	The data is cleaned and stored in a local SQL database.
•	Users can query trade trends by year, country, and commodity.
•	At least three different trade insights are visualized.
•	Create an interactive dashboard with Streamlit or Tableau
•	Reports are exportable in CSV format.

### Stretch Goals
•	Integrate other data sources
•	Automate monthly/quarterly data refresh
•	Add machine learning models for trade forecasting
•	Publish visualizations on a public website for stakeholder access

