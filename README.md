📊 Netflix Content Analysis & Visualization

This project presents an end-to-end exploratory data analysis (EDA) and visualization of Netflix’s content catalog. The objective is to uncover meaningful insights about movies and TV shows on the platform by analyzing trends related to genres, actors, directors, countries, ratings, and release patterns.

The analysis involves extensive data cleaning, transformation, feature engineering, and visualization to better understand how content is distributed and consumed on Netflix.

🔍 Analysis Performed
Data Exploration & Cleaning

Generated a summary and shape of the dataset

Detected and handled missing values

Checked for duplicate records

Renamed the listed_in column to Genre for clarity

Data Transformation

Unnested multi-valued columns:

director

cast

country

Genre

Dropped irrelevant columns:

description

show_id

Created a new feature added_year from the date_added column

Cleaned and transformed the duration column:

Converted values such as 90 min → 90

Converted 2 Seasons → 2

Removed null values from the duration column

Advanced Insights

Identified the best actor–director pair using combined frequency analysis

Determined which actors appear most frequently in specific rating categories

📈 Visualizations & Insights

The project includes multiple visual analyses to highlight content trends:

Distribution of Movies vs TV Shows

Number of movies released each year after 2018

Top 10 directors producing the most TV shows

Distribution of content across different genres

Top content-producing countries on Netflix

Year-wise trend showing how movies and TV shows added to Netflix have evolved

Top 5 most frequent actors appearing in the top 3 most represented genres

🛠️ Tools & Technologies

Python

Pandas & NumPy

Matplotlib & Seaborn

🎯 Key Takeaways

This project demonstrates strong proficiency in:

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Feature engineering

Data visualization

Extracting actionable insights from real-world datasets

It serves as a solid portfolio project for roles in Data Analysis, Data Science, and Business Intelligence.
