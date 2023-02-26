# Communicate data findings: Ford GoBike System Data
## by Mame Diarra NIANE


## Dataset

Bike-sharing systems have become increasingly popular in recent years as a sustainable and affordable means of transportation in urban areas. The Ford GoBike bike-sharing system in San Francisco's Bay Area is one such example, providing a convenient and efficient way to travel around the city. In this project, we will perform exploratory data analysis (EDA) on the usage data of the Ford GoBike system for February 2019.

The dataset contains information about the duration of the trip ,the user(biker) information and information about the station

The dataset came in a csv file with over 180000 entries and 16 columns.

In the **Wrangling step** ,there was 8265 missing data in the birth year ang gender observation that i decided to removes instead of compensating these missing values.

There was many features that have the wrong datatype that needed to be fixed before the analysis. the birth year was replace with the age that is is easily readable.I have also transformed the duration that was in seconds to minutes for convinience


## Summary of Findings

Our goal is to gain insights into the usage patterns and characteristics of the bike-sharing system's users.

Through EDA, we have analyzed the trip durations,usage habits and user types. We've explored whether there are any gender differences in bike usage patterns and investigate whether bike usage varies by day of the week or time of day. We have also compare the usage patterns of customers and subscribers to better understand the user base of the system. Finally, we have draw conclusions from our findings and suggest possible ways to improve the bike-sharing system to better meet the needs of its users.

The EDA  shows that:
Customers tend to have longer trips compared to subscriberss.
Female users, on average, ride slightly longer than male users. 
Thursdays have the highest usage frequency, with peak hours at 8:00 AM and 5:00 PM, likely due to work and school schedules. Female users tend to avoid biking between midnight and 5:00 AM, potentially for safety reasons.
Subscribers are more prevalent than customers among both male and female users. 
Lastly, bike rides tend to be longer on weekends than on weekdays.


## Key Insights for Presentation

For the presentation i focus on the influence of the users characteristics and the usage pattern that can also be used to improve the user experience.
The presentation focused on this question to respond:
1. What is the general characteristics of the bike-Sharing system usage? 
2. How long are the trip on average ? And do they wary by user ,type or gender ? 
3. Is there any time use patterns?
