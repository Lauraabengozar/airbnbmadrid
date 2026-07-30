# airbnbmadrid
📖 Project Overview

This project analyses Airbnb listings across Madrid to uncover patterns in pricing, neighbourhood performance, accommodation types and public transport accessibility.

The project follows the complete data analysis workflow:

📥 Data collection
🧹 Data cleaning
🔍 Exploratory Data Analysis (EDA)
📊 Interactive Power BI dashboard
💡 Business insights & recommendations

The aim is to demonstrate practical data analytics skills by transforming raw data into meaningful business insights.

🎯 Business Questions
This analysis answers questions such as:
Where is Airbnb supply concentrated?
Which neighbourhoods have the highest prices?
What types of accommodation dominate the market?
Which neighbourhoods represent the largest market opportunities?
How does the Madrid Airbnb market vary by location?

🧹 Data Cleaning

The dataset was cleaned using Python before importing into Power BI.

Cleaning steps included:

Removed invalid prices
Removed extreme minimum-night values
Checked missing values
Standardised column names
Corrected encoding issues
Calculated distance to the nearest Metro or Light Rail station
Created transport accessibility categories

🚇 Transport Accessibility Analysis

One of the project's key features was integrating Madrid's Metro and Light Rail network into the Airbnb dataset.

Using geographic coordinates, each listing was matched to its nearest transport station and classified into accessibility groups:

🟢 Very Close
🔵 Close
🟡 Medium
🔴 Far

This enabled an analysis of whether better transport access is reflected in Airbnb pricing.


