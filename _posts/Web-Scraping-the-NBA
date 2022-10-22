---
layout: post
title:  "Web Scraping the NBA"
date:   2022-10-18
author: Claudia Caten
description: Learn with me how to scrape data from the web to prepare for data analysis
image: /assets/images/basketball-data.jpeg
---

Web Scraping is an essential step in data analysis. In order to analyze data we need to first be able to collect that data. Walk through with me as I learned how to scrape data from the 2021-2022 NBA basketball season. I have always loved sports and as a numbers girl I have always specfically been interested in sports stats. This past year I have become much more interested in the NBA and specifically the Utah Jazz. I chose this dataset to analyze so that I can learn more about the factors that make an NBA player great. I plan to use this dataset to identify and predict which players will preform the best in the incoming 2022-2023 NBA season. 

# To Scrape or To not Scrape
All data isn't free data. Before you can just scrape data on the internet you need to check whether or not the website that you are scraping from allows their data to be used. If they have special requirements or requests you are ethically responsible to make sure that you adhere to these. Thus, before I scraped this data I checked whether or not it was ethical or not. Below you will see the simple code that I used to ensure that I could scrape this data.
```
r = requests.get(url)
r.status_code
```
After running this code it will produce a status code. There are a few status code possibilities. When I ran this for the NBA dataset I code the status code 200 which meant that the data from the website was allowed to be scraped! If you are wanting to scrape data from a website make sure to do so ethically!

![Test Image](https://raw.githubusercontent.com/claudia-caten/stat386-projects/main/assets/images/data-ethics.png)


# Using Packages to "Assist" your Web Scraping
Due to the importance of web scraping in data analysis, coders have developed packages to make web scraping very easy and user-friendly. Based on where you find your data and the format of the web page you are using, different packages will help you to accomplish your purposes. API's are also a great resource to use to scrape data. You can learn more about API's and how to use them on other data science blogs. 
In order to scrape this data, I used the requests package and specfically the pandas function read_html. This dataset was very easy to access using these packages. I encourage you to figure out what method would work best for the data that you are trying to scrape. Below is an example of how I used the read_html function to create a dataframe.
```
nba = pd.read_html(url)
nba = nba[0]
```

You can find the whole code that I used in my GitHub repository <a href="https://github.com/claudia-caten/web-scraping"> HERE </a>.

# Slam Dunk Data Analysis
Now that we have transformed the data from a website to a data frame we are ready to analyze the data! This is the whole point of scraping the data, so that we can use it to find out more about the subject of interest. Once you have the data you can run all sorts of tests to learn more about the population. Data can be used to make visualizations, inferences and even predictions. Now that I have created a dataframe full of interesting information about different NBA players I am excited to analyze it more throroughly. Data is powerful because data is knowledge, I am excied to see what else I can learn about this data to prepare for the next NBA season. What questions do you have about this data? Comment below anything you think would be interesting for me to analyze further!
