# Predictive Analysis of Uk Small Businesses and Residential Fibre Using Time Series

## Executive Summary

The Uk government has set targets for fibre broadband to be available to 85% of the Uk by 2025 and nationwide 2030 (Clark, 2023). To check whether or not the government will meet this target, I will apply a time series model to the following data set provided from Ofcom (Ofcom, 2024). This outcome of this project is to determine whether or not Uk Governments target is realistic. The results could affect not only affect economic performance (Sanyika and Roxburgh, 2011) but also voter confidence in meeting targets.
To ensure the success of the project I will follow a proven model (Yu, 2021), which will help with ensuring the accuracy of the data. Furthermore, so that I make sure to select the best trend which not only looks good but is conservative alongside the historical data. 

## Data Infrastructure & Tools
As the original file is in .CSV format, transformation was carried out in Excel. This made it easy to validate and transform the data. Being able to compare the results within EXCEL using graphs helps contribute towards the model. Next it was uploaded into Power BI for visualisation. This is because can Powerbase allows easy ingestion and can provide interactive graphs for visualisation.
The data was sourced from OFCOM (Wikipedia, 2019) which is a government approved regulatory. As a result, the data will have a higher accuracy and data integrity (Jones, 2024). Furthermore, as the data is open to the public this means it adheres to the latest GDPR regulations (Government of UK, 2018). 
As the model is using data during the Covid-19 period, this creates a challenge in providing an accurate prediction due to seasonal patterns which were not present pre-pandemic. This is why I’ve chosen to only forecast for 2 years.

## Data Engineering
As I followed a standard Extract Transform and Load (AWS, 2022) model, there are a number of processes I have to follow to ensure the adhere to the guidelines set. 

![Screenshots: ETL Diagram](Screenshots/FS_14.png)

### Heading 3
