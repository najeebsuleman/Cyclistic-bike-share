# Cyclistic Bike-Share: Converting Casual Riders to Members

## Background

This project is for the Google Data Analytics Certification capstone project.

I am wearing the hat of a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. Cyclistic is a bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering **reclining bikes, hand tricycles, and cargo bikes**, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day. Customers who purchase single-ride or full-day passes are referred to as *casual riders*. Customers who purchase annual memberships are *Cyclistic members*.

The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve the recommendations, so they must be backed up with compelling data insights and professional data visualizations.

## Project Approach

This project will be completed by using the 6 Data Analytics stages:

* **Ask:** Identify the business task and determine the key stakeholders.
* **Prepare:** Collect the data, identify how it’s organized, determine the credibility of the data.
* **Process:** Select the tool for data cleaning, check for errors and document the cleaning process.
* **Analyze:** Organize and format the data, aggregate the data so that it’s useful, perform calculations and identify trends and relationships.
* **Share:** Use design thinking principles and data-driven storytelling approach, present the findings with effective visualization. Ensure the analysis has answered the business task.
* **Act:** Share the final conclusion and the recommendations.

## Ask

* **Business Task:** Recommend marketing strategies aimed at converting casual riders into annual members by better understanding how annual members and casual riders use Cyclistic bikes differently.

* **Stakeholders:**
    * Lily Moreno: The director of marketing and my manager.
    * Cyclistic executive team: A detail-oriented executive team who will decide whether to approve the recommended marketing program.
    * Cyclistic marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Cyclistic’s marketing strategy.

## Prepare 

For this project, I will use the public data of Cyclistic’s historical trip data to analyze and identify trends. The data has been made available by Motivate International Inc. under the license.

I downloaded the ZIP files containing the csv files from the above link but while uploading the files in kaggle (as I am using kaggle notebook), it gave me a warning that the dataset is already available in kaggle. So I will be using the dataset cyclictic-bike-share dataset from kaggle. The dataset has 13 csv files from April 2020 to April 2021. For the purpose of my analysis I will use the csv files from April 2020 to March 2021. The source csv files are in Kaggle so I can rely on its integrity.

I am using Microsoft Excel to get a glimpse of the data. There is one csv file for each month and has information about the bike ride which contain details of the ride id, rideable type, start and end time, start and end station, latitude and longitude of the start and end stations.


