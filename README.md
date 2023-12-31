# New York CitiBike Rides Analysis

![images (2)](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/b77a737e-90d8-4814-959f-37e9e50ba7d2)

## Overview

This repository contains an analysis of New York City's Citi Bike rides based on data from August 2022 to July 2023. The analysis explores various aspects of Citi Bike usage, including ride duration, ridership by user type, bike type preferences, and more.

## Contents

- [Data](#data)
- [Analysis](#analysis)
- [Tableau Story](#tableau-story)
- [Usage Trends](#usage-trends)

## Data

The data used for this analysis was collected from the Citi Bike program and includes detailed information on ride duration, user types (members and casual riders), bike types (classic, electric, and docked), and monthly ridership. You can download the data [here](https://citibikenyc.com/system-data).

## Analysis

The analysis covers the following key aspects:

### Start and End Station Clusters

To visualize the distribution of start and end stations, I've created map clusters for both. These clusters provide insights into the most popular locations for starting and ending Citi Bike rides.

![Map_Start_Station](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/dedbcb74-d024-4fe5-b4f0-0130a530efa0)

![Map_End_Station](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/6e09ee63-f0e2-4f04-ae42-44986d767240)

The map reveals specific areas within the city that serve as hotspots for Citi Bike ridership, especially when users initiate and terminate their bike trips. These are characterized by dense clusters of bike stations and high user activity, often located near transit hubs, tourist attractions, and densely populated neighborhoods.

### Top and Bottom Stations

Let's also explore the top and bottom stations based on various metrics like ridership, ride duration, and user types. This will help us understand the most and least active stations in the Citi Bike network.

![Dashboard 1](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/0988cfaa-b66a-43f0-8018-950d958fe2e7)

![Dashboard 2](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/3f0500aa-bad8-479d-ad72-08f68095f43e)

By analyzing the data, we can identify the top and bottom 10 stations based on start and end usage. The busiest start and end stations in the Citibike program are Grove St PATH, while the least busy stations are listed in the bottom ten.

- **Seasonal Trends:** An examination of the impact of seasonality on Citi Bike ridership and the reasons behind usage fluctuations throughout the year.

  One of the standout observations from our analysis is the pronounced seasonality in Citi Bike program usage, with the period from May to October consistently marking the highest ridership levels.

- **Count Ride Analysis:** An exploration of the total number of rides for the analyzed period.

![Dashboard 3](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/7bea6c3b-8efa-4aab-9401-f438a4ab9201)

  **The total ride count for the period analyzed was: 977,641.**

  **Decline in Late 2022:**
  From August to December 2022, there is a consistent decline in ridership. The total ridership drops from 114,840 in August to 48,377 in December, representing a substantial decrease of approximately 58% over these five months.

  **Recovery and Growth in Early 2023:**
  The decline continues into January and February 2023, with ridership hitting its lowest point at 51,069 in February. However, in March, there is a notable uptick in ridership, and it continues to grow. From March to July 2023, ridership increases significantly by approximately 107%.

  **Peak Season in Summer:**
  The summer months of June and July 2023 mark the highest ridership, with 96,662 and 106,216 rides, respectively. This could be due to favorable weather conditions, increased tourism, and outdoor activities, driving more people to use Citi Bikes.

- **Percentage Grown Analysis:** An exploration of how members and casual riders differ in terms of rides during the analyzed period.

  **Member Ridership:**
  In August 2022, member ridership accounted for 7.32% of the total riders, which gradually declined to 3.75% by December 2022. In January 2023, there was a slight recovery, with member ridership at 4.45%. This trend continued, with member ridership gradually increasing, reaching 7.49% in July 2023.

  **Casual Ridership:**
  Casual ridership in August 2022 was 4.43% of the total rides, but it steadily decreased to 1.20% by December 2022. In 2023, casual ridership started at 1.26% in January and increased to 3.38% by July.

- **Peak Hour Analysis:** An overview of the peak hours for Citi Bike ridership and the factors contributing to these trends.

  **Highest Ridership at 6 pm:**
  The data shows that 6 pm is the peak hour for Citi Bike ridership. During this hour, the program experiences the highest number of rides. The key factor contributing to this phenomenon is the end of the workday; 6 pm typically marks the end of the traditional workday for many people. Commuters, especially those who use Citi Bikes for their daily commute, tend to head home during this time, creating a surge in ridership.

- **Ride Duration & Distance Analysis:** An examination of the ride durations and distances for members and casual riders, with insights into the reasons behind observed patterns.

![Dashboard 4](https://github.com/afadilla13/NY-Citibike-Challenge/assets/128363337/cf62e23b-6031-4876-935e-279b91ba690d)

  **Citibike Trip Analysis:**
  The situation where casual riders take longer trips in terms of time but members cover greater distances can be explained by the differences in the nature of their rides and how they use the Citi Bike program. Casual riders may take more relaxed, meandering routes, and they may pause to take photos or enjoy the scenery, all of which can extend their ride time. Members are more likely to take direct routes and may be more time-conscious, aiming to complete their journeys as quickly as possible, resulting in shorter ride times.

- **Bike Type Preferences & Likely To Be Repaired The Most:** A discussion of the usage patterns of classic, electric, and docked bikes, with insights into the reasons for these preferences and the type of bike that is most likely to be repaired.

  **Availability and Accessibility:**
  Classic bikes are often the most widely available type of bike in bike-sharing programs. They are accessible to a broader range of users and are usually more plentiful at bike stations, which encourages their usage. Electric bikes, while increasingly popular, may not be as readily available in all areas, which can limit their usage. Additionally, electric bikes often have a higher per-minute cost, which may deter some users. Docked bikes might be less available in comparison to dockless bikes (such as classic and electric bikes). Users may need to locate and return them to specific docking stations, which can be less convenient, particularly in areas with limited station coverage.

  **Most likely to be repaired:**
  Even though classic bikes are more common and widely used, electric bikes are likely to be repaired more frequently. Classic bikes are typically sturdy and only require standard maintenance, while electric bikes may require more specialized maintenance due to their electrical components, including batteries and motors. Electric bikes are likely to be repaired when electrical components or specialized parts need attention, especially because they often have a higher cost and are a preferred choice for riders covering longer distances.

## Tableau Story

You can access the interactive Tableau story for this analysis [here](https://public.tableau.com/app/profile/akbar.fadillah/viz/CitiBike-Tableau_16961332911440/Story1?publish=yes).

## Usage Trends

The analysis reveals significant trends in Citi Bike usage, including the influence of seasonality, user behavior, and the impact of various factors on ridership. Understanding these trends is essential for optimizing the Citi Bike program and catering to the diverse needs of riders.

