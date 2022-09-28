---
layout: post
title:  "Becoming a Regression ExpeRt"
date:   2022-08-02
author: Claudia Caten
description: Regression is an essential tool as a statistican. In this blog post I will go over how to use R to perform different types of Regression data analysis.
image: 
---
Learning how to perform regression is an indispensable tool as a statistician. Regression is useful to understand the relationship between variables and to be able to make predictions. In my experience as a learning statistician, I have learned a lot about regression, and I recognize that there is a lot more to be learned. I have been able to use Regression to answer all types of questions. I have been able to predict where a prospective farmer should purchase land, the amount of air pollution based off the amount of traffic in an intersection and even whether a tumor will be malignant. As you can see Regression is an incredibly important tool. This blog will cover some of the basics of regression, but I encourage you to learn even more!

#Different Types of Regression
It's first important to recognize that there are many different types of Regression, just like there are many types of datasets. Regression can be performed on the simplest and the most complex datasests. This blog will be centered on the most basic type of regression, simple linear regression. Beyond this you can perform regression on datasets with multiple explanatory variables, datasets with both categorical and quantitative variables and even variables that don't appear to have a linear relationship. Essentially each of these more complex types of regression are just variations of simple linear regression. We will go through the basic steps of this below.

#Exploring the Data
Before Americans expanded west, they sent explorers to learn more about the land in the west. Similarly, before we start to perform regression, we need to learn all that we can about the data. Performing an exploratory data analysis (also known as an EDA) is an essential step. Doing this helps us to know what kind of regression we will perform and helps us to become acquainted with the dataset that we are working with. 
The most basic type of exploratory data analysis is to graph the data. Humans are visual learners and to truly understand a dataset it helps us to be able to see the data. After graphing the data, it is also helpful to find simple statistics such as covariance and correlation to help us to better understand the relationships between variables. Once we have explored the data, we are ready to fit a model!

#Fitting a Model
A regression model is a model that can help us to understand the relationships between variables and to predict how other data would react. Models for regression can be derived using calculus and least squares estimates. To learn more about regression models go HERE. Although the math behind regression models is very interesting, this blog will focus more on how to use R code to fit the dataset to a model. I think that it is interesting to understand the mechanics behind models but for the most part, I let my computer do most of the actual computing for me. We can fit a simple linear regression model with a simple line of code:

#Time to Make Predictions
Once we have fit a model (and made sure that our data meets the assumptions) we can use it to make predictions about the data. In my opinion this is the funnest part. It is important to note here that it is unethical to try to use data outside of the range of the original dataset to make predictions. This is known as data extrapolation. If we use a data point that would fit within the range of the original dataset we can once again use R to predict the response variable associated with our explanatory variable as if it was in the original dataset. The line of code used to do this is:
