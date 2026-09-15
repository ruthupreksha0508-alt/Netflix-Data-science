# Netflix Movies and TV Shows - Data Analysis

## Project Overview

This project analyzes the Netflix Movies and TV Shows dataset to
identify patterns and trends in Netflix content.

The analysis covers content types, release years, countries,
categories, ratings, movie durations, and TV show seasons.

## Objectives

- Understand the structure of the Netflix dataset
- Clean and prepare the data for analysis
- Analyze Movies vs TV Shows
- Examine release-year trends
- Identify countries with the most Netflix titles
- Identify the most common content categories
- Analyze content ratings
- Analyze movie durations
- Analyze TV show seasons

## Dataset

The dataset used in this project is the Netflix Movies and TV Shows
dataset.

It contains information such as:

- Title
- Content type
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Categories
- Description

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

## Data Cleaning

The dataset was cleaned by:

- Handling missing values
- Converting the `date_added` column to datetime format
- Correcting incorrect values found in the `rating` column
- Preserving genuinely unavailable information as `Unknown`

## Exploratory Data Analysis

The following analyses were performed:

1. Movies vs TV Shows
2. Release Year Analysis
3. Movies vs TV Shows Over Time
4. Top Countries
5. Top Categories
6. Content Ratings
7. Movie Duration
8. TV Show Seasons

## Key Findings

- Movies account for approximately 69.6% of the titles in the dataset.
- TV Shows account for approximately 30.4%.
- The number of titles increases substantially in the more recent
  release years.
- Movies outnumber TV Shows across most of the years analyzed.
- The United States is the country most frequently associated with
  Netflix titles, followed by India and the United Kingdom.
- International Movies, Dramas, and Comedies are among the most common
  categories.
- TV-MA is the most frequently occurring content rating.
- The average movie duration is approximately 99.6 minutes.
- The median movie duration is 98 minutes.
- Most TV Shows have one season.

## Visualizations

The project includes visualizations for:

- Movies vs TV Shows
- Top 10 Countries
- Top 10 Categories
- Top 10 Ratings
- Movie Duration Distribution
- TV Show Seasons

## Project Structure

```text
Netflix-Data-Science/
│
├── data/
│   ├── netflix_titles.csv
│   └── netflix_cleaned.csv
│
├── notebooks/
│   └── netflix_eda.ipynb
│
├── visualizations/
│   ├── movies_vs_tv_shows.png
│   ├── top_10_countries.png
│   ├── top_10_genres.png
│   ├── top_10_ratings.png
│   ├── movie_duration_distribution.png
│   └── tv_show_seasons.png
│
├── src/
│
└── README.md