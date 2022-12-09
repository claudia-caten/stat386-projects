---
layout: post
title:  "The NBA Story"
date:   2022-12-08
author: Claudia Caten
description: A final explaination on what we learned from the NBA dataset
image: /assets/images/basketball.jpeg
---

Over the past couple of months I have used data from NBA Reference to learn more about the NBA players from the 2021 - 2022 NBA season. In order to do this I had to first learn how to web-scrape the data from the NBA Reference website in order to make the NBA dataset. This dataset had statistics about any player who played in the season last year. I then wanted to learn more about the teams specifically, so I then grouped the data by Team and took the mean of all of the statistics. When I did this I realized that the outliers were skewing the data significantly. Players who wouldn't play very much were included in the dataset but wouldn't score very much and would thus throw off the averages for the teams. To take care of these outliers I filtered the dataset to only include the players who playerd on average 15 minutes or more. Now the  


