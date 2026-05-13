#Netflix Data Analysis 📺

##Project Overview

This project performs data cleaning, preprocessing, exploratory data analysis (EDA), and visualization on the Netflix Movies and TV Shows dataset using Python.

##The analysis focuses on:

Handling missing values
Cleaning inconsistent data
Exploring content trends
Identifying popular genres
Analyzing release years and countries
Visualizing Netflix content distribution
Technologies Used
Python
Pandas
NumPy
Matplotlib

###Dataset Information

The dataset contains information about Netflix Movies and TV Shows including:

Title
Type (Movie / TV Show)
Director
Cast
Country
Release Year
Rating
Duration
Genres
Date Added

###Dataset size:

8807 rows
12 columns


###Data Cleaning

Several preprocessing and cleaning steps were performed to improve data quality.

Missing Values Handling
Country Column
Missing country values were replaced using the most frequent country.
Multiple-country entries were simplified by selecting the first country listed.
Rating Column

Some incorrect values such as movie durations were mistakenly stored inside the rating column. These invalid values were corrected and missing ratings were filled using the most common rating.

Director and Cast Columns

Large numbers of missing values existed in these columns. Missing entries were replaced with "Unknown" to preserve dataset consistency.

Date Added and Duration

Missing values in these columns were filled using the mode (most frequent value).

Feature Engineering

Additional features were created from the date_added column:

Month of upload
Uploaded year

Unnecessary columns such as:

show_id
description
date_added

were removed after processing.

Exploratory Data Analysis
Movies vs TV Shows

The dataset contains significantly more Movies than TV Shows.

Insight

Netflix appears to prioritize movie content over TV shows in its catalog.

Monthly Release Trends

A heatmap analysis was performed to study Netflix uploads across different months and years.

Insights
Netflix content uploads increased rapidly after 2016.
October, November, and December showed higher upload activity.
2019 and 2020 were peak years for content additions.
Most Popular Movie Genres

###The most common movie genres were:

International Movies
Dramas
Comedies
Documentaries
Action & Adventure
Insight

International and drama-based content dominates Netflix movie offerings.

Most Popular TV Show Genres

The most common TV show categories were:

International TV Shows
TV Dramas
TV Comedies
Crime TV Shows
Kids' TV
Insight

Netflix strongly emphasizes international TV content and drama-based series.

Release Year Analysis

Content releases increased significantly between 2016 and 2020.

Key Findings
2018 and 2019 had the highest movie releases.
2020 had the highest number of TV show releases.
Netflix rapidly expanded its content library during these years.
Country-Based Analysis

###Top countries contributing Netflix content:

United States
India
United Kingdom
Canada
Japan
Insight

The United States contributes the largest portion of Netflix content, followed by India.

Duration Analysis
TV Shows

Most TV shows on Netflix contain:

1 Season
2 Seasons
3 Seasons
Insight

Short-running TV series dominate the platform.

Ratings Analysis

The most common rating found in the dataset was:

TV-MA
Insight

A large portion of Netflix content is targeted toward mature audiences.

Key Insights from the Project
Movies dominate Netflix's platform compared to TV shows.
International content is highly popular.
Drama and comedy genres are the most common.
Netflix experienced massive content growth after 2016.
Most TV shows are short series with limited seasons.
The United States is the leading content producer on Netflix.
Skills Demonstrated

This project demonstrates practical skills in:

Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
Trend Analysis
Python Data Analytics
Future Improvements

Possible future enhancements include:

Building a recommendation system
Sentiment analysis on movie descriptions
Interactive dashboards using Plotly or Streamlit
Predictive analysis on future Netflix trends
Genre classification models using machine learning
Conclusion

This project provides a complete exploratory analysis of Netflix content and highlights important trends in genres, releases, countries, ratings, and content growth over time.

The analysis demonstrates how Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn can be used effectively for real-world data analytics and visualization projects.
