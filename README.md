Netflix Movies & TV Shows Data Analysis
Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to understand content distribution, popular genres, top countries, directors, and movie duration patterns.
The analysis focuses on data cleaning, univariate analysis, and visualization using Python.

Dataset Information

File Name: netflix_titles.csv

Description:
The dataset contains details of Netflix content including:

Title

Type (Movie / TV Show)

Director

Cast

Country

Date Added

Rating

Duration

Listed Categories (Genres)

Technologies & Libraries Used

Python

Pandas – Data loading and preprocessing

Matplotlib – Data visualization

Seaborn – Statistical visualizations

NumPy – Numerical operations

Analysis Workflow
1. Data Loading

Imported required Python libraries.

Loaded the Netflix dataset using pandas.read_csv().

Displayed initial rows to understand data structure and column types.

Purpose:
To familiarize with the dataset and identify relevant columns for analysis.

2. Missing Value Handling

Checked missing values across all columns.

Removed rows containing null values in key columns:

director

cast

country

date_added

rating

duration

Purpose:
To improve data quality and ensure reliable analysis results.

3. Content Type Distribution

Analyzed the type column to compare Movies vs TV Shows.

Visualized the distribution using a bar chart.

Insight Objective:
To understand whether Netflix’s catalog is dominated by Movies or TV Shows.

4. Top 10 Content Categories

Analyzed the listed_in column.

Identified the top 10 most frequent content categories.

Visualized results using a horizontal bar chart.

Insight Objective:
To identify the most popular genres available on Netflix.

5. Top 10 Content Producing Countries

Counted the number of titles per country.

Sorted and visualized the top 10 countries.

Insight Objective:
To understand which countries contribute the most content to Netflix.

6. Top 10 Directors

Analyzed the director column.

Identified directors with the highest number of titles.

Visualized the top 10 directors.

Insight Objective:
To identify key contributors in Netflix’s content creation.

7. Movie Duration Analysis

Filtered dataset to include only Movies.

Extracted numeric movie duration (in minutes).

Converted duration values into integers.

Visualized the distribution using a histogram.

Insight Objective:
To analyze typical movie length patterns on Netflix.

8. Top Titles by Duration Frequency

Analyzed frequently occurring title-duration combinations.

Visualized the top 10 titles based on duration occurrence.

Insight Objective:
To identify notable duration patterns among popular titles.

Key Insights

Movies significantly outnumber TV Shows on Netflix.

Drama and International content dominate the platform.

The United States is the largest content contributor.

A small group of directors accounts for a large share of content.

Most Netflix movies fall within a standard duration range (90–120 minutes).

How to Run This Project

Clone the repository

Install required libraries:

pip install pandas matplotlib seaborn numpy


Place netflix_titles.csv in the project directory

Run the Python script or Jupyter Notebook

Project Learnings

Practical experience in data cleaning and preprocessing

Handling missing values in real-world datasets

Creating effective data visualizations

Conducting structured EDA for business insights

Author

Deep Roy
Aspiring Data Analyst | Python | SQL | Data Visualization
