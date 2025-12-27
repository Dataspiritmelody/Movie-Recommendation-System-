# Interactive Movie Recommendation System

An interactive movie recommendation engine built with Python and Jupyter Notebook. This project allows users to type in a movie name and immediately receive ten recommendations based on what other similar viewers enjoyed.

## 🚀 Project Overview
In this project, I built a real-world recommendation system. By entering a movie title (like *Toy Story*), the system identifies the film, finds users who gave that film a high rating, and then discovers other movies those same users also enjoyed.

**Key Features:**
* **Interactive Search Box:** Built using `ipywidgets` for a seamless user experience.
* **Title Search Engine:** Uses `TfidfVectorizer` and `Cosine Similarity` to find movies even if titles aren't typed perfectly.
* **Recommendation Logic:** Implements a collaborative filtering-style algorithm that finds "niche" recommendations by comparing similar users to the general population.

## Tech Stack & Skills
* **Python:** Core logic and data manipulation.
* **Pandas:** Data cleaning and processing of the MovieLens 25M dataset.
* **Scikit-Learn:** Used TF-IDF Vectorization to build the movie search engine.
* **Ipywidgets:** Created the interactive GUI inside the notebook.

##  How to Run
1.  Clone this repository.
2.  Ensure you have `movies.csv` and `ratings.csv` (from the MovieLens dataset) in the same folder.
3.  Install dependencies: `pip install pandas scikit-learn ipywidgets`.
4.  Open `movie_recommendations.ipynb` and run all cells.
