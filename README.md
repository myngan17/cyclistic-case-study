CYCLISTIC TRIP DATA

=======================================



Source: Motivate International Inc. (Divvy Bike Share)

Data time for this analysis: 01/2025 - 12/2025

Original dataset can be found at: https://divvy-tripdata.s3.amazonaws.com/index.html

Data license can be found at: https://divvybikes.com/data-license-agreement

Raw data size: \~1.1 GB (5.3 million of rows) 

Processed data size: \~900 MB (5.174 million of rows)



COLUMN DESCRIPTIONS

\-------------------

1. ride\_id - Unique id for each ride
2. rideable\_type - Types of bike (classic and electric bike)
3. started\_at - Trip start day and time
4. ended\_at - Trip end day and time
5. start\_station\_name - Trip start station
6. start\_station\_id - Trip start station id
7. end\_station\_name - Trip end station
8. end\_station\_id - Trip end station id
9. start\_lat - Starting latitude of the trip
10. start\_lng - Starting longitude of the trip
11. end\_lat - Ending latitude of the trip
12. end\_lng - Ending longitude of the trip
13. member\_casual - Types of customers (Casual rider - purchasing single ride or full day passes \& Member - purchasing annual memberships)



NOTES

\-----

\- No personally identifiable information (PII) is included in this dataset.



PIPELINE

=======================================

Google Colab (Data Cleaning + Transforming) => Google Big Query (Data Source) => Connected Sheet (Google Sheet - Analyzing \& Visualization)

CANVA SLIDE LINK: https://canva.link/yvlw5sdetgopx2u 
