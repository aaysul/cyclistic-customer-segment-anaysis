# [Cyclistic Bike-Share Customer Segment Analysis](https://github.com/aaysul/cyclistic-customer-segment-anaysis)

This repository contains the analysis report on the customer usage of Cyclistic bikes. Cyclistic is a fictional bike-share company in Chicago. The report provides details on the step by step process to identify usage behaviour of Cyclistic's customers. The project has been completed in R language using RStudio and shared as a pdf report. 

## Scenario:
Cyclistic is a Chicago based bike-share company. It has two customer segments,
1. Casual Riders
2. Annual Members 

Lily Moreno, the Director of Marketing at Cyclistic believes that the future of the company relies on increasing the number of Annual Members and thus desires analysis of the usage behaviour of both customer segments to gain insights so that marketing campaigns can be designed to convert casual riders into annual members.

## Analysis Process
The process followed in this analytics project involves the following steps,
1. Ask
2. Prepare
3. Process
4. Analyze
5. Share
6. Act

### 1. Ask
Asking the right questions which will result in laying out the track for the proper solution to the Cyclistic's business problem. Following questions are the most relevant,
* How do annual members and casual riders use Cyclistic bikes differently?
* Why would casual riders buy Cyclistic annual membership?
* How can Cyclistic use digital media to influence casual riders to become annual members?

### 2. Prepare
The dataset available for this project is in different sections from the year 2013. For the project to be successful only relevant data is to be analyzed. It was decided to analyze data from the past 12 months. This data was made available on monthly basis in CSV format for each month. Before analysis the data had to be merged. Consistency in the names of columns for the provided datasets was must before merging. 

### 3. Processing
After ensuring consistency the data was merged as a first step in processing step. The total data enteries sum upto around 5.9M rows. After merging the unnecessary information was removed such as columns which were not useful for the analysis. New columns were also created from timestamps to seperate hours of the day, day of the week, weeks and months so that the behaviuor in these timelines could be assessed.

### 4. Analyze
Once the process part was complete it was time for analysis. Usage of the Cyclistic bikes by both segments were analyzed based on hour of the day, day of the week, weekly and monthly usage trends. Relevant charts were prepared to provide the insights into the usage behaviour for casual riders and annual members in these timelines.

### 5. Share 
The analysis has been carried out using R programming language in RStudio. The report has been prepare in R markdown format. Click [code](https://github.com/aaysul/cyclistic-customer-segment-anaysis/blob/main/Cyclistic_Analysis.Rmd) to view the R markdown. Click [report](https://github.com/aaysul/cyclistic-customer-segment-anaysis/blob/main/Cyclistic_Analysis.pdf) to view the final report in pdf format.

### 6. Act
The final part is to act on the provided insights based on the suggestions of the analytics team. The suggestions were forwarded to the marketing team at the end of the report.


