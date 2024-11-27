# Pipeline-County-Health-Rankings  

This repository outlines the data pipeline for permitting data from the University of Wisconsin's County Health Rankings.

All data is stored in a SQLite database called CountyHealthRankings that is located in the "Outputs" folder. 
A guide to this database called "DB_CountyHealthRankings_Metadata.xlsx" is located in the "Outputs" folder and should be updated whenever a new data series is added or updated.

Data is formatted for years 2019 through 2024. In 2024 some metrics changes and "Ranking" ceased, instead a range for a smaller number of factors was provided. 
Here, we have decided to take the 50th percentile value of that range and continue to compare rankings over time for consistency.
