# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity
MOVIE-RECOMMENDATION-COSINE-SIMILARITY
Machine learning algorithms in recommender systems typically fit into two categories: content-based systems and collaborative filtering systems. Modern recommender systems combine both approaches.

We will be creating a content-based recommender.

Content-Based Movie Recommendation Systems:
image Content-based methods are based on the similarity of movie attributes. Using this type of recommender system, if a user watches one movie, similar movies are recommended. For example, if a user watches a comedy movie starring Adam Sandler, the system will recommend them movies in the same genre or starring the same actor, or both. With this in mind, the input for building a content-based recommender system is movie attributes.

Tech stacks
PYTHON : for machine learning part
STREAMLIT: for building up a web application
HEROKU : for deploying a web application
tmdb3api : for showing Movie details
cosine similarity : for showing movie recommendation
Link to the video
CHECK OUT-> https://youtu.be/lQF9fFNJG30

Link to the working application
CHECK OUT-> https://ptflix.herokuapp.com/

Snapshots of the application
Screenshot (126) Screenshot (127) Screenshot (128) Screenshot (129)

How to get TMDB API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

RUN STREAMLIT COMMAND ON YOUR TERMINAL
the command to run the web application on your system is streamlit run appp.py

Algorithm used for application
Cosine similarity:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

How does Cosine similarity works:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity. image

Dataset
I have used the TMDB 5000 movies dataset to build the model You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata

NOTE
Please download the file from link given below to run the program and save it in the repository

https://drive.google.com/drive/folders/1zozuR_uU4JGqeNNHpeR0dLUIqj70efCI?usp=sharing
