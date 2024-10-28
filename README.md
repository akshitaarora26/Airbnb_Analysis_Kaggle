## **Airbnb Market Analysis**
Welcome to the Airbnb Market Analysis project! This repository contains a data analysis project that examines Airbnb listing data across 10 major cities, focusing on factors that influence pricing and market characteristics.

**Project Overview**
This project uses a dataset of over 250,000 Airbnb listings and 5 million reviews from 10 major cities worldwide. The primary objectives are to analyze key factors impacting pricing, identify major differences between markets, and evaluate which attributes offer the best value for travelers. The analysis also explores trends and seasonality in review data.

**Objectives**
Identify Market Differences: Analyze and compare pricing across different cities.
Determine Price Influencers: Understand which listing attributes, such as city, room type, and number of bedrooms, significantly impact the price.
Analyze Trends and Seasonality: Detect patterns in review data to identify seasonal variations or trends.
Evaluate Travel Value: Determine which cities offer the best value for Airbnb guests by balancing price, ratings, and reviews.

**Dataset**
The dataset includes the following key attributes:

Listing Information: city, price, room_type, bedrooms, and other features.
Review Data: review_scores_rating, review_scores_cleanliness, review_scores_location, and additional review metrics.

**Data Preprocessing**
The project preprocesses the data by:

Handling Missing Values: Filling or dropping missing values.
Currency Standardization: Converting prices to a standard currency (USD) for cross-city comparisons.
Categorical Encoding: Converting categorical variables (e.g., room type, city) to numerical format using one-hot encoding.

**Key Analysis and Findings**
1. Major Market Differences
Cities like New York, Sydney, and Paris are high-cost markets, while cities like Istanbul and Mexico City offer more budget-friendly options.
Entire homes tend to have the highest prices, whereas shared and private rooms offer cheaper alternatives across most cities.
2. Attributes Influencing Price
Using linear regression and Random Forest models, the analysis identified the top attributes influencing price:

City: The biggest price influencer, with cities like New York and Sydney commanding higher prices.
Room Type: Entire homes are generally more expensive, while private and shared rooms are cheaper.
Number of Bedrooms: More bedrooms significantly increase the listing price.
Review Scores: Higher ratings slightly increase prices, though this effect is minimal compared to city and room type.
3. Trends and Seasonality
Monthly analysis of review counts and scores reveals potential seasonal trends, such as higher review volumes in months on Oct, Nov and Dec. (in 2019)
4. Best Value for Travelers
A value score was created to balance price and ratings, showing that budget-friendly cities with high ratings, such as **Istanbul**, offer the best value.

**Future Enhancements**
Extend Analysis: Incorporate additional cities and compare across different regions.
Dynamic Currency Rates: Use dynamic exchange rates to adjust for real-time market fluctuations.
Advanced Models: Apply advanced machine learning models for more nuanced insights on price prediction.
