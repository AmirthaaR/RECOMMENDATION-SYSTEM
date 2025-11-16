# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AMIRTHAA R

*INTERN ID*: CT04DR1837

*DOMAIN*: Machine Learning

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION ABOUT MY PROJECT 

This project involves building a recommendation system using Item-Based Collaborative Filtering, a widely used technique in modern recommendation engines. The objective is to suggest items (movies) to users based on how similar they are to movies the user has already rated. Unlike user-based filtering, which compares users with similar rating patterns, item-based filtering focuses on the similarity between items, making it more stable and scalable, especially when the number of users is large.

In this task, a small but meaningful movie rating dataset was created containing ratings from multiple users across several movies. The first step involved converting this dataset into a User–Item Rating Matrix, where rows represent users, columns represent movies, and each cell holds the rating a user gave a movie. Missing values were filled with zeros to prepare the data for similarity computation.

To measure how similar movies are to each other, the Cosine Similarity metric was applied to the item vectors. Cosine similarity is effective in identifying relationships between items because it measures the angle between two vectors instead of their magnitude, making it suitable for sparse rating matrices.

Once the similarity matrix was generated, a recommendation function was implemented to retrieve the top movies that are most similar to a given movie. For example, if a user likes “Movie2,” the system identifies other movies with similar rating patterns and suggests them as recommendations.

This project demonstrates key concepts of collaborative filtering and highlights how recommendation systems can be built using simple mathematical techniques without the need for complex deep learning models. The implementation is efficient, fully offline, and easy to extend to larger datasets.

# OUTPUT
