# Module 2 Summative Lab

## Introduction

This is an investigation into the performance of football teams in the German D1 and D2 leagues during 2011. I will be looking at summary performance statistics of teams with a visualisation. I will also be investigating the effect of whether on team performance. I will be using a variety of data sources for this including:

* Database of European football performance since the early 00's as the primary data set
* This will be cross referenced with historic weather data by location using the [DarkSky API](https://darksky.net/dev)
* This information will be uploaded to a Mongo DB for ease of future investigate

During these steps I will demostrate awareness and competence of the PEP8 standard for [Python coding](https://www.python.org/dev/peps/pep-0008/) and Object Oriented programming principles.  

# Goals Scored Analysis 

Looking at the data for team performance by number of goals scored we see that the top 3 teams by goal scoring are:

* Dormund
* Ein Frankfurt
* Bayern Munich

All of these teams score well above the group mean of 80 goals for the season. In terms of the spread of the data, we can see from the histogram that there is a right skew with a high standard deviation and 75% of the teams accounting for 99% of the goals in the population. This shows that there is a high vairance between those teams that do really well in this league and the "average" performing teams. Reasons for why this would be so would make an interesting point for further study.

# Win/Loss/Analysis 

Looking at the data for the number of wins/loses/draws for each teams and the visulation created (see notebook and git repo), we can see the top performing teams in terms of wins/loses/draws are: 

* Dortmund
* Bayern Munich
* Greuther Furth

This ties in with the success we have seen for Dortmund and Bayern Munich in terms of goals scored. Greuther Furth are intersting because in terms of goals scored, they were at position 5. This visualisation highlights the gap in performance between the highest performing (top 3) teams and the rest of the population.

#To do:

Due to time constraints, I've not been able to complete all tasks in the lab. I'll complete the remainder of these tasks over time. The remainder of tasks to be done are:

[ ] Retrieve data from the Darksky API

[ ] Cross reference data and analyse

[ ] Upload findings to a Mongo DB

[ ] Use OOP classes to implement the above functionality
