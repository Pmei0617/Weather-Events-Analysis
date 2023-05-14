# Weather-Events-Analysis

In this project, I explored a storm weather data and a US state data extracted from AWS S3 buckets and then, executing advanced SQL queries to gain storm insights.

### Project Steps
1. I first created a database in Snowflake called **WEATHER**. Then I created a worksheet selecting the **WEATHER** database using the **PUBLIC** schema
2. Two CSV files, **"severe-weather"** and **"state_sizing"** are stored in AWS S3 bucket in a file called **"severe_weather"**. I created two tables within the **WEATHER** database and within the **PUBLIC** schema called **"severe_weather"** and **"state_sizes"**. Then I extracted data from the two CSV files in S3 bucket and loaded them into their corresponding tables using the COPY command. 
3. Performed advanced SQL queries such as CTES, window functions, date functions, subqueries, joins and CASE statements to gain insights from the storm data
