# 🎬 Phase 2 Project – Movie Industry Data Analysis

# Group 15 Members
1. Diana Aloo
2. Catherine Kaino
3. Sylvia Wambui
4. Vincent Buluma

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

Drama, Comedy, and Documentary are the most common genres. However, frequency does not always equate to profitability.

---

### 2. Average IMDB Rating by Year

![Average IMDB Rating By Year](./images/Average%20IMDB%20Rating%20By%20Year.png)

Viewer ratings have generally remained stable, with slight increases in recent years.

---

### 3. Balance Between Ratings and Revenue

![Balance Ratings vs Revenue](./images/Balance%20Ratings%20vs%20Revenue.png)

Some genres achieve both high ratings and high revenue — these are ideal targets for production.

---

### 4. Box Office vs IMDB Ratings (Scatter Plot)

![Box Office VS IMDB Ratings Scatter Plot](./images/Box%20Office%20VS%20IMDB%20Ratings%20Scatter%20Plot.png)

Highly rated movies do not always perform well at the box office, suggesting other factors (e.g. marketing, genre) affect revenue.

---

### 5. IMDB Ratings vs Worldwide Gross Revenue

![IMDB Ratings Vs Worldwide Gross Revenue](./images/IMDB%20Ratings%20Vs%20Worldwide%20Gross%20Revenue.png)

There is some correlation between ratings and revenue, but it’s not strong enough to rely on ratings alone for success prediction.

---

### 6. Top 10 Studios by Worldwide Gross

![Top 10 Studios By Worldwide Gross](./images/Top%2010%20Studios%20By%20Worldwide%20Gross.png)

Top studios like Warner Bros and Disney dominate global earnings — suggesting strong distribution and branding matter.

---

### 7. Top Genres Balancing Ratings and Revenue

![Top Genres Balancing Ratings and Revenue](./images/Top%20Genres%20Balancing%20Ratings%20and%20Revenue.png)

Action, Adventure, and Animation perform well both critically and financially — optimal for investment.

---

### 8. Worldwide Gross by Year

![Worldwide Gross by Year](./images/Worldwide%20Gross%20by%20Year.png)

Global revenue trends reveal industry growth patterns and dips, helpful for strategic planning.

---

## 💡 Recommendations

- **Invest in Action, Adventure, and Animation genres** — they consistently perform well in both ratings and revenue.
- **Prioritize mid-to-high budget films** in these genres with strong pre-release marketing.
- **Avoid niche genres** that perform poorly both critically and commercially unless targeting specific markets (e.g. documentaries).
- **Study top-performing studios** to understand their distribution and branding strategies.

---

## 🧾 Conclusion

Our analysis provides a data-driven foundation for entering the film industry. While genre and budget play major roles, success also depends on timing, marketing, and execution. Using these insights, the company can make informed decisions on the types of films to develop and distribute.

---

## 🛠️ Technologies Used

- Python (pandas, numpy, seaborn, matplotlib)
- Jupyter Notebooks
- SQLite / SQLAlchemy
- Git & GitHub
- VS Code

