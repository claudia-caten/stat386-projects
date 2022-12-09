---
layout: post
title:  "The NBA Story"
date:   2022-12-08
author: Claudia Caten
description: A final explaination on what we learned from the NBA dataset
image: /assets/images/NBA.png
---

#Where Have We Been?
Over the past couple of months I have used data from NBA Reference to learn more about the NBA players from the 2021 - 2022 NBA season. In order to do this I had to first learn how to web-scrape the data from the NBA Reference website in order to make the NBA dataset. To read more about this process, you  can check out one of my previous blog <a href="[https://github.com/claudia-caten/web-scraping](https://claudia-caten.github.io/stat386-projects/2022/10/18/Web-Scraping-the-NBA.html)"> posts </a>. This dataset had statistics about any player who played in the season last year. To learn more about the dataset as a whole I first did a little bit of exploratory data analysis. You can read more about this here in my last blog <a href="[[https://github.com/claudia-caten/web-scraping](https://claudia-caten.github.io/stat386-projects/2022/10/18/Web-Scraping-the-NBA.html)](https://claudia-caten.github.io/stat386-projects/2022/11/17/Exploring-the-NBA.html)"> posts </a>. I then wanted to learn more about the teams specifically, so I then grouped the data by Team and took the mean of all of the statistics. When I did this I realized that the outliers were skewing the data significantly. Players who wouldn't play very much were included in the dataset but wouldn't score very much and would thus throw off the averages for the teams. To take care of these outliers I filtered the dataset to only include the players who playerd on average 15 minutes or more. Now the data will tell it's story.

#Field Goal Percentage per Team
Just like any dataset this dataset had many stories to tell. One that I found is illustrated in the graphic below. ![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/NBA_story.png)


This graphic illustrates the relationship between the different NBA teams' average field goals made to its average field goals attempted for the players who played more than 15 minutes on average per game. This graphic gives us a better understanding of the teams' field goal percentage. The Field goal percentage of a team gives us greater understanding of a teams' accuracy. A better field goal percentage does not necessarily mean that the team is better, there are many elements to a good team. Nevertheless, field goal percentage is still a good measure of accuracy. By looking at the data we can see that OKC had an approximately 50% field goal percentage for the players who played more than 15 minutes. 

#The End?
That is the end of the NBA dataset, or is it? There is still much more to be gleaned from this dataset. What other questions do you have about this dataset? What stories does it still have to tell? If you are interested in learning more, leave a comment below of what questions you still have. You can access the code for this dataset <a href="https://github.com/claudia-caten/web-scraping"> HERE </a>. Thanks for following along!


