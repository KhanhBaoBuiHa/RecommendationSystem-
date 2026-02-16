Overview

This project implements a hybrid recommender system for e-commerce platforms using user behavior data and product information to generate personalized product recommendations. The system integrates multiple recommendation approaches into a production-oriented architecture rather than a standalone model.

Key Features

- Implicit feedback modeling from user interactions (view, cart, purchase)

- Collaborative Filtering using ALS (matrix factorization)

- Content-Based Filtering using TF-IDF and cosine similarity

- Hybrid recommendation strategy (switching + weighted)

- Cold-start handling and user segmentation

- Ranking-based evaluation (Precision@K, Recall@K)

Architecture : Data Processing → Feature Engineering → Model Training → Hybrid Integration → Evaluation

Tech Stack : Python, Pandas, NumPy, Scikit-learn, Implicit, SciPy
