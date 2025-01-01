# Poetry-Book-Recommender-System
**Third Year (2022/2023) Recommender System Module**

A poetry recommender system using a hybrid approach. Including a content-based and model-based collaborative filtering switch model for personalised recommendations, and a non-personalised system to recommend popular books, with an interactive command-line interface.

Using a subset of the UCSD Book Graph dataset, with over 35,000 poetry books, 2.7 million interactions and 150,000 reviews.

The content-based filtering uses chi-squared feature selection and cosine similarity. The collaborative filtering is implemented with SVD and optimised with stochastic gradient descent. Content-based filtering is used for new users with few interactions, which then later switches to collaborative filtering.

https://github.com/user-attachments/assets/bc9ecc96-b394-49bc-ac6f-61a0d3335bcf

