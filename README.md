# Data Visualization Tableau

**Topic:** Understanding Movie Trends through Data  

---

## Dataset Description

**Dataset Source:** [Kaggle - Movie Metadata CSV](https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv)  
**Description:**  
This dataset, sourced from IMDb via Kaggle, contains data on over 5000 movies, with 28 features per film. It includes information such as movie titles, directors, actors, genres, budgets, and more. Below is a brief description of key features:

- **movie_title:** Title of the movie  
- **color:** Indicates if the movie is black and white or in color  
- **num_critic_for_reviews:** Number of critic reviews  
- **movie_facebook_likes:** Facebook likes for the movie  
- **duration:** Movie duration (minutes)  
- **director_name:** Principal director's name  
- **gross:** Movie gross revenue (USD)  
- **genres:** Sub-genres  
- **budget:** Production budget (varied currencies)  
- **imdb_score:** IMDb user rating  

## Intended Audience

The visualizations target **movie production studios**, aiming to provide insights like:
- Types of movies that yield higher profits.
- Directors and actors who gross the most revenue.
- The correlation between ratings and gross revenue.

## Data Exploration

### Goals:
- Discover trends between key metrics (e.g., gross revenue, genres, ratings).
- Provide studios with insights into film success factors.

### Dashboard Link:
[Tableau Dashboard - Part 1](https://public.tableau.com/app/profile/oluwatobi.omole/viz/Assignment1Part1DataExploaration/Dashboard1?publish=yes)

### Breakdown of Visualizations:

1. **Interactive Summary Table**  
   Displays average statistics (e.g., budget, duration) with filters for directors, actors, and genres.

2. **Tree Map (Genres and Gross Revenue)**  
   - Color-coded by average gross (red = high, blue = low).  
   - Sorted by IMDb ratings to identify popular and profitable genres.

3. **Bar Chart (Lead Actor Gross Revenue)**  
   - Shows actors’ cumulative gross with color-coded average IMDb ratings.

4. **Scatter Plot (Gross Revenue vs IMDb Ratings)**  
   - Highlights the relationship between movie ratings and revenue.

## Data Insights

### Goals:
- Explore additional dimensions for actionable insights.
- Understand factors affecting movie budgets and returns.

### Dashboard Link:
[Tableau Dashboard - Part 2](https://public.tableau.com/app/profile/oluwatobi.omole/viz/Assignment1Part2DataInsights/Dashboard1?publish=yes)

### Breakdown of Visualizations:

1. **Bar Chart (Lead Actor Budget)**  
   - Shows actors' cumulative budgets with average returns.

2. **Tree Map (Genres and Budgets)**  
   - Color-coded by average budget, identifying costly genres like Action and Animation.

3. **Bar Chart (Director Budget and Returns)**  
   - Highlights directors with high budgets and their average returns.

---

## Key Insights

- **Genres:**  
  Action movies are the most expensive, while Film Noir is the cheapest.  
- **Directors:**  
  Steven Spielberg and Peter Jackson create high-budget films.  
- **Actors:**  
  Johnny Depp frequently stars in expensive films with high gross returns.

### Example Filters Applied:
1. **Director Filter (Steven Spielberg):**  
   - Directed 33 films grossing over $6 billion.  
   - Works frequently with Harrison Ford, grossing ~$1 billion together.  
   - Family movies yield the highest revenue, while Biographies receive higher ratings.

2. **Genre Filter (Action Movies):**  
   - Michael Bay leads in cumulative budget for Action films.  
   - Action movies have the darkest red hues, denoting high costs.

---

### Conclusion

This analysis provides movie studios with critical insights into the financial and qualitative aspects of filmmaking. Studios can leverage these findings to make data-driven decisions regarding film production strategies.

---
