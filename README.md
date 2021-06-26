# MovieLens Recommendation System




The purpose of this study is to build a recommendation engine that recommends movies to users. A recommendation system is a platform that provides its users with various contents based on their preferences and likings. From Netflix to Hulu, the need to build robust movie recommendation systems is extremely important given the huge demand for personalized content of modern consumers. Recommendation systems are used not only for movies, but on multiple other products and services like Amazon (Items, Books), Spotify/Pandora (Music), Google (News, Search), YouTube (Videos) etc. 

These systems open new opportunities for businesses and individuals. As a data scientist, we extract insights and behavioural patterns of not only the users (audience) but also from the movies themselves, which when done right could be highly beneficial to the service and its users. 

The overall engagement rate of the user with a streaming service could increase with the help of the recommender system. This will lead to lower cancellation rates and increased streaming hours. We may also understand our customer churn better by understanding if it was the customer’s choice to cancel the service or if there were any other causes like payment gateway failures etc. Also, member satisfaction could also increase with the development and changes to the recommendation system. Personalization and recommendations save Netflix more than 1 Billion $ per year. 
75% of the content people watch today are provided by their recommendation system. Investing in data science technology has helped Netflix to be the best in the video streaming industry.  Also, it is one of the important factors in attracting new subscribers to the platform.

Simply put a Recommendation System is a filtration program whose prime goal is to predict the “rating” or “preference” of a user towards a domain-specific item or item. In our case, this domain-specific item is a movie, therefore the main focus of our recommendation system is to filter and predict only those movies which a user would prefer given some data about the movies and user him or herself. We do the following EDA and Pre-processing techniques to get the data ready for model building, predicting and recommending.

MODEL BUILDING: We will start with Item Based Collaborative filtering method, using the  Classification technique KNN Classifier algorithm to compute similarity with Cosine Distance, in which we will check the assumptions. Then we will move on to other algorithms such as follows: 
❖	Content based filtering (Cosine similarity, Term Frequency and Inverse Term Frequency) 
❖	Memory-based Collaborative filtering (Pearson similarity)
❖	Model-based collaborative filtering (Matrix factorization, Dimensionality reduction)

I worked on this project after referring to the following links:

https://le-james94.medium.com/the-4-recommendation-engines-that-can-predict-your-movie-tastes-bbec857b8223

https://www.analyticsvidhya.com/blog/2020/11/create-your-own-movie-movie-recommendation-system/

https://analyticsindiamag.com/how-to-build-a-content-based-movie-recommendation-system-in-python/

https://www.kaggle.com/shubhammehta21/movie-lens-small-latest-dataset?select=movies.csv

https://towardsdatascience.com/netflix-recommender-system-a-big-data-case-study-19cfa6d56ff5
