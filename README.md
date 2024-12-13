# data-analytics-assignment
Analysis of user behavior, cooking preferences, and order trends with Python


Project Overview
This project analyzes user activity, cooking sessions, and order details from a cooking platform. The goal is to derive actionable insights and provide recommendations based on demographic trends, popular dishes, and session dynamics.

Features
*Data Integration: Combines data from three datasets: User Details, Cooking Sessions, and Order Details.
*Data Cleaning: Handles missing values and standardizes column names for consistency.
*Exploratory Data Analysis:
     Identifies the top 10 popular dishes.
     Analyzes the relationship between cooking sessions and order frequency.
     Examines demographic factors influencing user behavior.
*Visualization: Exports charts and insights into an Excel file with embedded visualizations.
*Recommendations: Generates business strategies based on analysis findings.
Datasets
*User Details: Contains user demographic information (e.g., User ID, Age, Location).
*Cooking Sessions: Records session details (e.g., Session ID, Session Start/End Times).
*Order Details: Tracks order information (e.g., Order ID, Dish Name, Amount, Rating).
Analysis Workflow
-Load Data: Import datasets from an Excel file.
*Clean Data:
   Handle missing values using forward-fill.
   Standardize column names to a consistent format.
*Merge Datasets: Integrate datasets for combined analysis.
*Insights Extraction:
*Popular Dishes: Rank dishes by frequency of orders.
*Age Group Behavior: Analyze order patterns across age groups.
*Sessions and Orders Correlation: Understand how cooking sessions influence orders.

Export Results:
Save analysis and visualizations to an Excel file with dynamic charts.

Key Insights
The top 10 most popular dishes are highlighted, suggesting strong user preferences.
A correlation exists between the number of cooking sessions and orders per user.
Certain age groups show higher engagement, with varying order frequencies.

Business Recommendations
Promote Popular Dishes: Focus on top-ranked dishes in marketing campaigns.
Encourage Sessions: Incentivize more frequent sessions for less active users.
Targeted Marketing: Develop personalized strategies for high-performing demographics.

Output Files
Analytics_Insights.xlsx:
Contains:
 Table of popular dishes.
 Orders by age group.
 Includes visual charts for easy interpretation.
Charts:
 Column chart for top 10 popular dishes.
 Bar chart for orders by age group.

Running the Project
Ensure the dataset file (Assignment.xlsx) is in the working directory.
Run the Python script.


IMP  "While processing the Dish Name column in the dataset, an error was encountered that required manual correction in Excel"
