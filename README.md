# 📊 Steam Games EDA Project

## 📝 Overview
This project presents an Exploratory Data Analysis (EDA) on a curated Steam games dataset. The aim is to uncover insights about game pricing, popularity, genres, release patterns, user engagement, and market trends. Through structured data cleaning and visualizations, this project highlights key factors that influence game performance on the Steam platform.

## 🎯 Objectives
- Understand overall distribution of Steam games  
- Identify pricing trends and discount patterns  
- Explore relationships between features like user reviews, genres, and playtime  
- Analyze release year trends and market growth  
- Visualize correlations to reveal major performance drivers  

## 🗂️ Dataset
The dataset contains **1,000 cleaned Steam game records**, including:
- Game titles  
- Genres  
- Release dates  
- Positive & negative review counts  
- Price and discount  
- Average playtime  
- Tags and features  

### File Used  
`steam_games_1000_final_cleaned.csv`

## 🧹 Data Cleaning
Important preprocessing steps:
- Removed duplicates and null values  
- Standardized date formats  
- Converted price and review fields to numeric  
- Cleaned genre and tag inconsistencies  
- Extracted year-based features for time-series analysis  

## 📈 Visualizations
The project includes multiple visualizations:
- Pricing distribution  
- Top genres by game count  
- Correlation heatmap  
- Release year timeline  
- Positive vs negative reviews  
- Playtime-based popularity  

These visuals help uncover patterns such as:
- How prices vary across genres  
- Dominant categories on Steam  
- Influence of reviews on success  
- Historical growth in game releases  

## 🧠 Key Insights
- Action and Indie genres dominate the platform  
- High correlation between playtime and positive reviews  
- Consistent rise in game releases over time  
- Most games are priced below $20  
- Discounts strongly improve visibility and engagement  

## 🛠️ Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📌 Conclusion
This EDA provides meaningful insights into the Steam marketplace and factors that shape a game's performance. These findings help developers, analysts, and gamers understand trends and user behavior effectively.
