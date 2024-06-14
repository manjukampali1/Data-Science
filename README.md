**Airbnb Data Analysis**: 

Objective
Identify key factors that contribute to higher customer satisfaction ratings for Airbnb listings in Boston.

****Library used ****
pandas
plotly.express 



**Project Motivation**
The motivation behind this project is to get  understanding of the of Airbnb listings in Boston. With the popularity of short-term rentals that are happening , it is crucial for rent owners and investors to make good decisions based on data. This project trying address the following key questions 
Occupancy Rates:
Pricing Strategy
Customer Satisfaction

**Link to Blog **
https://medium.com/@manjukampali/a-newbies-journey-into-airbnb-data-analysis-and-data-science-pricing-strategy-occupancy-rates-2b36ba4c5038

**Acknowledgement **
would like to express our gratitude to the following:
Amdocs : for giving me opportunity to learn and Udacity program 
Airbnb: For providing the datasets used in this analysis. The data has been good in understanding different aspects of Airbnb listings in Boston
pandas: flexible data manipulation library that made data cleaning and preprocessing easy.
plotly: visualization library that helped us to create insightful visualizations.



**Steps**
1. Data Loading
Load datasets: calendar.csv, listings.csv, and reviews.csv.
2. Data Merging
Merge datasets on listing_id.
3. Data Cleaning
Convert price to numeric by removing dollar signs and commas.
4. Exploratory Data Analysis (EDA)
Visualize relationships between satisfaction ratings and:
Price
Number of reviews
Room type
5. Key Findings
Price: No clear linear relationship with satisfaction ratings.
Number of Reviews: Listings with more reviews have a wide range of ratings; fewer reviews often correlate with higher ratings.
Room Type: Entire homes/apartments generally have higher satisfaction ratings compared to private or shared rooms.
Conclusion
Room type and the number of reviews are significant factors in customer satisfaction, while price alone is not a strong determinant.

Visualizations
Scatter plot: Review Scores Rating vs. Price
Scatter plot: Review Scores Rating vs. Number of Reviews
Box plot: Review Scores Rating vs. Room Type
Usage
Run the provided Python code to reproduce the analysis and visualizations.
