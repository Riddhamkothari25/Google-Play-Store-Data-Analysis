# Google-Play-Store-Data-Analysis


PROJECT TITLE	
GOOGLE PLAY STORE APPS
(REGULATORY AFFIARS)

TOOLS	
PYTHON,  ML, GOOGLE COLLAB

DOMAIN	
DATA ANALYST & DATA SCIENTIST
 
About Dataset- 
Context
While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, I found out that the iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

Content
Each app (row) has values for category, rating, size, and more.

Acknowledgements
This information is scraped from the Google Play Store. This app information would not be available without it.
Inspiration
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market!

Android is the dominant mobile operating system today with about 85% of all mobile devices running Google’s OS. The Google Play Store is the largest and most popular Android app store. The purpose of our project was to gather and analyze detailed information on apps in the Google Play Store in order to provide insights on app features and the current state of the Android app market. The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app (row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps. Explore and analyze the data to discover key factors responsible for app engagement and success.

Steps:
1.	Importing libraries
2.	load the Data
3.	Description of Data
4.	Cleaning the Data
5.	Top 10 Highest rating Apps in google play store in terms of categories
6.	Number of Application in terms of Category
7.	Top 10 apps which has more downloads
8.	Which 10 apps from the 'FAMILY' category are having the lowest rating and highest rating.
9.	Free and Paid Apps
10.	Relation between app category and app price
11.	Filter out "junk" apps
12.	Sentiment analysis of user reviews.
Project Name - Play Store App Reviews Analysis

Project Summary
This project focuses on gathering and analyzing comprehensive information about apps on the Google Play Store to provide valuable insights into app features and trends in the Android app market.
We utilized Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to perform data cleaning, analysis, and visualization effectively.
The Google Play Store sees the addition of thousands of new applications daily, created by developers worldwide striving to make their apps successful. Given the intense global competition, it is crucial for developers to understand whether their strategies align with user preferences and market trends. While most Play Store apps are free, the revenue mechanisms—such as in-app purchases, advertisements, and subscriptions—are often ambiguous and not easily measurable. Therefore, the success of an app is usually judged by factors like the number of installations and user ratings rather than direct revenue generation.
The objective of this project is to uncover patterns and insights that help developers better understand user demands and optimize their apps for popularity and success. Specifically, we explored relationships between various attributes, such as app pricing models (free vs. paid), user reviews, and app ratings, to provide actionable insights for developers.

Problem Statement :
The goal of this project is to explore and analyze data to identify the key factors that drive app engagement and success.
The analysis is based on two datasets: one containing fundamental information about apps (googleplaystore.csv) and another with user reviews (googleplaystore_user_reviews.csv) for those apps. By thoroughly examining and evaluating these datasets, the objective is to pinpoint the critical characteristics and trends that influence user engagement and contribute to an app's overall success.

Business Objective :
The objective is to analyze user preferences and behaviors related to apps based on various attributes such as category, genre, number of installations, app size, and type (free or paid). These insights will assist developers in making informed decisions and tailoring their apps to align with user demands, ultimately enhancing app success and engagement.

🛠️ Builds with
Python

NumPy

Pandas

Matplotlib

Seaborn

GoogleColab

Summary and Conclusion
Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we replaced these null values with the mode of ratings.

After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs.

Furthermore, we merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

Key insights and conclusions drawn from our analysis include: Positive correlation between reviews and installs, while price and rating exhibit negative correlation.

The "Art and Design" category has the highest number of installs.
Developing apps within the "Family" and "Lifestyle" categories may result in higher revenue.
Approximately 61% of users have a positive sentiment, while only around 15% express negative sentiment.
Free apps account for 92.12% of the dataset, while paid apps constitute 7.81%.
The "Everyone" content rating category dominates, representing 81.80% of all apps.
The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
"Game" category presents potential opportunities for developers due to its high number of installs.
Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
The average rating of apps on the Play Store is 4.17, indicating a satisfactory overall quality.
Users prefer lightweight apps and may be hesitant to download larger, paid apps.
Apps reviewed by a larger number of people tend to be downloaded more frequently.
Users tend to leave harsher reviews for paid apps.
A positive correlation exists between installs and rating.
Developing an app with a high rating requires timely updates and optimal app size.
Developing free apps with a content rating suitable for everyone is beneficial.
The dataset holds immense potential for improving business value and making a positive impact. - - It extends beyond the specific problem addressed in this project, with numerous other interesting possibilities waiting to be explored through further analysis.
By successfully achieving our project objectives and answering our research questions, we have obtained valuable insights into the Google Play Store apps ecosystem and the trends within.

