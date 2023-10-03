# Google Data Analytics Capstone Project : Cyclistic

## Introduction
This project is the final task for the Google Data Analytics course on Coursera. Throughout this project, I apply some of the skills I learnt on the course, as well as other skills I learnt along the way.

I use Python to process and clean the data and Tableau to visualise the data. Please note that although the course teaches RStudio over Python, I decided I want to work on my Python skills in this project. I elected not to use SQL this time, but hope to do so in future projects.

## The Scenario
In this fictional case study, I act as a junior data analyst in the marketing analytics team at a bike-sharing company called Cyclistic, based in Chicago. The director of the team believes that the future of the company's success lies within maximising the number of customers with annual memberships. It is my team's job to analyse how 'members' (those customers with annual memberships) and 'casuals' (one-time or daily pass users) use Cyclistic's bikes differently. From these insights, the team must design a new marketing strategy which will convert casual customers into annual members.

Cyclistic's services function as normal bike-sharing services do - users unlock a bike at one station, then lock the bike at another station at any time. Cyclistic also offers different kinds of bikes, including classic bikes, electric bikes and bikes designed for disabled customers.

## The Task
Three questions are posed to the marketing analytics team:
1. How do annual and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

The director of marketing has assigned me the first question: **How do annual and casual riders use Cyclistic bikes differently?**


## The Data
Google has provided .csv files for both monthly and quarterly data from 2014 up to the present. This is an immense amount of data, so I decided to focus in on the monthly data for 2021 only. The data is collected internally by Cyclistic for the purposes of the marketing analytics team.

## Preparation and Cleaning
First, I open a few of these .csv files in Excel to get a general feel for the data. I notice that the data is generally quite clean.

The details of the data preparation and cleaning process are given in the attached Jupyter notebook. Please take a look!

## Analysis

![Type Of Bike Dashboard](https://github.com/dtbesson/Cyclistic-Google-Data-Project/assets/92056999/2d76e6f3-d98c-4ee8-a03a-e368304d8473)

We can see that despite the recent emergence of electric bikes, classic bikes still remain the favourite. Casual users are slightly more likely to use electric bikes compared to members. However, this difference is small and no strong conclusions can be drawn.

![Trips Per Dashboard](https://github.com/dtbesson/Cyclistic-Google-Data-Project/assets/92056999/3eeb8a64-2b85-4c6b-9c62-d77e64341bcb)

There is a big spike in usage amongst casual users on the weekends, particularly on Saturdays. On the other hand, members usage is consistent throughout the week, even seeing a slight decrease on the weekends. This suggests that casual users and members use Cyclistic bikes for different purposes. Members are more likely to use them for commutes to work, whereas casual users are more likely to use them for leisure on the weekends.

It comes as no surprise that the overall number of trips is much higher in the summer and lower in the winter. However, the curve for casual users has higher peaks and lower troughs than the curve for members. This may be because members have paid for an annual membership, and want to get their money's worth, regardless of the weather. Casual users have greater incentive to hire a bike when the weather is good.

There is a dramatic spike in usage around 5PM daily. This coincides with the time of day that people start to come home from work. Both members and casual members use Cyclistic bikes more around this time of day. However, the spike is slightly larger for members. There is another spike in usage around 8AM, but only for members. Again, this supports the notion that members use the bikes more for commuting purposes. It is also important to note that casual users use them for commuting purposes as well, but much more in the evening than the morning.

![Trip Duration Per Dashboard](https://github.com/dtbesson/Cyclistic-Google-Data-Project/assets/92056999/1594445a-3b0a-4cb2-99ed-a540e4df6cf8)

Looking at all three graphs together, we see that the median trip duration is greater for casual users on the whole. Once again, this highlights how casual users use Cyclistic bikes more leisurely.

The median trip duration is quite consistent throughout the week for members, with a slight increase on the weekends. This increase on the weekends is slightly exaggerated for casual users.

For both parties, trip duration decreases during the winter months. Users likely cycle faster in order to get out of the cold. Interestingly, trip duration is at its highest during the spring months, particularly for casual users. So although the number of trips is highest during the summer, the duration of trips is highest during the spring. It is difficult to explain exactly why this is the case. It is possible that in the summer, people want to get out on a bike and enjoy the weather. However, the perfect temperature for cycling may be in the spring, and thus people stay on the bike for longer.

The median trip duration for members remains quite stable throughout the day. Trips starting at 5PM (hometime) are marginally longer, but this is likely due to increased traffic around this time. The median trip duration for casual users is very short when started at early hours (around 6AM), but much longer when starting in the afternoon (around 2PM). This suggests that casual users start their most leisurely rides in the afternoon.

## Conclusion
Based on our analysis, here would be my recommendations to the marketing team:
- Marketing campaigns should run in the spring and summer months, when casual users take the most trips and for the longest durations.
- Adapt campaigns to highlight the benefits of cycling to work, to encourage casual users to use Cyclistic bikes on a more regular basis.
- Casual users have longer trip durations, so including some sort of reward for longer trips into memberships may entice them.
- Casual users tend to use Cyclistic bikes more on the weekends and during the summer months. Instead of focusing on annual memberships, pushing weekend passes or seasonal memberships may be a more profitable venture.






