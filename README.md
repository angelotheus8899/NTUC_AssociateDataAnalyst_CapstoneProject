<blockquote>
    <h1 style="font-size:2em;color:#4169E1">
        <p>SCTP              : Associate Data Analyst</p>
        <p>Capstone Project  : Movie IMDb Score Prediction</p>
        <p>Name              : Marteus Yulianto</p>
    </h1>
</blockquote>


# Problem Statement
**IMDb (Internet Movie Database)** is an online database of information related to films, television programs, home videos, and video games, and streaming content online -- including cast, production crew and personal biographies, plot summaries, trivia, fan reviews, and ratings.

The **IMDb score** (or IMDb rating) is a numerical rating assigned to movies, TV shows, and other video content on the Internet Movie Database (IMDb). It is designed to reflect how much audiences like or dislike a particular title. IMDb users rate movies on a scale from 1 to 10, where 1 = terrible and 10 = excellent. These ratings are not a simple average. IMDb uses weighted average algorithm to prevent manipulation by spam or biased voting. 

### 📌 IMDb Score Interpretation Guide

| IMDb Score | Interpretation          |
|------------|--------------------------|
| **9.0–10** | Masterpiece, all-time classic |
| **8.0–8.9** | Excellent               |
| **7.0–7.9** | Very good               |
| **6.0–6.9** | Good / Above average    |
| **5.0–5.9** | Average                 |
| **< 5.0**   | Below average to poor   |

A media analytics firm aims to understand the key factors influencing IMDb movie ratings. The goal is to analyze historical movie data and build a predictive model for **imdb_score** using features like budget, cast popularity, reviews, and more. Finally, it will boost profit or ROI (return on investment) in media industry. 


## Source Dataset
Here are the links to the data source and location:
* **Data Source:** movie_metadata.csv
* **Location:** https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset


## Data Description
Inside the CSV files contains 28 variables for 5043 movies, we will use **imdb_score** as target variable while other 27 variables as possible predictors.

| Feature  Name            | Description                                                                                      |
| -----------------------  | -------------------------------------------------------------------------------------------------|
| movie_title              | Title of the Movie                                                                               |
| duration                 | Duration of the Movie (in minutes)                                                               |
| director_name            | Name of the Director of the Movie                                                                |
| director_facebook_likes  | Number of likes of the Director on his/her Facebook Page                                         |
| actor_1_name             | Primary actor of the movie                                                                       |
| actor_1_facebook_likes   | Number of likes of the primary actor on his/her Facebook Page                                    |
| actor_2_name             | Secondary actor of the movie                                                                     |
| actor_2_facebook_likes   | Number of likes of the secondary actor on his/her Facebook Page                                  |
| actor_3_name             | Third actor of the movie                                                                         |
| actor_3_facebook_likes   | Number of likes of the third actor on his/her Facebook Page                                      |
| num_user_for_reviews     | Number of users who gave a review                                                                |
| num_critic_for_reviews   | Number of critical reviews                                                                       |
| num_voted_users          | Number of people who voted for the movie                                                         |
| cast_total_facebook_likes| Total number of facebook likes of the entire cast of the movie                                   |
| movie_facebook_likes     | Number of Facebook likes in the movie page                                                       |
| plot_keywords            | Keywords describing the movie plot                                                               |
| facenumber_in_poster     | Number of the actor who featured in the movie poster                                             |
| color                    | Film colorization. 'Black and White' or 'Color'                                                  |
| genres                   | Film categorization like 'Animation', 'Comedy', 'Romance','Horror', 'Sci-Fi', 'Action', 'Family' |
| title_year               | The year in which the movie is released                                                          |
| language                 | English, Arabic, Chinese, French, German, Danish, Italian, Japanese etc                          |
| country                  | Country where the movie is produced                                                              |
| content_rating           | Content rating of the movie                                                                      |
| aspect_ratio             | Aspect ratio the movie was made in                                                               |
| movie_imdb_link          | IMDb link of the movie                                                                           |
| gross                    | Gross earnings of the movie (in US Dollar)                                                          |
| budget                   | Budget of the moview (in US Dollar)                                                                 |
| imdb_score               | IMDb Score of the movie in IMDB                                                                  |

## Content:
- **1. Data Exploration / Preparation**
- **2. Data Visualisation**
- **3. Machine Learning**
- **4. Conclusion / Recommendation**
