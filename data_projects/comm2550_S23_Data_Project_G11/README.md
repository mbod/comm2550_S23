# Data project for COMM2550 _Foundations in Data Science for Communication_ (Spring 2023)

## Background Information

Dengue is a virus spread by the Aedes mosquito and causes fever, bone pain and in severe cases, internal bleeding, organ failure and death. The Aedes mosquito thrives in hot and rainy tropical climates, like that of Singapore, leaving its citizens susceptible to the virus. Given that dengue outbreaks occur almost every year in Singapore, it is important to investigate predictors of the virus, so that action can be taken to curb the spread of dengue.

## Project Overview

Our overarching research question is: How do Google search trends correlate with various measures of weather and dengue cases in Singapore?

We decided to focus on Google search trends because it is possible that there is an increased interest in dengue before an outbreak, especially since there is an incubation period of about 1 week before a dengue diagnosis. If we could find a significant correlation, it could mean that Google search trends may be useful in predicting dengue outbreaks, since more people are Googling about it.

We also want to investigate how various weather measures like the amount of precipitation and hours of sunshine may correlate with dengue trends. Even though we know that Singapore has a higher average rainfall compared to other countries and thus has an increased risk of dengue, we are not sure what kinds of seasonal weather patterns there may be across the year in relation to dengue in Singapore.

Further, there could be a relationship of the weather with Google search trends related to dengue, which could in turn provide more evidence that these Google searches are predictors of dengue outbreaks.

## Research Questions & Hypotheses

**RQ1: What is the relationship between trends of Google search terms for dengue and the number of reported dengue cases in Singapore?**  
```
H1: The number of dengue-related Google searches is positively correlated with the number of reported dengue cases in Singapore.  

H2: An increase in dengue-related Google searches will be followed by a slightly delayed increase (within 0-2 weeks) in the number of reported dengue cases in Singapore.  

H3: An increase in the number of reported dengue cases in Singapore will be followed by a slightly delayed increased (within 0-2 weeks) in dengue-related Google searches  
(H3 was added after conducting exploratory analysis for H2)
```

**RQ2: What is the relationship between various weather measures and dengue cases in Singapore?**
```
H4: Precipitation rate is positively correlated with the number of dengue cases in Singapore.

H5: Relative humidity is positively correlated with the number of dengue cases in Singapore.

H6: Hours of sunshine is positively correlated with the number of dengue cases in Singapore.
```

**RQ3: What is the relationship between various weather measures and trends of Google search terms for dengue in Singapore?**
```
H7: Precipitation is positively correlated with the number of dengue-related Google searches in Singapore.

H8: Humidity is positively correlated with the number of dengue-related Google searches in Singapore.

H9: Hours of sunshine is positively correlated with the number of dengue-related Google searches in Singapore.
```

## Data Sources

For the weekly number of dengue cases, we downloaded the data from Singapore's [official open data repository](data.gov.sg). 

Many measures of weather, including daily temperature, rainfall and relative humidity, could not be found on official websites, and were thus downloaded from [Open Meteo's API](https://open-meteo.com/en/docs/historical-weather-api). 

For Google search trends, we used Google trends and found data on 9 keywords including: dengue fever, dengue, fever, bone pain, mosquito bite, mosquito, rain, rash and rashes. Apart from “dengue”, we selected the rest of these keywords because they were the most common symptoms for dengue.

All data was obtained for the period between 2012 and 2022, in intervals of 1 weeks, based on the epidemiological weeks used by Singapore (and many countries around the world) for the recording of such data. The time period of 2012-2022 was decided based on the scope of the dengue case data that was made avaiable on the [Singapore open data repository](data.gov.sg).


## Brief Summary of Findings
Overall, we find that many of our hypotheses were either rejected or even shown to be the contrary, at least based on the correlations and visual inspection of the line graph trends. One of the most intriguing is that neither rainfall nor relative humidity really correlates with dengue cases, which is opposite to what we would usually expect, given the increased breeding of Aedes aegypti mosquitoes in wetter environments. Nonetheless, mean temperature was still found to be one of the stronger predictors for dengue cases at lags of 0-1 week, in line with general expectations.

In terms of Google search trends, we find that search terms directly related to dengue are moderately and positively correlated with dengue cases with no lag intervals, which supports our overarching theory that people will tend to search more about dengue when they have dengue symptoms, which correspondingly reflects dengue case numbers. Perhaps, given the high awareness of dengue in Singapore, people with prolonged symptoms or symptoms characteristic of dengue tend to think of dengue and perform searches to confirm (or otherwise assure themselves) that they might have or do not have dengue.

## Folder Structure
The root folder contains subfolders of 3 main components of this project, each of which may contain further subfolders:
1. `data`: the raw and cleaned data that was used for this project
    - `cleaned`: contains csv files of the cleaned data
    - other subfolders contain the raw data for dengue, weather, and Google search trends
2. `data_analysis`: Jupyter notebooks detailed the steps taken for the data cleaning and data analysis
    - `data_cleaning`: Jupyter notebooks used for cleaning the raw data and consequently generating the csv files in the `data/cleaned` folder
    - three Jupyter notebooks that detail our data analysis, segmented and titled by the corresponding research question
3. `data_story`: a blog post written in a Jupyter notebook, summarizing the findings of our project, which can be read without delving into any of the code
    - `photos`: required resources to render the blog post Jupyter notebook
    - one Jupyter notebook that is the blog post
4. `presentation`: a brief presentation and summary of our work halfway into this data project