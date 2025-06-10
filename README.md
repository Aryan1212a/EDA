# Netflix TV Shows and Movies Data Analysis

## Project Overview

This project involves performing an exploratory data analysis (EDA) on the Netflix content catalog. The goal is to uncover patterns, trends, and insights related to content distribution, geographical production, genre popularity, release trends, and content characteristics.

The analysis utilizes a dataset containing information about movies and TV shows available on Netflix, including details like title, director, cast, country, release year, rating, duration, and genre.

## Problem Statement

As a leading global streaming platform, Netflix needs to understand the composition and characteristics of its vast content library to make informed decisions about content acquisition, production, and regional strategy. The challenge is to analyze this diverse dataset to extract meaningful insights.

## Business Objectives

The key business objectives of this analysis are:

*   Identify content distribution patterns and trends.
*   Understand regional content contribution and characteristics.
*   Analyze genre popularity and evolution over time.
*   Discover opportunities for content gap filling and strategic expansion.
*   Provide data-driven recommendations for content acquisition and production strategies.

## Dataset

The dataset used for this analysis is `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv`.

**Source:**  Flixable

**Columns:**

*   `show_id`: Unique identifier for each title.
*   `type`: Content type ("Movie" or "TV Show").
*   `title`: Name of the movie or TV show.
*   `director`: Director(s) of the content.
*   `cast`: Cast members featured in the content.
*   `country`: Country (or countries) of production.
*   `date_added`: Date the content was added to Netflix.
*   `release_year`: Original release year of the content.
*   `rating`: Content rating (e.g., TV-MA, R, PG-13).
*   `duration`: Content duration (minutes for movies, seasons for TV shows).
*   `listed_in`: Genres or categories the content belongs to.
*   `description`: Brief description of the content.

## Analysis and Findings

The analysis involves:

1.  **Data Loading and Understanding:**
    *   Loading the dataset.
    *   Inspecting the first few rows, shape, and data types.
    *   Checking for duplicate and missing values.
2.  **Data Wrangling:**
    *   Handling missing values (e.g., filling with 'Unknown').
    *   Converting `date_added` to datetime.
    *   Extracting relevant time-based features (year, month).
    *   Creating a numerical duration column.
    *   Categorizing content by age.
3.  **Exploratory Data Analysis (EDA) and Visualization:**
    *   Visualizing the distribution of content types (Movies vs. TV Shows).
    *   Analyzing content addition trends over time.
    *   Identifying top content-producing countries.
    *   Examining content type distribution by country.
    *   Exploring the distribution of content by release year and decade.
    *   Analyzing movie durations and TV show seasons.
    *   Investigating content rating distribution.
    *   Identifying popular genres and directors/cast.
    *   Exploring relationships between variables through various charts (bar charts, pie charts, line charts, histograms, box plots, heatmaps).
  
  

## Tools and Libraries Used

*   Python
*   pandas
*   numpy
*   matplotlib
*   seaborn
*   plotly (express, graph\_objects)
*   gdown

## How to Run the Notebook

1.  Open the `.ipynb` file in Google Colab or a Jupyter Notebook environment.
2.  Ensure you have the necessary libraries installed (`pip install pandas numpy matplotlib seaborn plotly gdown`).
3.  Run the cells sequentially. The notebook includes code for loading the dataset using `gdown`.


## Contribution

This project was completed as an individual contribution.

## GitHub Repository

[Link to your GitHub repository]
