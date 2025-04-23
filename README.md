# Steam Recommender System (RECSYS)

This project is focused on developing a recommendation system for Steam, aiming to help users discover new games amidst a rapidly growing catalog. The system leverages various machine learning techniques to provide personalized game suggestions based on user interactions and preferences.

## Machine Learning Technologies Used

1. **Collaborative Filtering**:
   - **itemKNN**: Recommends games based on item similarity (cosine similarity).
   - **userKNN**: Identifies similar users and suggests games based on their preferences.
   - **SVD (Singular Value Decomposition)**: Decomposes the user-item matrix into latent factors to capture implicit preferences.
   - **BPR (Bayesian Personalized Ranking)**: A pairwise learning method tailored for implicit feedback (e.g., game purchases).
   
2. **Content-Based Filtering**:
   - **TF-IDF (Term Frequency-Inverse Document Frequency)**: Utilizes game tags and descriptions to recommend games based on their content similarity.

## Educational Purpose

This project is designed for educational purposes to explore various recommendation system techniques. It aims to provide hands-on experience with:
- Data preprocessing and exploration.
- Implementing and comparing different recommendation models.
- Evaluating model performance using MAP (Mean Average Precision).

## Technologies Used
- Python
- NumPy
- Scikit-learn
- Pandas
