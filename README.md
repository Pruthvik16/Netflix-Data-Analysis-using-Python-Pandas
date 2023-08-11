## Netflix Dataset Analysis

In this repository, I present an in-depth analysis of the Netflix dataset using Python's pandas library. By harnessing the power of pandas functions, I delve into various aspects of the dataset to extract meaningful insights and answer intriguing questions about the content available on Netflix.

### Project Overview

The main objective of this project is to explore and analyze the Netflix dataset, shedding light on its various attributes and trends. By leveraging pandas functions and Seaborn visualizations, I unravel valuable information about the dataset's content, release years, directors, genres, and more.

### Methodology

Throughout this project, I extensively utilize pandas functions to perform a wide range of data manipulation tasks:

- **Exploratory Data Analysis:** Leveraging `head()` and `tail()` functions to provide quick glimpses into the dataset.
- **Data Dimensions:** Utilizing `shape`, `size`, and `columns` functions to gain insights into the dataset's structure.
- **Data Types and Information:** Employing `dtypes` and `info()` functions to understand column data types and summary statistics.
- **Categorical Insights:** Utilizing functions like `value_counts()`, `unique()`, and `nunique()` to examine categorical data distribution.
- **Duplicate Detection:** Detecting and handling duplicate records through the `duplicated()` function.
- **Handling Missing Data:** Identifying and managing null values using `isnull()` and `dropna()` functions.
- **Filtering and Search:** Applying `isin()` and `str.contains()` functions for targeted data retrieval.
- **Date-Time Conversion:** Transforming date-time data using `to_datetime()` for consistent formatting.
- **Aggregation and Grouping:** Using `groupby()` to aggregate data and perform analyses.
- **Visualization:** Crafting insightful bar graphs using Seaborn's `countplot()`.

### Key Tasks

Within this project, I tackle essential tasks and questions related to the dataset:

1. Identifying and eliminating duplicate records from the dataset.
2. Visualizing null values through a heatmap for a comprehensive understanding.
3. Extracting the Show ID and Director of the TV show 'House of Cards'.
4. Uncovering the peak year for TV show and movie releases using a bar graph.
5. Visualizing the distribution of movies and TV shows through a bar plot.
6. Listing movies released exclusively in the year 2000.
7. Displaying titles of TV shows exclusively released in India.
8. Highlighting the top 10 directors who significantly contribute to Netflix content.
9. Filtering records based on specific criteria such as genre or country.
10. Counting instances where Tom Cruise appears in movies/shows.
11. Analyzing the distribution of Netflix's content ratings.
12. Determining the maximum duration of movies/shows available on Netflix.
13. Identifying the country with the highest number of TV shows.
14. Sorting the dataset based on release year.
15. Extracting records with specific category and type combinations.
