---
layout: post
title:  "Exploring the NBA"
date:   2022-11-17
author: Claudia Caten
description: What can you do with data about NBA players? What can you learn about NBA players?
image: /assets/images/basketball.jpeg
---

In my last post I talked about how to web-scrape data about NBA players from the internet. Now that we have that data what do we do with it? The first step is to explore the data. Creating simple graphics can help us to learn more about the dataset at hand. Follow along to see what I learned about NBA players from the 2021-2022 season. 

# The Older the Better?
The first thing that I was curious about was the impact of Age on NBA players. Age often means experience but to what extent? In the graph below we can see that there seems to be a relatively small relationship between the age of a player and the average amount of points scored. That being said there is an interesting spread about the data. The data is significanly less concentrated about the lower point amounts. This just shows that overall, most of the players don't score lots of points. The less concentrated data towards the higher points could be representative of star players.
![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/graph2.png)


# Playing Time
The next thing that I wanted to analyze is the relationship between Minutes Played and Average Points Scored. If everything goes at it should there should be a positive relationship between minutes and points. We see in the graph below that this is the case. It makes sense that as a player gets more points they will play more minutes. 
![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/graph1.png)


# Position 
Which position has the best shooters? Field Goal Percentage helps us to analyze this question. I created a boxplot to better assess this question. I compared the Field Goal Percentage of different positions. As you can see in the graph below the Centers are more consistently better shooters. Secondly, you can see that the Power-Forwards are the next best shooters. 
![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/graph3.png)


# Correlation Matrix
An important part about exploring data is understanding the correlation between different variables. I created a correlation matrix between age, points, minutes played, field goal percentage, and games played. We can see that all of these values have a positive correlation coefficient which means that as any one of these variables increases the other one does as well.  
![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/graph4.png)


# Take Note of Age
Finally I wanted to do some exploratory data analysis on the Utah Jazz. Since this is my team of interest I wanted to explore more information about thier team. At first I just analyzed the relationship between the age of the players and their Field Goal Percentage. This data doesn't actually show us that much because the size of the team isn't big enough for us to learn too much about the team. It could be more beneficial to explore other statistics about the Utah Jazz. That being said, by looking at the graph it appears that the jazz has both old and young strong shooters as there are high bars at 22 and also at 31. This is probably reflective of some players specifically. This data could also be skewed by players who only played a few minutes who either go a really good or really bad field goal percentage.
![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/graph5.png)


# Looking Forward
Exploring the data is just the beginning. Now that we have found out more about our data we can use it to tell a story. In addition, we can use our data to make an interence or predictions about our data. I am still learning more about data analyzation and have ways to grow. I think if I am going to keep using this data I want to gain more data about players such as height and weight to predict what physical attributes make a great NBA player. If you want to see the code that I used for this project you can find it <a href="https://github.com/claudia-caten/web-scraping"> HERE </a>.
