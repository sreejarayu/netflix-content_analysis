# netflix-content_analysis
Netflix content analysis project using Python, Pandas, and Power BI to explore content trends, genres, and global production patterns.
## Dashboard Preview
<img width="1316" height="734" alt="Screenshot 2026-03-12 230234" src="https://github.com/user-attachments/assets/9b8f70d5-091e-4667-8473-b5a291f0d90f" />
# Netflix Content Strategy Analysis

## Project Overview

This project analyzes Netflix's content catalog to understand trends in content distribution, genre popularity, geographic production, and catalog growth over time. The goal is to extract insights that can help guide content acquisition and production strategies.

Using Python for data cleaning and exploratory analysis and Power BI for visualization, this project demonstrates a complete data analytics workflow from raw data to an interactive dashboard.

---

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* Power BI
* Data Visualization

---

## Dataset

The dataset contains metadata about Netflix movies and TV shows including:

* Title
* Content Type (Movie / TV Show)
* Director and Cast
* Country of Production
* Release Year
* Date Added to Netflix
* Rating
* Duration
* Genre
* Description

---

## Data Cleaning & Preparation

The following steps were performed to prepare the dataset for analysis:

* Handled missing values in country, rating, and duration fields
* Converted date columns to proper datetime format
* Extracted **year_added** for time-based analysis
* Split duration into:

  * **movie_duration_min**
  * **tv_seasons**
* Removed rows with unknown country values to ensure accurate geographic analysis

---

## Key Business Questions

The analysis focuses on answering the following questions:

1. What is the distribution of Movies vs TV Shows on Netflix?
2. How has Netflix's content catalog grown over time?
3. Which countries produce the most Netflix content?
4. What genres are most common on the platform?
5. What ratings dominate Netflix content?
6. What is the distribution of movie durations?
7. How many seasons do Netflix TV shows typically have?

---

## Key Insights

* Movies dominate Netflix's content catalog compared to TV shows.
* Netflix significantly expanded its content library after **2016**.
* The **United States** produces the majority of Netflix content.
* **Drama and international movies** are among the most common genres.
* Most Netflix movies fall between **90–120 minutes** in length.
* The majority of Netflix TV shows have **1–3 seasons**.

---

## Dashboard Features

The Power BI dashboard includes:

### KPI Metrics

* Total Titles
* Total Movies
* Total TV Shows
* Total Countries

### Visualizations

* Netflix Content Growth Over Time
* Movies vs TV Shows Distribution
* Top Content Producing Countries
* Top Genres on Netflix
* Content Ratings Distribution
* Movie Duration Distribution
* TV Show Season Distribution

## Project Structure

netflix-content-analysis
│
├── data
│   cleaned_netflix_data.xlsx
│
├── notebook
│   netflix_analysis.ipynb
│
├── powerbi
│   netflix_content_dashboard.pbix
│
├── images
│   dashboard_preview.png
│
└── README.md

---

## Future Improvements

Possible future enhancements include:

* Content recommendation analysis
* Predictive modeling for content popularity
* Sentiment analysis of movie descriptions
* Advanced genre clustering

---

## Author

Lucky

This project is part of my **Data Analytics Portfolio**, demonstrating skills in data cleaning, exploratory analysis, and dashboard development.
