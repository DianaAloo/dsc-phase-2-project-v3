<img width="611" height="436" alt="image" src="https://github.com/user-attachments/assets/ba7d23a5-7af3-4968-9c89-e0e17d46fc35" />## 🎬 Phase 2 Project – Movie Industry Data Analysis
# Overview

This project explores movie industry data to generate actionable insights for a business stakeholder interested in launching a new movie studio. The analysis identifies which types of films perform best at the box office, providing recommendations that can guide investment and content strategy.

The project uses exploratory data analysis (EDA) techniques, combining data from multiple sources such as Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.
# Business Understanding

# Business Problem:
Big companies are finding success by producing original video content. Our company wants to enter this space but lacks expertise in making movies. The goal is to identify what types of films are most successful at the box office so the new movie studio can make informed decisions.

Key Questions:

What genres and film types are consistently performing well?

How do budgets and revenue relate to success?

What trends should guide the studio’s content creation strategy?
# Data Understanding & Analysis
Data Sources:

Box Office Mojo (bom.movie_gross.csv.gz)

IMDB (SQLite Database) (im.db) – Focused on movie_basics and movie_ratings tables

Rotten Tomatoes, TheMovieDB, The Numbers (additional context and enrichment)

# Data Highlights:

Movies dataset includes information on genres, release year, revenue, and ratings.

Integrated data required cleaning, merging, and transformation to align different formats.

Analysis was conducted using Python (pandas, matplotlib, seaborn, SQLite).
# Key Findings & Visualizations
1. Genre Performance

Visualization: This bar chart provides insights into the dominant genres in the dataset, helping us understand which types of movies are most commonly represented.



Finding: Action and Adventure movies generate the most revenue. Drama is the most common genre but earns significantly less per movie.
