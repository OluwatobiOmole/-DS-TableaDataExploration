# Data Visualization Tableau

**Topic:** Understanding Movie Trends through Data  
This project will use Tableau to visualize key insights from a dataset of movies.

---

## Dataset Description

**Dataset Source:** [Kaggle - Movie Metadata CSV](https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv)  
**Description:**  
TThe dataset under analysis and scrutiny is a collection of various movies from different creative backgrounds and countries from the website IMDB.com sourced from Kaggle.com. IMDB is a renowned website for its appraisal of movies and collection of several key metrics on films, from essential features like movie runtime to budget, total gross profit, and many other interesting attributes about movies. Therefore, it is a rich enough dataset to perform an extensive investigation as it contains over 5000 movies with 28 features on each film. The features are explained briefly below to give a brief understanding of the kind of information present in the data set. 

- **movie_title:** Title of the movie  
- **color:** Indicates if a movie is black and white or in color
- **num_critic_for_reviews:** Number of critic reviews for the movie
- **movie_facebook_likes:** Number of Facebook likes for movie
- **duration:** Duration of a movie (minutes)
- **director_name:** Name of the principal director of a movie
- **director_facebook_likes:** Number of Facebook likes for a director
- **actor_3_name:** Indicates name of the 3rd leading actor of a movie
- **actor_3_facebook_likes:** Number of Facebook likes for actor 3rd leading actor
- **actor_2_name:** Indicatesname of the 2nd leading actor of a movie
- **actor_2_name:** Indicatesname of the 2nd leading actor of a movie
- **actor_2_facebook_likes:**  Number of Facebook likes for actor 2nd leading actor
- **actor_1_name:**  Indicates the name of the leading actor of a movie
- **actor_1_facebook_likes:**  Indicates the name of the leading actor of a movie
- **gross:**  Amount a movie grossed (USD)
- **genres:**  Sub-genres of a movie
- **num_voted_users:**  Number of users who votes for a movie
- **cast_total_facebook_likes:**  Number of Facebook likes for the entire cast of a movie
- **facenumber_in_poster:**  Number of actor’s faces on a movie poster
- **plot_keywords:**  Key plot words associated with a movie
- **movie_imdb_link:**  Link to the IMDB movie page
- **num_user_for_reviews:**  Number of user-generated reviews for the movie
- **language:**  Language of a movie
- **country:**  Name of the country of origin of the movie
- **content_rating:**  Age rating of a movie
- **budget:**  Amount of money spent in production per movie (not always in USD)
- **title_year:**  Year in which a film was released
- **imdb_score:**  User-generated rating for the movie

## Intended Audience

As a visualization designer, the dashboards created are aimed at movie production studios to help them identify important information about movies. Information like what types of movies are more profitable, which directors or actors gross high amounts of movies, whether movie ratings are important to film success, and other important insights. These insights will guide these movie studios into what type of movies to invest in and perhaps what kind of actors and directors to employ.

## Data Exploration

In data exploration, I am looking at finding trends between interesting metrics in the dataset. Focus is placed on metrics that could give information about the potential commercial viability of a film in production so my audience knows the kind of movies to make. The type of money film genres make and which actors tend to bring in the most money will be good for studios to know. Also, looking at the relationship between things like the perceived quality of a movie and its gross.![image]

### Dashboard Link Part 1:
[Tableau Dashboard - Part 1](https://public.tableau.com/app/profile/oluwatobi.omole/viz/Assignment1Part1DataExploaration/Dashboard1?publish=yes)

### Breakdown of Visualizations:

 **Interactive Summary Table**  
Displays average statistics (e.g., budget, duration) with filters for directors, actors, and genres.
Firstly, I made an interactive table with important summary statistics like the average budget, average duration, average movie rating, and film count that can be filtered with information like the director of the movie, lead actor of the movie, 
and the genre. 

![Picture1](https://github.com/user-attachments/assets/83c52f10-fb9c-4bdf-a35c-d1b8b48c8b94)
Sheet 1 (Exploratory Analysis)

**Tree Map (Genres and Gross Revenue)**  
Color-coded by average gross (red = high, blue = low).  
Sorted by IMDb ratings to identify popular and profitable genres.
The second exploratory sheet is a tree map of different movie genres color-coded with their respective average gross amounts to denote higher gross revenue amounts. Darker red hues indicate a higher average gross amount per category, while darker blue hues indicate a lower amount per genre. The boxes are arranged in order of their average IMBD ratings. This visualization's rationale is to see which categories are more highly rated on average and which make the most money. 

![Picture2](https://github.com/user-attachments/assets/2916cb7e-7c9f-45d7-8571-4c943cce0af2)
Sheet 2 (Exploratory Analysis)

**Bar Chart (Lead Actor Gross Revenue)**  
Shows actors’ cumulative gross with color-coded average IMDb ratings.
The third explanatory sheet shows lead actor names with their cumulative total gross for all movies they have starred in. The bar is color coded with the average IMBD ratings of all their movies to show whether higher-rated movies might gross more. The rationale behind this Visualisation is to show which actors made the most revenue and whether their movies are perceived as good on average. 

![Picture3](https://github.com/user-attachments/assets/075dd732-2827-4861-85e1-514e6c94359c)
Sheet3 (Exploratory Analysis)

 **Scatter Plot (Gross Revenue vs IMDb Ratings)**  
Highlights the relationship between movie ratings and revenue.
The fourth explanatory sheet shows the average Gross Revenue for each IMDB rating. The plot shows that higher IMBD ratings tend to have better average gross performances, i.e., better-rated films tend to do better. The rationale behind this Visualisation was to see if the perceived quality of a movie influenced its gross revenue.

![Picture4](https://github.com/user-attachments/assets/4cfaf493-4309-4a6b-bdff-32cb0cdaeca9)
Sheet 4 (Explanatory Analysis)

**Dashboard 1**  
The dashboard was created with filters including the director's name and genre to see how these factors affect each of the created individual visualizations. By selecting a specific director, it is easy to see how many films they directed, the actors they work best with and how much these actors made in movies directed by the director, how much the director's films have made, the average ratings of their movies concerning how much they made and the types of movies they typically make. Filtering with genre also helps find which actors grossed the highest for that genre, the average ratings of the genre movies, how many films are in that genre, etc. The image below shows the dashboard without any filter applied yet.

![Picture 5](https://github.com/user-attachments/assets/b474e9cd-104e-41af-bd97-887a4a3a522f)
Dashboard 1 (Exploratory Analysis no filter applied)

Now I will apply a filter by looking at the Visualisation focusing on a director from the list of directors. I will select Steven Spielberg and see how it changes the Visualisation in the image below. He directed 33 films, and his films have grossed over 6 billion dollars. He also seems to work very well with Harrison Ford as the films they've worked together on have made almost 1 billion dollars. Also, his Biography movies are more highly rated than his other kinds of movies, but his family movies make the most money on average. These are just some of the insights that can be obtained with this Visualisation; more can be seen. 

![Picture 6](https://github.com/user-attachments/assets/851a6c24-86db-4c18-891d-c459553ba885)
 Dashboard 1 (Exploratory Analysis, director filter applied)
 
## Data Inisghts

### Goals:
Explore additional dimensions for actionable insights.
Understand factors affecting movie budgets and returns.
Now that I could explore the data, I gained many meaningful ideas about relationships between important metrics in the dataset, like directors, actors, genres, and gross amounts. Now I will look at other data dimensions to get new insights. This is the link to the dashboard below:

### Dashboard Link:
[Tableau Dashboard - Part 2](https://public.tableau.com/app/profile/oluwatobi.omole/viz/Assignment1Part2DataInsights/Dashboard1?publish=yes)

The first data insight sheet shows lead actor names with the cumulative total budget for all movies they have starred in. The bar is color coded with the average returns of all their movies to show how much their movies tend to make. A darker bar indicates that their movies make more on average. The rationale behind this Visualisation is to show which actors tend to take part in more expensive films, which could give an idea of which actors to avoid if the film's budget is not too high.

![Picture 7](https://github.com/user-attachments/assets/b1808bde-b1d4-4220-b23a-09b747057224)
Sheet 1 (Data Insight)

The second data insight sheet is a tree map of different movie genres color-coded with their respective average budget amounts to denote higher budget category amounts. Darker red hues indicate a higher average budget amount per category while darker blue hues indicate a lower amount per genre. The boxes are arranged in order of their average IMBD ratings. The rationale behind this visualization is to see what categories are more highly rated on average and which cost the most to make. Action, Adventure and Animation genres are the most expensive on average to make; therefore, a studio with a low budget might not opt for these options. 

![picture 8](https://github.com/user-attachments/assets/a29d7b65-77de-41d2-9eb5-d36645c1df05)
Sheet 2 (Data Insight)

The third data insight shows director names with the cumulative total budget for all movies they have created. The bar is color coded with the average returns of all their movies to show how much they tend to make. A darker bar indicates that their movies make more on average. The rationale behind this Visualisation is to show which directors tend to create more expensive films and how these costs compare to how much their movies make on average with other directors, which could give an idea of which director to avoid if the budget of the film is not to be too high. Peter Jackson and Steven Spielberg for instance, have very high cumulative budgets but Peter Jackson returns higher gross revenue on average hence his darker bar. Ridley Scott has a high cumulative budget as well, but his bar is lighter hence his films don't make as much on average as the other expensive directors. 

![Picture 9](https://github.com/user-attachments/assets/e3b066cd-8552-403c-9627-2921cb2b7de3)
Sheet 3 (Data Insights)

The dashboard was created with filters including director's name and genre to see how these factors affect each of the created individual visualizations. By selecting a certain director, it is easy to see how many films they directed, the actors they work best with and how much these actors made in movies directed by the director, how much the director's films have made, the average ratings of their movies concerning how much they made and the types of movies they typically make. Filtering with genre also helps find which actors grossed the highest for that genre and the average ratings of the genres movies as well as how many films are in that genre etc. The image below shows the dashboard without any filter applied yet.

![Picture 10](https://github.com/user-attachments/assets/95451eb4-dde1-4879-a439-21624c96624d)

I have applied a filter for the genre to select only Action movies. Michael Bay is the director with the highest cumulative budget of movies so he's very expensive to hire. Johnny Depp stars in the most expensive action movies and action movies, in general, are expensive to make, marked by the dark red hue.

![Picture 11](https://github.com/user-attachments/assets/3d4c404c-82e3-48f8-b16b-93bb139b1597)

So, for some of the insights of this Visualisation, I have been able to deduce:
•	Action movies tend to be the most expensive to make. Film Noir movies tend to be the cheapest to make
•	Peter Jackson and Steven Spielberg make costly movies
•	Johnny Depp stars in costly movies to make quite often, but his movies have a high average gross as well


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
