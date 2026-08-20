###Google Play Store Apps - Exploratory Data Analysis

## Project Overview
This project analyzes Google Play Store apps to understand app categories, ratings, reviews, installs, prices, and user engagement.
The main goal is to find useful patterns in the data and understand what makes apps more popular.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains information about Google Play Store apps, including:
- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated

## Data Cleaning
The following steps were performed:
- Removed duplicate records
- Handled missing values
- Converted columns into suitable data types
- Cleaned Reviews, Installs, Price, and Size columns
- Converted Last Updated into datetime format
- Created an Updated Year column

## Exploratory Data Analysis
The analysis was divided into:
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
A total of 22 visualizations were created to understand the dataset.

## Key Insights
- Free apps are much more common and have more installs than paid apps.
- Most apps have ratings in the higher range.
- Reviews and installs have a strong positive relationship.
- More reviews do not necessarily mean a higher rating.
- Price has a weak relationship with installs and ratings.
- Game, Photography, and Entertainment have strong user reach.
- Social and Communication apps receive high user engagement.
- Most paid apps are in the lower price range.
- Everyone is the largest content-rating group.
- Most apps in the dataset were updated in 2018.

## Conclusion
This analysis shows that free apps dominate the Play Store and reach more users. Reviews have a stronger connection with installs than ratings or price. Overall, the project helped identify useful patterns in app popularity and user engagement.

## Project Files
- `Google_Play_Store_Raw_Data.csv` - Original dataset
- `Google_Play_Store_Cleaned.csv` - Cleaned dataset
- `Google_Play_Store_EDA.ipynb` - Complete analysis
- `visualizations/` - 22 analysis graphs
