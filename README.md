# 🎬 Phase 2 Project – Movie Industry Data Analysis

## 👥 Group 15 Members
- Diana Aloo  
- Catherine Kaino  
- Sylvia Wambui  
- Vincent Buluma  

---

This project explores movie industry data to generate actionable insights for business stakeholders interested in launching a new movie studio. The analysis identifies which types of films perform best at the box office, providing recommendations that can guide investment and content strategy decisions.

We utilized exploratory data analysis (EDA) techniques, combining data from multiple sources including Box Office Mojo, IMDB, Rotten Tomatoes, TheNumbers, and TheMovieDB.

---

## 📌 Table of Contents

- [Business Understanding](#business-understanding)  
- [Data Understanding & Analysis](#data-understanding--analysis)  
- [Data Highlights](#data-highlights)  
- [Key Findings & Visualizations](#key-findings--visualizations)  
- [Recommendations](#recommendations)  
- [Conclusion](#conclusion)  
- [Technologies Used](#technologies-used)  
- [Next Steps](#next-steps)  

---

## 💼 Business Understanding

### Business Problem:
Big companies in media are seeking success by producing original video content. Our company wants to enter this space but lacks experience in making movies. The goal is to identify what types of films are most successful at the box office so the new movie studio can make informed decisions.

### Key Questions:
- What genres and film types are consistently performing well?  
- How do budgets and revenues relate to success?  
- What trends should guide the studio’s content creation strategy?

---

## 📊 Data Understanding & Analysis

### Data Sources:
- **Box Office Mojo:** Box office revenue  
- **IMDB:** Ratings and movie metadata  
- **The Numbers & TheMovieDB:** Budget and revenue data  
- **Rotten Tomatoes:** Ratings and critic reviews  

### Data Processing:
- Cleaned missing or inconsistent data  
- Merged multiple sources using movie titles and release years  
- Transformed data for clarity: normalized revenue, grouped genres, handled outliers  
- Visualized using plots: bar charts, scatter plots, trend lines  

---

## 🔍 Data Highlights

- The dataset includes key information on genres, release year, budget, revenue, and ratings.  
- Multiple sources were used to enrich the data, reducing bias from any single source.  
- Outliers (very high or low revenue / rating) were considered and handled.  
- Analysis was done using Python (pandas, numpy), with visualizations through seaborn & matplotlib.  

---

## 📈 Key Findings & Visualizations

### 1. Top Genres  
![Top Genres](top_genres.png)  
*Drama, Comedy, and Documentary are the most common genres. However, frequency does not always equate to profitability.*

---

### 2. Average IMDB Rating by Year  
![Average IMDB Rating By Year](avg_imdb_rating_by_year.png)  
*Viewer ratings have generally remained stable over time, with slight increases in recent years.*

---

### 3. Balance Between Ratings and Revenue  
![Balance Ratings vs Revenue](balance_ratings_vs_revenue.png)  
*Some genres achieve both high ratings and high revenue — these are ideal targets for production.*

---

### 4. Box Office vs IMDB Ratings (Scatter Plot)  
![Box Office VS IMDB Ratings Scatter Plot](box_office_vs_imdb_scatter.png)  
*Highly rated movies do not always perform well at the box office, suggesting other factors like marketing and genre affect revenue.*

---

### 5. IMDB Ratings vs Worldwide Gross Revenue  
![IMDB Ratings Vs Worldwide Gross Revenue](imdb_vs_worldwide_gross.png)  
*There is some correlation between ratings and revenue, but it’s not strong enough to rely on ratings alone for success prediction.*

---

### 6. Top 10 Studios by Worldwide Gross  
![Top 10 Studios By Worldwide Gross](top_studios_worldwide_gross.png)  
*Top studios like Warner Bros and Disney dominate global earnings — suggesting strong distribution and branding matter.*

---

### 7. Top Genres Balancing Ratings and Revenue  
![Top Genres Balancing Ratings and Revenue](top_genres_balancing_ratings_revenue.png)  
*This combined bar-and-line chart highlights the top 5 genres that best balance audience approval (ratings) and financial performance (revenue). The blue bars represent average ratings, while the red line shows average worldwide revenue (in millions USD).*

- Sci-Fi leads in revenue (~$339M) but with slightly below-average ratings (~6.45). Its strength lies in blockbuster franchises and mass-market appeal.  
- Animation shows a strong balance, achieving both high revenues (~$312M) and solid ratings (~6.7). This genre is especially attractive due to its family-friendly appeal and global reach.  
- Adventure films also perform well commercially (~$323M) with decent ratings (~6.5), making them a reliable revenue driver.  
- Documentary films receive the highest average ratings (~7.29) but much lower revenue (~$67M), signaling strong critical acclaim but niche market reach.  
- Sports films combine above-average ratings (~6.9) with moderate revenue (~$123M), offering room for future growth with strategic marketing.  

📌 *Insight:* This visualization reinforces our earlier findings:  
Animation, Sci-Fi, and Adventure are the most profitable genres that also maintain respectable ratings, making them ideal for large-scale investment. Documentary and Sport genres, while less lucrative, contribute to brand reputation, critical prestige, and niche audience loyalty. Together, these genres provide a balanced portfolio strategy — driving

---

