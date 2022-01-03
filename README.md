# Covid-19_vaccine Twitter data

These data files are used to support the findings in the paper "Dynamic assessment of the COVID-19 vaccine acceptance leveraging social media data" published in the Journal of Biomedical Informatics by Lingyao Li, Jiayan Zhou, Zihui Ma, Michelle Bensi, Molly Hall, and Gregory Baecher.

In this study, we proposed a social media-based approach that derives a vaccine acceptance index (VAI) to quantify Twitter users’ opinions on COVID-19 vaccination. This index is calculated based on opinion classifications identified with the aid of natural language processing techniques. This index provides a quantitative metric to indicate the level of vaccine acceptance across different geographic scales in the U.S. 


### 1. Tweet data

This folder contains all the tweet data, including original tweets, retweets, mentions, and replies related to the COVID-19 vaccine. The Twitter Standard Search API was used with the search term "vaccine" and geocode "39.8, -95.583, 2500 km" to scrape vaccine-related tweets in the date range from August 9, 2020, to April 18, 2021, over the geographic area covered by the geocode. 

Please note that restrictions apply to the availability of Twitter data, which are used under license for the current study, and so specific user information or tweets messages are not publicly available. The tweet IDs are however available from this published dataset, but the original tweets are available with permission of Twitter Inc.


### 2. National-level analysis

1  VAI_nation_volume.xlsx\
This file includes the volume of positive- and negative-classified tweets over time from August 9, 2020, to April 18, 2021. It also shows the national VAI computed each day and on a 7-day rolling average. 


### 3. State-level analysis

1  VAI_state_daily.xlsx\
2  VAI_state_weekly.xlsx\
3  VAI_state_monthly.xlsx\
These three files include the state-level VAI results that were calculated on a daily, 7-day rolling, and 30-day rolling basis. 

4  vaccination_state.xlsx\
This file shows the vaccination rate for each state on April 22, May 22, June 22, 2021. The data for vaccination rates were obtained from CDC COVID-19 Data Tracker https://covid.cdc.gov/covid-data-tracker.

5  correlation_state_day.xlsx\
6  correlation_state_week.xlsx\
7  correlation_state_month.xlsx\
These three files show the temporal change in correlation between the vaccination rate (reported on June 22, 2021) and the state-level VAI. The correlation analysis was repeated based on daily, 7-day rolling, and 30-day rolling VAI.


### 4. County-level analysis
1  VAI_county_0809.xlsx\
2  VAI_county_1214.xlsx\
These two files show the county-level VAI results that were calculated using Twitter data: (1) from August 9, 2020, to April 18, 2021, and (3) from December 14, 2020, to April 18, 2021.

3  vaccination_county.xlsx\
This file shows the county-level vaccination rate on April 22, May 22, June 22, 2021. The data for vaccination rates were obtained from CDC COVID-19 Data Tracker https://covid.cdc.gov/covid-data-tracker.

4  vaccine_hesitancy_cdc.xlsx\
This dataset is the CDC estimated vaccine hesitancy based on the data collected by the CDC from March 3 to 15, 2021. Specific explanations to the estimated vaccine hesitancy is listed here: https://data.cdc.gov/stories/s/Vaccine-Hesitancy-for-COVID-19/cnd2-a6zw/.

5  VAI_county_user30.xlsx\
Our study explores the effect of sample size on the computed correlation between the index and county-level vaccination rates. The correlation analysis suggests that correlations stabilized when only considering counties for which data was available from at least 30 users. This file shows the county-level data with at least 30 users from a county.

6  correlation_county_users.xlsx\
This dataset shows the change in correlation with number of users and the vaccination rate in a county. The change in correlation with number of users in a county was based on two scenarios: (1) using all the data in the study period, and (2) using data after the first vaccine distribution. 

#### Please note that these data files can only be used for non-commercial purposes related to COVID-19 vaccine topics. If you have any questions about the posted datasets, please do not hesitate to reach us at lilingyao@hotmail.com. 
