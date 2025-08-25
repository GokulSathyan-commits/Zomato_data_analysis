# Zomato Restaurant Data Analysis

## Overview
This project analyzes a dataset of restaurants from Zomato to uncover cuisine popularity, pricing vs. rating relationships, and location-based restaurant patterns. It provides insights into top cuisines, restaurant pricing and ratings, city-wise trends, and identifies top-rated and best-value restaurants.

## Key Features

### Cuisine Analysis
- Parses and counts occurrences of different cuisines from the dataset.
- Displays the top 5 most popular cuisines.

### Pricing and Ratings Analysis
- Provides descriptive statistics for average cost for two and restaurant ratings.
- Visualizes the relationship between cost and rating using scatter plots.
- Computes the correlation between pricing and ratings.

### Location Analysis
- Lists top cities by number of restaurants.
- Shows average restaurant ratings by city, highlighting the highest-rated cities.

### Insights and Summary
- Identifies the top 3 highest-rated restaurants.
- Highlights the top 3 best-value restaurants based on a custom value metric (high rating, low cost).
- Summarizes key statistics: total restaurants, average rating, average cost.
- Reports the most popular cuisine and city, and counts restaurants that offer table booking.

## Working of the Code

1. **Data Loading**: Loads the `zomato.csv` file with proper encoding handling to avoid errors.
2. **Cuisine Parsing**: Splits the "Cuisines" column into individual cuisines and counts their frequencies.
3. **Statistical Analysis**: Uses pandas to calculate descriptive statistics for cost and ratings.
4. **Visualization**: Creates a scatter plot to observe the relationship between average cost and aggregate rating.
5. **City-wise Analysis**: Aggregates the count and average rating of restaurants by city.
6. **Insight Generation**: Finds top-rated restaurants and best-value restaurants by combining cost and rating into a "value score".
7. **Summary Statistics**: Outputs overall dataset statistics including total restaurants, average rating, and popular cuisine/city information.
8. **Outputs**: Prints results on the console and displays a scatter visualization.

## Usage

1. Place the `zomato.csv` dataset file in the same directory.
2. Run the Python script.
3. View the printed insights and the scatter plot visualization.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
