# Covid-19_vaccine Twitter data

These data files are used to support the findings in the paper "Dynamic assessment of the COVID-19 vaccine acceptance leveraging social media data" published in the Journal of Biomedical Informatics by Lingyao Li, Jiayan Zhou, Zihui Ma, Michelle Bensi, Molly Hall, and Gregory Baecher.

In this study, we proposed a social media-based approach that derives a vaccine acceptance index (VAI) to quantify Twitter users’ opinions on COVID-19 vaccination. This index is calculated based on opinion classifications identified with the aid of natural language processing techniques. This index provides a quantitative metric to indicate the level of vaccine acceptance across different geographic scales in the U.S. 


### 1. Tweet data

This folder contains all the tweet data including original tweets, retweets, mentions, and replies related to COVID-19 vaccine. The Twitter Standard Search API was used with the search term “vaccine” and geocode “39.8, -95.583, 2500 km” to scrape vaccine-related tweets in the date range from August 9, 2020 to April 18, 2021 over the geographic area covered by the geocode. 

This folder also contains the datasets used for training and testing the classification models. 

Please note that restrictions apply to the availability of Twitter data, which are used under license for the current study, and so specific user information or tweets messages are not publicly available. The tweet IDs are however available from this published dataset, but the original tweets are available with permission of the Twitter Inc.


### 2. National-level analysis

1. temporal analysis.xlsx
This file include the volume of positive- and negative-classified tweets over time from August 9, 2020, to April 18, 2021. It also shows the national VAI computed each day and on a 7-day rolling average. 


### 3. State-level analysis

1. acceptance_daily.xlsx
2. acceptance_weekly.xlsx
3. acceptance_monthly.xlsx
These three files include the state-level VAI results that were calculated on daily, 7-day rolling, and 30-day rolling basis. 

4. vaccination_rate.xlsx
This file shows the vaccination rate for each state on April 22, May 22, June 22, 2021. The data for vaccination rates were obtained from CDC COVID-19 Data Tracker. https://covid.cdc.gov/covid-data-tracker

5. correlation_day.xlsx
6. correlation_week.xlsx
7. correlation_month.xlsx
These three files show the temporal change in correlation between vaccination rates (June 22, 2021) and the VAI. The correlation analysis was repeated based on daily, 7-day rolling, and 30-day rolling VAI.


### 4. County-level analysis
