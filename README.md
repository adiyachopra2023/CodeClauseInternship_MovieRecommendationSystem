# CodeClauseInternship_MovieRecommendationSystem

# Movie Recommendation System

## Types of Recommendation Systems:

1. Content Based Recommendation System
- Recommends movies/series based on the content watched before, for instance, if the user watched a spaced related movie, the recommendations revolve around the genre of space and sci-fi.

2. Popularity Based Recommendation System
- Recommends movies/series that are popular at that given point, for example, netflix has a list of top 10 movies on it's home page, where popularity increases as the views/viewers to that movie increase. Popularity is based on the movie, the actors, the directors, etc.

3. Collaborative Recommendation System
- Groups people based on their watching pattern, say for instance, a bunch of unknown people watch similar kind of content, so this type of system groups them and recommends each other's watched movies to a new user who happened to watch similar movies.

## Workflow:

1. Data Collection 
2. Data Pre-processing
3. Feature Extraction - data is in the form of text which is to be converted into numerical values and find similarity score
4. Ask user from input about their favorite movie
5. Use cosine similarity algorithm to find similarity between vectors (texts are converted to vectors)
6. Suggest similar list of movies

### Note: We don't use a specific ML algorithm but we use only Cosine Similarity Algorithm

## Libraries Used:
1. numpy - used to create numpy arrays
2. pandas - used to create dataframes because data cannot be accessed directly from csv files, it needs to be converted into structured dataframes
3. difflib - used to get the closest match to the value input by the user, here, to find the most similar movie from the dataset to the one input by the user
4. TfidfVectorizer (from klearn.feature_extraction.text) - used to convert text data into numerical vectors
5. cosine_similarity (from sklearn.metrics.pairwise) - used to calculate similarity confidence score to find the most similar movies

### NOTE: This will be a content-based and popularity based recommendation system

## Dataset Link:
https://drive.google.com/file/d/1cCkwiVv4mgfl20ntgY3n4yApcWqqZQe6/view



