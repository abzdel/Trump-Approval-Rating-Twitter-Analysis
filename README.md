# Trump-Approval-Rating-Twitter-Analysis

## Project Overview
In this project, we scrape tweets about COVID19, stimulus checks, and President Trump to see how the sentiment of these tweets change with his approval rating throughout the COVID19 Pandemic. We also use twitter's API to scrape more recent tweets by location and produce an election simulation.

## Task
  This project explores Donald Trump’s approval rating based on tweets regarding the US stimulus checks as well as tweets regarding Coronavirus. We explore how Trump's approval rating moves across time in conjunction with these tweets. Our goal is to see if there is a correlation between the number (and sentiment) of tweets with a keyword and the approval rating. We will annotate key dates from the Trump Administration's coronavirus timeline on our plots as well. We will then take the results from this analysis and see how they correlate to the winner of our election simulation.

- Part 1 deals with Trump's approval rating as compared to our scraped tweets
- Part 2 deals produce an election simulation based off of current tweets (sample of 10 states)

## Run Locally
1. Run the command `git clone https://github.com/abzdel/Trump-Approval-Rating-Twitter-Analysis`
2. Run `npm install`
3. Run `npm start-dev`

## Programs & Packages
- **Python**: Version 3.7
- **Packages**: twython, pandas, numpy, textblob, basemap, 
seaborn, matplotlib, re, nltk, wordcloud, geopy
- **Excel**: For initial data cleansing

## Outside Data
- We used [Donald Trump's Approval Rating](https://projects.fivethirtyeight.com/trump-approval-ratings/) from fivethirtyeight.com. We analyzed the approval rating from January 4th, 2020 through May 2nd, 2020 (our project's due date).

