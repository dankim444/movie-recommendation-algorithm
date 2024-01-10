##Overview
- This repo creates a movie recommendation system using Jupyter, Python, and Pandas. Users are able to type the name of a movie in an input box and get recommendations for other movies.
  Using the MovieLens 25M dataset, this system analyzes movie data, processes user input, and provides movie recommendations based on user preferences. Here are the list of steps of how
  the code operates:

1. Data Loading and Preprocessing: It loads movie data and preprocesses it, including cleaning the titles for better analysis.

2. Vectorization: It transforms the cleaned movie titles into a numerical format (TFIDF) for similarity comparison.

3. Search Functionality: Implements a search function to find movies similar to a given title.

4. User Interface: Uses IPyWidgets to create an interactive interface where users can type a movie title and get recommendations.

5. Similarity-Based Recommendations: After receiving a movie title from the user, the system finds and displays similar movies based on defined criteria.

##Dependencies
- Pandas (pip install pandas)
- Scikit-learn (pip install scikit-learn)
- IPyWidgets (pip install ipywidgets)
- NumPy (pip install numpy)

##Usage
- To run the system, execute the script in a Jupyter Notebook environment. Ensure you have the required dataset (MovieLens) placed correctly.
