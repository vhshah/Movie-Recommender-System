# Movie-Recommender-System
I worked on developing a movie #recommendersystems similar to those used by e-commerce websites, music and movie streaming apps. The dataset is available on https://www.kaggle.com/rounakbanik/the-movies-dataset . This was by far the most unstructured dataset that I had to deal with as most of the data had to be extracted from strings, lists and JSON forms before it could be computed. After a lot of data cleaning, I developed 3 different recommender systems and one search/filter system. I also performed extensive #EDA to explore the most movies, highest rated movies etc. per genre, cast, director etc. I used the weighted rating formula of IMDb.com to rate the movies and used these to filter out movies based on genre and language.

I designed two content based recommender systems using #NLP techniques like TfidfVectorizer, CountVectorizer, Snowball Stemmer. The first system used the movie overview to find similar movies through the cosine similarity rule. For the second recommender, I used the cast, director, genre and the keywords to design the similar movies ( again with the cosine similarity).

I also created a user based recommender system which used all the ratings of each user and recommended movies using Single Vector Decomposition.
