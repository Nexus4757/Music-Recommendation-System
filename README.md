# Music-Recommendation-System
Project Overview
This project focuses on creating a text-based music recommendation system using the lyrics of songs. By leveraging Natural Language Processing (NLP) techniques and machine learning, the system analyzes song lyrics to recommend similar songs based on their textual content. The project uses TF-IDF vectorization to extract important features from the lyrics and employs cosine similarity to compute the similarity between songs.

The recommender can suggest top recommendations for a given song, making it an ideal starting point for understanding collaborative filtering and content-based recommendation systems.

Journey Behind This Project
This project started as an experiment fueled by my love for music and curiosity about how streaming platforms like Spotify recommend songs. Initially, I wanted to create a system that mimicked these platforms. As I progressed, I realized the potential of NLP in analyzing song lyrics to offer recommendations.

Through trial and error, I discovered the importance of data cleaning and preprocessing. The journey was not without its hurdles, especially when dealing with large datasets and technical limitations, but it has been a fulfilling learning experience. The project not only deepened my technical skills but also gave me an appreciation for how AI intersects with creative fields like music.

Skills Learned
Natural Language Processing:
1. Text cleaning, tokenization, and stemming.
2. Stop-word removal and normalization.

Machine Learning for NLP:
1. Implemented TF-IDF Vectorization for feature extraction.
2. Used cosine similarity to compute relationships between songs.

Challenges Faced
1. Handling Large Datasets:
   The original dataset was too large to process on my local GPU. I resolved this by sampling the data and optimizing text preprocessing steps.

2. Preprocessing Song Lyrics:
   Lyrics often contained special characters, line breaks, and non-standard formatting. I overcame this by implementing regex-based text cleaning and ensuring consistent formatting.

3. GPU/Memory Constraints:
   The TF-IDF computation for the entire dataset would exhaust the available memory. Sampling and efficient data handling were key to overcoming this limitation.

4. Balancing Simplicity and Scalability:
   While building the recommender system, I learned to balance simple solutions with scalable implementations that could work for larger datasets.
