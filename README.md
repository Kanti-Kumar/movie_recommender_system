# Movie Recommender System

Website : https://kanti-movie-recommender.streamlit.app/

Blog Link : https://kanti-kumar.medium.com/end-to-end-movie-recommender-system-project-cf50133bc433

As we know, there are mainly three types of recommender systems:
1. Content Based
2. Collaborative Filtering
3. Hybrid

In this project, I developed a Content Based recommender system, which creates 'tags' from movie data to generate recommendations.

## Project Flow :
This project mainly have 5 steps:
1. Data : I used TMDB 5000 movies dataset for this project.

2. Preprocessing : Data preprocessing involved cleaning and preparing the data, creating tags, and handling missing values or duplicates.

3. Model Building : I built a content-based recommendation model using the 'tags' generated during preprocessing. The model computes similarities between movies based on these 'tags' and recommend movies which have highest similarity score.

4. Website Building : I created a basic website using Python Streamlit library. To enhance the user experience, I fetched movies 'poster' from their 'titles' using the OMDB API, otherwise it only shows 'title' of movies recommended by model which not seems good.

5. Deployment : The app was deployed on Streamlit Community Cloud, a free platform for deploying apps.

# Future Improvements :
* Implement collaborative filtering or hybrid recommendation approaches.
* Enhance the User Interface with more features.
* Integrate additional data sources for better recommendations.

# Contributing :
Contributions are welcome! Feel free to open an issue or submit a pull request.
