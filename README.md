Airbnb Data Analysis: Customer Satisfaction
Objective
Identify key factors that contribute to higher customer satisfaction ratings for Airbnb listings in Boston.

Steps
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