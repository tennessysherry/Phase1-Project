# **Movie Data Exploration

## Overview
This is a comprehensive movie data analysis and visualization task, leveraging a Jupyter Notebook environment. It involves cleaning and preprocessing a dataset, performing exploratory data analysis (EDA), and visualizing the findings using various plots and charts. The objective is to uncover insights and patterns within the data, facilitating informed decision-making.

## Introduction
This project demonstrates how to perform a thorough data analysis using Python. The primary tools and libraries used include Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for any necessary machine learning tasks. The dataset used in this analysis includes various attributes that we will explore to gain insights.

## Setup and Installation
To start this project, ensure you have the following installed:
- Python 3.8 or above
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

You can install the required libraries using pip:

"pip install pandas matplotlib seaborn scikit-learn"

## **Data Cleaning and Preprocessing**

1. **Data Loading:**
   - Loaded four datasets:
     - Movie gross data
     - Movie reviews data
     - Movie budget data
     - Movie information data
2. **Data Cleaning:**
   - Removed duplicate rows.
   - Handled missing values by either dropping rows or imputing with the mean or mode.
   - Converted data types to appropriate formats.
3. **Data Merging:**
   - Created a common identifier column ('id') for each dataset.
   - Merged the four datasets into a single dataframe.
4. **Data Transformation:**
   - Created a new 'revenue' column by summing 'domestic_gross' and 'foreign_gross'.
   - Dropped unnecessary columns.

## **Exploratory Data Analysis**

1. **Descriptive Statistics:**
   - Calculated descriptive statistics for the numerical columns.
2. **Revenue by Rating:**
   - Calculated the average revenue for each rating.
   - Visualized the results as a bar plot.
3. **Top Critic Reviews:**
   - Counted the occurrences of each value in the 'top_critic' column.
   - Visualized the results as a bar plot and a pie chart.
4. **Revenue Over Time:**
   - Plotted the revenue over time by release year as a line plot.
5. **Rating Distribution:**
   - Plotted the distribution of ratings as a histogram.
6. **Original Language:**
   - Counted the occurrences of each value in the 'original_language' column.
   - Visualized the results as a bar plot.
7. **Vote Average vs Revenue:**
   - Plotted the 'vote_average' against 'revenue' as a scatter plot.
8. **Vote Average Distribution:**
   - Plotted the distribution of 'vote_average' as a histogram.
9. **Freshness:**
   - Counted the occurrences of each value in the 'fresh' column.
   - Visualized the results as a bar plot and a pie chart.
10. **Highest and Lowest Revenue Movies:**
    - Identified the top and bottom 5 movies by revenue.
    - Visualized the results as bar plots.
11. **Correlation Matrix:**
    - Calculated the correlation matrix for the numerical columns.
    - Visualized the results as a heatmap.

## **Conclusions**

- There is a positive correlation between 'vote_average' and 'revenue'.
- Movies with higher ratings tend to have higher revenues.
- There is a large number of movies with no top critic reviews.
- The average revenue for movies has increased over time.
- English-language movies are more popular than movies in other languages.
- The top 10 highest-grossing movies are a mix of genres.

## **Recommendations**

- Further investigate the relationship between 'vote_average' and 'revenue'.
- Explore the reasons for the increase in average revenue over time.
- Conduct a more detailed analysis of the different genres and their impact on revenue.
- Use the insights from this analysis to make informed decisions about movie selection and marketing.
