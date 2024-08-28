# Movie-Recommendation-Engine
Objective:
To develop a movie recommendation engine that suggests movies based on user input by calculating similarity scores using various features.

Tools:
Python
Jupyter Notebook

Project Context:
This project was completed as part of my Data Science Internship program at Acmegrade.

Process:
1. Data Cleaning and Preparation:
- Handled missing values in the dataset.
- Removed duplicates and irrelevant features.
- Preprocessed text data by tokenizing and normalizing to ensure consistency.

2. Feature Selection:
Selected key features for calculating similarity:
- Title
- Genre
- Overview
- Keywords
- Cast
- Director
- Writer

3. Text Vectorization:
- Converted textual data into vectors using Term Frequency-Inverse Document Frequency (TF-IDF).
- Represented each movie by combining the vectors of selected features.

4. Similarity Calculation:
- Applied Cosine Similarity to measure the similarity between movies.
- Computed similarity scores based on the user's input movie.

5. Recommendation Generation:
- Ranked movies based on similarity scores.
- Returned the top 30 most similar movies as recommendations.

6. Model Evaluation:
- Validated the relevance of recommendations through manual inspection.
- Ensured diverse genre coverage and accurate matching of thematic elements.

Outcome:
Successfully developed a movie recommendation engine that provides personalized movie suggestions based on user input. This project demonstrated the effective use of text processing, vectorization, and similarity measures in building recommendation systems.
