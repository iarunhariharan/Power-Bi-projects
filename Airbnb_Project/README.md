#Airbnb Data Analysis Project

Overview
This project analyzes Airbnb listing data for New York City to uncover patterns, trends, and actionable insights.

 The dataset includes information about hosts, neighborhoods, room types, pricing, reviews, and availability.
 
 The project includes data cleaning, analysis, and visualization, culminating in a Power BI dashboard.

1. Data Cleaning Process

The following steps were performed to clean and prepare the data:

i. Handling Missing Values:

- Missing values in columns such as name and host_name were replaced with "Unknown."

- For last_review and reviews_per_month, missing values were handled logically:
last_review set to null when no reviews exist.
reviews_per_month filled with 0 for listings with no reviews.

ii. Standardizing Text Data:

- Removed extra whitespaces and unnecessary special characters.

iii. Removing Duplicates:

- Duplicate rows were identified and removed to ensure data integrity.


2. Visualizations

The analysis is summarized through interactive visualizations built using Power BI. Key dashboards include:

i. Reviews Overview:

Average reviews per month: 1.37
Total number of reviews: 1M+
Review trends by year and month to observe seasonality.

ii. Bookings by Neighborhood Group:

- Bookings are predominantly from Manhattan and Brooklyn.

iii. Price Analysis:

- Average prices by neighborhood show Sea Gate as the most expensive area ($482.50).

- Neighborhood group and room type combinations indicate:

- Entire homes/apartments are costliest in Manhattan ($230.19).

- Shared rooms are most affordable in Brooklyn ($45.46).

iv. Top Hosts and Neighborhoods:

- Top 10 hosts by review count, with Maya having the highest number of reviews (2.2K).

v. Room Type and Availability:

- Insights into minimum nights required by room type and neighborhood.


3. Insights

Key findings from the analysis include:

i. Manhattan and Brooklyn dominate the Airbnb market in NYC, contributing to over 85% of the total bookings.

ii. Sea Gate and Tribeca are premium neighborhoods, while the Bronx offers affordable options.

iii. Seasonality in reviews: Most reviews occur in the summer months, indicating higher demand.

iv. High host diversity: Hosts with multiple listings contribute significantly to availability in Manhattan and Brooklyn.

4. Conclusion

This analysis provides a comprehensive understanding of the Airbnb market in New York City, highlighting key trends and areas of interest for stakeholders. The findings can guide hosts in optimizing their listings and help travelers make informed decisions.



