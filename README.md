# Analysis of Full-time STEM Compensation

**Project Status: Completed**

## Table of contents
- [Introduction](#introduction)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Project Description](#project-description)
- [Project Results](#project-results)
- [Installation](#installation)

## Introduction
[(Back to top)](#table-of-contents)
<br>

As a current M.S. in Data Science student at NYU, I'm looking to work as a full-time data scientist after I graduate. I think it's important for me and other job seekers to more fully understand compensation in the STEM field. However, it is not entirely clear which specific factors are driving STEM compensations. 

In this project, I answer the following questions: 
+ Which STEM roles are the most well-paid?
+ Are graduate degrees such as Master’s degrees and Doctorates important driving factors of salary compensation? 
+ Do years of experience directly contribute to the amount of compensation? 
+ Lastly, which specific factors are the major driving forces of salary in the STEM fields? 
In this report, I will explore possible answers to these questions and more by analyzing data from an online site that offers services in salary negotiation.

## Methods Used
[(Back to top)](#table-of-contents)
+ Data Collection
+ Data Cleaning
+ Exploratory Data Analysis
+ Correlation Analysis
+ Data Visualization
+ Multiple Linear Regression

## Technologies:
[(Back to top)](#table-of-contents)
+ Python
+ NumPy 
+ Pandas
+ Datetime
+ Matplotlib
+ Seaborn
+ Scipy
+ Sklearn
+ Requests

## Project Description:
[(Back to top)](#table-of-contents)

+ Loaded .json file from levels.fyi into a pandas DataFrame using the requests library 
+ Cleaned the data by using pandas
+ Regarding feature engineering I added race and education from 'other details' column
+ To read more about the data cleaning and feature engineering process <a href="" target="blank">, view full code here.</a>
+ Conducted an exploratory data analysis (EDA) to investigate factors impacting STEM Compensation
+ Implemented a Multiple Regression Analysis to see the most important factors that determine "total yearly compensation" 

## Project Results:
[(Back to top)](#table-of-contents)
<br>


## Installation:
[(Back to top)](#table-of-contents)
+ Clone this repo <a href="https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository" target="_blank">(for help see this tutorial).</a>
+ Raw data, data processing/transformation script is being kept in this repo. <a href="" target="_blank">Click here for notebook.</a>
