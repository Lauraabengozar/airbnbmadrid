Airbnb Madrid Analysis
📖 Project Overview

This project analyses Airbnb listings across Madrid to uncover patterns in pricing, neighbourhood performance and market distribution.

Using Python for data cleaning and exploratory analysis, and Power BI for data visualisation, the project transforms raw Airbnb data into an interactive dashboard that supports data-driven decision making.

A key feature of the project is the integration of Madrid's Metro and Light Rail network, allowing each Airbnb listing to be analysed based on its proximity to public transport.

🎯 Business Questions
Where is Airbnb supply concentrated across Madrid?
Which neighbourhoods have the highest and lowest prices?
What accommodation types dominate the market?
Does proximity to public transport influence Airbnb prices?
Which neighbourhoods offer the strongest market opportunities?
🧹 Data Preparation

The dataset was cleaned and enriched using Python before being imported into Power BI.

Main preparation steps included:

Removing invalid records and unrealistic values
Handling missing data and encoding issues
Standardising column names
Calculating the distance from each listing to the nearest Metro or Light Rail station
Creating transport accessibility categories for further analysis
📊 Dashboard

The interactive dashboard provides an overview of Madrid's Airbnb market through KPIs, neighbourhood comparisons, room type distribution, pricing analysis and transport accessibility.

Users can explore the data dynamically using interactive filters to compare different areas of the city.

(Insert dashboard screenshot here)

💡 Key Insights
19K Airbnb listings analysed across 134 neighbourhoods.
Embajadores has the highest concentration of listings.
Entire homes account for 71.6% of all listings.
Nearly 90% of listings are within 500 metres of a Metro or Light Rail station.
Canillejas, San Andrés and Hellín have the highest average listing prices.
Aluche, Moscardó and Zofío are among the most affordable neighbourhoods.
The project combines Python (Pandas, Folium) and Power BI to analyse the relationship between neighbourhood characteristics, pricing and transport accessibility.
🛠️ Tools
Python (Pandas, NumPy, Matplotlib, Folium)
Power BI
Git & GitHub
📂 Project Structure
airbnbmadrid/
├── data/
├── notebooks/
├── dashboard/
├── images/
└── README.md


