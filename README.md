# Movie-Recommendation-Systems
Movie Recommendation Systems Using Time Series Analysis:

**Introduction:**
In today's world, movie recommendation systems can benefit both the users and the service providers. It helps in enhancing the user experience and engagement, helps in content discovery, generates data and insights, and helps in user retention.
Time series can help us understand the trends and seasonality of the different types of movies around the year. Utilization of Time Series models to predict the ratings of movies in the future helps to understand how different movies and genres will perform at different intervals of time

**Data and Methodologies:**
The MovieLens 25M dataset is used for the analysis and prediction which comprises 25 million ratings for 62000 movies and 162000 users. For the initial analysis, the MovieLens 10M data set is used. 10 million ratings applied to 10,000 movies by 72,000 users. It contains data from the period of 1995 to 2009.
Univariate forecasting models like ETS, TBATS, ARIMA, Prophet (developed by Facebook) and Croston (to handle intermittent data) will be used for forecasting. An ensemble will be created using the top three performing models (benchmarking using accuracy metrics) to predict the ratings.
Multivariate forecasting models like ARIMAX, and Vector AR will be used to include external factors as well.
Stage of work:
 
The MovieLens 10M data has been converted to Panel data which comprises the average ratings provided to each movie in a given month by taking the average ratings for that month for all the users.
The data is then converted to time series objects, and EDA has been performed on the same. Continuity analysis is performed to identify if any intermittent data exists using the Cofv (Coefficient of Variation).

**Pre-existing Study:**
Movie recommendation systems are made using two main methodologies:
•	Content-Based Filtering: Provides recommendations based on the attributes of a movie
•	Collaborative Based Filtering: Provides recommendations based on the preferences of other users

**Objectives of current study**
•	The main aim of this research is to understand which genre of movies or which specific movies perform well at different times of the year based on seasonality. 
•	This will help suggest those specific movies to the users providing them user-specific recommendations
•	This will also help the service providers interpret how to run their campaigns and advertisements at different times of the year which customer base, improve customer retention, and also increase the revenue generation for service providers

