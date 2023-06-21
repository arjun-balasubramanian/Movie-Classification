# Movie-Classification
CLASSIFICATION OF PUBLIC MOVIE REVIEWS USING KNN.

## INTRODUCTION
The classification of movies into genres is an important task in the film industry. It helps moviegoers find movies that match their preferences, and it helps filmmakers and producers identify trends in the market. In recent years, there has been increasing interest in using natural language processing and machine learning techniques to automate the movie genre classification process. In this paper, we present a movie genre classification model that uses the KNN algorithm and TfidfVectorizer for feature extraction. 

##DATASET
The dataset used for this project is a CSV file containing movie reviews and their corresponding genre labels. The dataset has been reduced to a smaller size for the purpose of this project. The dataset contains the following columns: 

review: The movie review text 

genre: The genre label of the movie (Action, Comedy, Drama, Horror, Romance, or Thriller). 

The earlier version of the dataset was converted from a plain text file to an Excel file and the dimensionality of the dataset was further reduced to achieve greater accuracy. 

##METHOD USED
This movie genre classification model is based on the K-nearest neighbors (KNN) algorithm and TfidfVectorizer for feature extraction. The KNN algorithm is a simple and effective classification algorithm that works by finding the K closest data points in the training set to the test point and using their labels to predict the label of the test point. TfidfVectorizer is a feature extraction method that converts text into numerical feature vectors based on the term frequency-inverse document frequency (TF-IDF) weighting scheme. 
