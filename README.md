# Cyclistic-Case-Study

## Introduction

In this case study, you work for a fictional company, Cyclistic, along with some key team members. In order to answer the business questions, follow the steps of the data analysis process: **Ask, Prepare, Process, Analyze, Share, and Act**.


### Scenario

You are a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

## ASK

**Business Task**: Design marketing strategies to convert casual riders into annual members. 
**Data Analysis Question**: How do annual members and casual riders use Cyclistic bikes differently?

## PREPARE

The data used are the previous 12 months (May 2023 to April 2024) trip data of Cyclistic stored in this [link](https://divvy-tripdata.s3.amazonaws.com/index.html). The data was extracted on the 13th day of May 2024. The data came from 5,824 bicycles that are geo-tracked and locked into a network of 692 stations across Chicago. The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement).

***Note:  Data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t beable to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.***

Each dataset contains monthly trip data and contains the following fields:
1. ride_id – the unique key for every trip
2. rideable_type – the type of bike used
3. started_at – the date and time the use of bike started
4. ended_at - the date and time the use of bike ended
5. start_station_name – the station where the use of bike has started 
6. start_station_id – the id for the station where the use of bike has started 
7. end_station_name – the station where the use of bike has ended 
8. end_station_id - the id for the station where the use of bike has ended
9. start_lat – the latitude of the station where the use of bike started
10. start_lng – the longitude of the station where the use of bike started
11. end_lat - the latitude of the station where the use of bike ended
12. end_lng - the longitude of the station where the use of bike ended.
13. member_casual – identifies whether the user is a member or a casual rider


