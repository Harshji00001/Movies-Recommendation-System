# Movies-Recommendation-System
A content-based Movie Recommendation System built using Python, Jupyter Notebook, and machine learning techniques. The system recommends similar movies based on features such as overview, genres, keywords, cast, and crew.

# Description
This project uses content-based filtering to recommend movies.
The dataset is processed by combining multiple features into a single text vector.
Using TF-IDF Vectorization and Cosine Similarity, the system finds and recommends movies similar to the one selected by the user.

Using the following steps, the system generates recommendations:

# Step 1: Data Preprocessing
Load and clean movie metadata
Extract features such as:
- Overview
- Genres
- Keywords
- Cast
- Crew

Combine all feature text into one column

# Step 2: Vectorization
Convert text into numerical values using
TF–IDF Vectorization (Term Frequency–Inverse Document Frequency)

# Step 3: Similarity Calculation
Compute similarity between movies using
Cosine Similarity Matrix

# Step 4: Movie Recommendation
When the user enters a movie name,
the system finds the top most similar movies
based on similarity scores.

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NTLK
- Jupyter Notebook
- TMDB Movie Dataset
