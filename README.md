# CS210_Project




Motivation: 

During the last few years, watching movies has evolved from a casual pastime into one of my most cherished hobbies. As a zealous moviegoer, I've maintained an online diary to track the films I've watched. This project was born out of a desire to delve into my cinematic journey, to understand my evolution as a movie enthusiast, and to uncover patterns in my movie-watching behavior. By analyzing the data of movies I've watched and rated, I aimed to gain insights into my preferences and to see how they align with broader cinematic trends and critiques.


Data Source: 

The dataset that formed the foundation of this analysis was downloaded from Letterboxd, a platform where I've been diligently logging my movie-watching experiences. While Letterboxd provided a good starting point, the data was somewhat limited in depth. To enrich my analysis, I crafted code to fetch additional movie details from the OMDb API, retrieving richer attributes such as IMDb ratings, Metascores, and Box Office figures. These code blocks have been documented in my project as comments, marking the steps taken to enhance the dataset.


Data Analysis: 

The analytical phase of the project involved meticulous data preparation followed by exploratory data analysis. I utilized a range of Python libraries, including Pandas for data manipulation and Scikit-learn for machine learning tasks. After cleaning and merging the datasets, I embarked on a quantitative analysis to draw correlations between my ratings and various movie features. Decision Trees played a pivotal role in modeling these relationships, with hyperparameter tuning conducted via GridSearchCV to refine the model's predictive capabilities.


Findings: 

The analysis led to several key discoveries:
Metascores are highly indicative of my personal ratings, suggesting a strong alignment with critical perspectives.
A moderate correlation with IMDb votes implies that popular opinion does have a sway in my movie choices.
Genre analysis confirmed my preference for certain types of films, which typically received higher ratings from me.
Through this project, I gained a clearer picture of my cinematic tastes and how they are influenced by both critics and the general audience.


Limitations and Future Work: 

This project had some limits. The information I had was only from Letterboxd and OMDb, so I might have missed out on other important things that could affect how I rate movies, like the style of the director or the movie's deeper messages. The Decision Tree model I used was helpful but didn't catch all the subtleties of what makes me like or dislike a movie.


Looking ahead, I want to: 

Add more detailed information, like what people say about movies in reviews and what the trailers show.
Try out more advanced types of models that might do a better job of guessing how I'd rate a movie.
Make my dataset bigger to include more movies and more details about when and where I watched them.
I'm just getting started on combining my love for movies with data analysis. I'm excited to learn more about what makes a movie special to me and to get even better at predicting how much I'll enjoy a new movie.

