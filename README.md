# Movie Recommendation System

This is a movie recommendation system built using Python and the scikit-learn library. The system recommends movies similar to the user's input based on textual features such as genres, keywords, taglines, cast, director, and original language.

## Requirements
- Python 3.x
- pandas
- scikit-learn

## Usage

1. Clone the repository:


2. Navigate to the project directory:


3. Install the required dependencies:


4. Run the movie recommendation system:


5. Enter your favorite movie when prompted.

## Approach

- The system uses a TF-IDF vectorizer to convert textual features of the movies into numerical vectors.
- Cosine similarity is calculated between the feature vectors of the input movie and all other movies in the dataset.
- Movies with higher cosine similarity scores are recommended to the user.

## Data

The system uses a dataset of movies containing information such as title, genres, keywords, taglines, cast, director, and original language.
the data set movies.csv is provided

## Acknowledgments

- This project is inspired by various movie recommendation systems and tutorials available online.

