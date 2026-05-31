# movie-recommender
Movie recommendation system built using Term Frequency Inverse Document Frequency (TF-IDF) and Cosine Similarity
This project employs a content-based recommendation system to suggest new movies to users based on previously liked movies.

Technologies Used:
- Python
- Sklearn
- Pandas
- TF-IDF Vectorizer
- Cosine Similarity

Features:
- Previously watched movie name input by user
- Similar movie recommendations generated

How it Works:
- Select features are extracted from each movie in the dataset (synopsis, cast and crew...)
- Those features are converted to numeric vectors using TF-IDF
- The numeric vectors are compared using cosine similarity to find movies with similar content to the inputted movie
