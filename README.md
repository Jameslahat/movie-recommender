# movie-recommender
A simple content-based Movie Recommendation System built using Python, TF-IDF Vectorization, and Cosine Similarity. Includes a clean Streamlit web interface for interactive movie search and recommendations. Ideal beginner-friendly AI/ML project demonstrating NLP feature extraction, similarity scoring, and model deployment.

movie-recommender/
│
├── data/
│   └── movies.csv
│
├── models/
│   └── tfidf_sim.pkl
│
├── src/
│   ├── data_loader.py
│   ├── model_builder.py
│   └── recommender.py
│
├── app.py
├── requirements.txt
└── README.md

How It Works

Load and clean movie dataset

Convert movie overviews into numerical vectors using TF-IDF

Compute similarity matrix using cosine similarity

When the user enters a movie name → return top similar movies

Streamlit UI displays recommendations in a clean interface
