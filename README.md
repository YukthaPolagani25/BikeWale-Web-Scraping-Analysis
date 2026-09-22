# BikeWale Bike Market Analysis_Regex_Web_Scraping

## Project Overview

This project analyzes bike data collected from the BikeWale website using web scraping, Regular Expressions and Python.

The project follows an end-to-end data analytics workflow:

**Web Scraping → Data Cleaning → EDA → Data Visualization → Power BI Dashboard → Business Insights**

## Problem Statement

Analysis on finding out the best bikes in India based on their features.

## Objectives

- Collect bike information from the BikeWale website.
- Extract useful information using Regular Expressions.
- Clean and structure the scraped data.
- Perform Exploratory Data Analysis (EDA).
- Analyze price, rating, mileage, power and other bike features.
- Create a Power BI dashboard for interactive analysis.
- Generate business insights and recommendations.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Regular Expressions (Regex)
- Pandas
- NumPy
- Matplotlib
- Power BI

## Dataset

The final cleaned dataset contains **30 bike records** with features such as:

- Bike Name
- Rating
- Ratings Count
- Engine CC
- Mileage
- Power
- Weight
- Price
- Value Score
- Popularity Score
- Price per BHP

## Project Workflow

1. Website Selection
2. Web Scraping
3. Data Collection
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Engineering
7. Data Visualization
8. Power BI Dashboard
9. Business Insights
10. Recommendations

## Power BI Dashboard

The Power BI dashboard provides interactive analysis of:

- Total number of bikes
- Average price
- Average rating
- Average mileage
- Average engine capacity
- Bike price comparison
- Rating comparison
- Mileage comparison
- Engine CC vs Price
- Power vs Price
- Bikes by price range

Interactive slicers are provided for:

- Bike Name
- Price Range
- Rating

## Key Insights

- Commuter-oriented bikes generally show competitive mileage and lower prices.
- Higher-performance bikes generally have greater power output and higher prices.
- Bikes across different price ranges can have similar customer ratings.
- Price alone does not indicate customer satisfaction.
- Different customers may prioritize affordability, mileage, power or overall balance.

## Limitations

- The dataset represents a sample collected from the selected BikeWale listing page.
- BikeWale is a live website, so values and listings may change over time.
- Some electric bikes may not have conventional engine, mileage or power specifications.
- The comparison scores used in this project are project-defined metrics and are not official BikeWale rankings.

## Project Files

- `BikeWale_Regex_Web_Scraping_Project_Updated.ipynb` – Python web scraping, cleaning, EDA and analysis
- `BikeWale_Cleaned_Dataset.csv` – cleaned dataset
- `BikeWale_Data_Dictionary.csv` – data dictionary
- `BikeWale_Bike_Market_Analysis_Dashboard.pbix` – Power BI dashboard
- `README.md` – project documentation

## Author

**Yuktha Polagani**
