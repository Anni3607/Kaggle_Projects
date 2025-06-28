Netflix Titles Recommender System

This is a content-based recommender system built using the Netflix dataset from Kaggle. It recommends similar shows/movies based on their descriptions.

 Dataset

Dataset used: [Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows)

 How It Works

- Uses TF-IDF Vectorization on the "description" column
- Computes cosine similarity between all titles
- Recommends the top 10 most similar titles

