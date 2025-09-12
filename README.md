# 🎬 Group 15 Project – Movie Industry Data Analysis

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
- [Next Steps](#next-steps)  
- [Technologies Used](#technologies-used)  

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

- Cleaned missing data  
- Merged multiple sources using movie titles and release years  
- Transformed data for analysis (genres, revenue, ratings)  

---

## 🔍 Data Highlights

- The dataset includes key information on genres, release year, revenue, and ratings.  
- Multiple sources were used for reliable and enriched data.  
- Analysis was conducted using Python (pandas, matplotlib, seaborn, SQLAlchemy).  

---

## 📈 Key Findings & Visualizations

### 1. Top Genres

![Top Genres](./images/Top%20Genres.png)  

*Drama, Comedy, and Documentary are the most common genres in the dataset, highlighting popular content creation areas. However, high frequency does not necessarily translate to box office profitability, showing that volume alone isn’t the best indicator of commercial success.*

---

### 2. Average IMDB Rating by Year

![Average IMDB Rating By Year](./images/Average%20IMDB%20Rating%20By%20Year.png)  

*IMDB ratings have remained relatively stable over the years, with a slight upward trend in recent times. This suggests consistent audience perception of movie quality, despite shifts in industry trends and releases.*

---

### 3. Balance Between Ratings and Revenue

![Balance Ratings vs Revenue](./images/Balance%20Ratings%20vs%20Revenue.png)  

*Some genres manage to balance both audience ratings and box office revenue successfully. These “sweet spot” genres represent ideal investment opportunities, blending critical acclaim with financial viability.*

---

### 4. Box Office vs IMDB Ratings (Scatter Plot)

![Box Office VS IMDB Ratings Scatter Plot](./images/Box%20Office%20VS%20IMDB%20Ratings%20Scatter%20Plot.png)  

*This scatter plot reveals that high ratings don’t always guarantee high box office performance. Other factors such as marketing, distribution, and franchise popularity likely play significant roles in financial outcomes.*

---

### 5. IMDB Ratings vs Worldwide Gross Revenue

![IMDB Ratings Vs Worldwide Gross Revenue](./images/IMDB%20Ratings%20Vs%20Worldwide%20Gross%20Revenue.png)  

*The weak correlation between ratings and gross revenue indicates that audience approval is just one of many variables influencing commercial success. This insight highlights the need for multifaceted strategies beyond simply making “critically acclaimed” movies.*

---

### 6. Top 10 Studios by Worldwide Gross

![Top 10 Studios By Worldwide Gross](./images/Top%2010%20Studios%20By%20Worldwide%20Gross.png)  

*The dominance of studios like Warner Bros and Disney suggests that established distribution channels, brand loyalty, and franchise portfolios significantly contribute to box office success. New entrants must consider partnerships or strong marketing to compete.*

---

### 7. Top Genres Balancing Ratings and Revenue

![Top Genres Balancing Ratings and Revenue](./images/Top%20Genres%20Balancing%20Ratings%20and%20Revenue.png)  

*Action, Adventure, and Animation genres perform well both critically and financially, making them prime candidates for investment. Their global appeal, especially family-friendly Animation, provides sustainable revenue streams.*

---

### 8. Worldwide Gross by Year

![Worldwide Gross by Year](./images/Worldwide%20Gross%20by%20Year.png)  

*Trends in global revenue reveal industry growth patterns and dips, with notable peaks around blockbuster release years. Understanding these cycles can aid in strategic timing of movie launches.*

---

## 💡 Recommendations

- **Invest in Action, Adventure, and Animation genres:** These genres show strong performance both in revenue and audience approval, offering the best balance of profitability and critical success. Their broad appeal, particularly Animation’s family-friendly nature, ensures stable long-term revenue.

- **Prioritize mid-to-high budget films with strong pre-release marketing:** Budget correlates with box office success, but marketing plays a crucial role in attracting audiences. Well-funded marketing campaigns paired with genre choice can maximize returns.

- **Avoid niche genres with low ratings and revenue unless targeting specific markets:** Genres like documentaries appeal to niche audiences and garner critical acclaim but usually don’t generate large revenues. Invest here for brand prestige and awards, not direct profit.

- **Study and emulate top-performing studios:** Established studios succeed through franchise-building, effective distribution, and brand loyalty. New studios should build strong IP (intellectual property) and seek strategic partnerships to increase market reach.

- **Balance quality with commercial appeal:** While critical acclaim is valuable, financial success depends on multiple factors like marketing, timing, and franchise power. Ratings alone should not dictate production decisions.

---

## 🧾 Conclusion

Our analysis provides a data-driven foundation for entering the film industry. While genre and budget play major roles, success also depends on timing, marketing, and execution. Using these insights, the company can make informed decisions on the types of films to develop and distribute.

A balanced approach focusing on profitable blockbuster genres complemented by select prestige films will maximize both revenue and brand reputation.

---

## 🚀 Next Steps

1. **Expand dataset and refine analysis:** Incorporate more recent data, international markets, and streaming platform revenues to deepen insights.

2. **Perform predictive modeling:** Use machine learning to forecast box office success based on budget, genre, cast, and marketing spend.

3. **Investigate marketing and release timing:** Analyze impact of marketing budgets and seasonal release windows on revenue.

4. **Develop franchise potential metrics:** Identify which movies have the best potential to launch or expand lucrative franchises.

5. **Conduct competitor benchmarking:** Study competitor studios’ strategies in depth to identify partnership and differentiation opportunities.

6. **Engage with domain experts:** Collaborate with film industry professionals to validate data findings and align business strategies.

---

## 🛠️ Technologies Used

- Python (pandas, numpy, seaborn, matplotlib)  
- Jupyter Notebooks  
- SQLite / SQLAlchemy  
- Git & GitHub  
- VS Code  

