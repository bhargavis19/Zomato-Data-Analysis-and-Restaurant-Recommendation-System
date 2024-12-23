# Zomato-Data-Analysis-and-Restaurant-Recommendation-System

## Overview
Bengaluru, known for its rich food culture, offers a diverse array of cuisines from across the globe. From American and Japanese to Russian, and even rare finds like Antarctic cuisines, Bengaluru has it all. Whether you're looking for delivery, dine-in, pubs, bars, buffets, or desserts, the city caters to every culinary need. With over 12,000 restaurants currently operating and new ones opening daily, Bengaluru continues to be a paradise for food lovers. Despite the burgeoning number of eateries, the industry remains unsaturated, driven by rising demand. However, new entrants face significant challenges such as high real estate costs, food price inflation, staffing shortages, fragmented supply chains, and complex licensing processes.

This project utilizes Zomato data to explore the food landscape of Bengaluru, aiming to assist aspiring restaurateurs in making data-driven decisions. By analyzing this dataset, we can identify trends and preferences, offering insights into popular cuisines, optimal pricing, and restaurant themes for specific neighborhoods. Additionally, this dataset provides valuable information for understanding customer reviews and restaurant ratings, enabling a deeper exploration of food culture in Bengaluru.

## Dataset Information
The dataset focuses on key elements influencing restaurant success in Bengaluru:
- **Locations of restaurants and their demographic influences.**
- **Price range of food served.**
- **Restaurant types (buffets, cafes, pubs, bars, etc.).**
- **Cuisine trends in different neighborhoods.**
- **Customer reviews and ratings, offering insights into user satisfaction.**

This dataset is accurate as of March 15, 2019, and includes detailed information for over 12,000 restaurants. It has been compiled in multiple phases, offering a comprehensive view of Bengaluru's restaurant ecosystem.

## Steps of Data Collection

### Step-1: Basic Data Extraction
- Gathered restaurant URLs, names, and addresses visible on Zomato's main pages.
- URLs were saved for individual restaurant data scraping later, reducing resource usage.

### Step-2: Detailed Restaurant Data
- Extracted data for 15 attributes, including:
  - Online ordering options
  - Table booking availability
  - Ratings
  - Votes
  - Location
  - Cuisine types
  - Cost for two
  - Reviews
  - Menu items

### Step-3: Sentiment Analysis
- Conducted a sentiment analysis of customer reviews to identify user perceptions of restaurants.
- Categorized sentiments as positive, negative, or nuanced emotions (e.g., joy, anger).

### Step-4: Recommendation System
- Built a content-based recommendation system.
- Recommendations are generated based on user preferences and restaurant attributes, enabling personalized suggestions for users.

## Objectives
This project aims to:
- **Analyze Bengaluru's Restaurant Landscape**: Understand demographic preferences, cuisine popularity, and cost trends across different neighborhoods.
- **Support Aspiring Restaurateurs**: Provide insights into neighborhood-specific food preferences, helping new entrants decide their themes, menus, and pricing.
- **Predict Ratings**: Build models to predict restaurant ratings based on features like location, cuisine, and cost.
- **Perform Sentiment Analysis**: Use reviews to gauge customer satisfaction and identify key factors influencing ratings.
- **Create a Recommendation System**: Suggest restaurants based on user preferences and similar establishments.

## Key Questions Addressed
- What factors influence the success of a restaurant in Bengaluru?
- How does demography affect cuisine preferences in a neighborhood?
- Is a particular restaurant theme or type more suited for specific areas?
- What are the differences between established restaurant chains and new players?
- Can neighborhoods with similar food trends be identified and compared?

## Sections of the Project
-  **Exploratory Data Analysis (EDA)**
-  **Data Visualization**
-  **Predicting Restaurant Ratings**
-  **Sentiment Analysis of Reviews**
-  **Building a Recommendation System**

## Inspiration
Bengaluru's dynamic restaurant industry raises numerous questions for enthusiasts and entrepreneurs alike. How do restaurants sustain themselves amidst intense competition? What role does location, theme, or cuisine play in their success? How do neighborhoods influence food trends, and which types of restaurants thrive in specific areas? This project aims to answer these questions, offering actionable insights backed by data.

Whether you're a foodie planning your next meal or an entrepreneur looking to open a new restaurant, this analysis provides valuable information to enhance your dining or business experience.

[Download the dataset here](#https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants).
