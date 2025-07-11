# Book-Recommendation-System
📚 Book Recommendation System using Item-based KNN Collaborative Filtering
This project implements an item-based collaborative filtering recommendation engine using the K-Nearest Neighbors (KNN) algorithm to recommend books based on users’ past ratings. The system analyzes user-item interaction data to find books similar to the ones a user has previously rated highly, delivering personalized suggestions without requiring explicit user profiling.

🔍 Key Features:
Item-based Collaborative Filtering: Uses cosine similarity between book rating vectors to identify books that are similar based on user ratings.

KNN Algorithm: For each unrated book, finds the k most similar books the user has rated and predicts a rating by weighted average.

Personalized Recommendations: Outputs top-n recommendations tailored to individual user preferences.

Data Preprocessing Pipeline:

Cleaned and filtered sparse user-book rating data

Merged relevant metadata (e.g., book titles, authors, publication years)

Handled missing values and outliers

Visualized rating distributions and sparsity for insight and tuning

Similarity Computation: Optimized using vectorized operations and caching to efficiently handle large datasets.

📊 Dataset Used:
Book-Crossing Dataset containing user ratings for thousands of books, including metadata.
from https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?resource=download
