# Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.9-blueviolet)
![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

Machine learning algorithms in recommender systems typically fit into two categories: content-based systems and collaborative filtering systems. Modern recommender systems combine both approaches.

We will be creating a content-based recommender.

## Content-Based Movie Recommendation Systems:

![](https://github.com/pr-atha-m/Movie_recommendation_system/blob/main/Images/Content1.png)

Content-based methods are based on the similarity of movie attributes. Using this type of recommender system, if a user watches one movie, similar movies are recommended. For example, if a user watches a comedy movie starring Adam Sandler, the system will recommend them movies in the same genre or starring the same actor, or both. With this in mind, the input for building a content-based recommender system is movie attributes.

## Link to the working application
Check out -> https://pratham-movie-time.herokuapp.com/

## Snapshots of the application


![GitHub Logo](https://github.com/pr-atha-m/Movie_recommendation_system/blob/main/Images/Screenshot%20(313).png)

 
![GitHub Logo](https://github.com/pr-atha-m/Movie_recommendation_system/blob/main/Images/Screenshot%20(314).png)


![GitHub Logo](https://github.com/pr-atha-m/Movie_recommendation_system/blob/main/Images/Screenshot%20(315).png)


## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

# Algorithm Used For Recommendation:

### Cosine Similarity:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.


## Dataset 
1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)


### references:
1. https://www.machinelearningplus.com/nlp/cosine-similarity/
2. https://docs.streamlit.io/en/stable/

