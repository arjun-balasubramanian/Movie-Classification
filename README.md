# Movie-Classification
CLASSIFICATION OF PUBLIC MOVIE REVIEWS USING KNN.


## INTRODUCTION
The classification of movies into genres is an important task in the film industry. It helps moviegoers find movies that match their preferences, and it helps filmmakers and producers identify trends in the market. In recent years, there has been increasing interest in using natural language processing and machine learning techniques to automate the movie genre classification process. In this paper, we present a movie genre classification model that uses the KNN algorithm and TfidfVectorizer for feature extraction. 


## DATASET
The dataset used for this project is a CSV file containing movie reviews and their corresponding genre labels. The dataset has been reduced to a smaller size for the purpose of this project. The dataset contains the following columns: 

review: The movie review text 

genre: The genre label of the movie (Action, Comedy, Drama, Horror, Romance, or Thriller). 

The earlier version of the dataset was converted from a plain text file to an Excel file and the dimensionality of the dataset was further reduced to achieve greater accuracy. 


## METHOD USED
This movie genre classification model is based on the K-nearest neighbors (KNN) algorithm and TfidfVectorizer for feature extraction. The KNN algorithm is a simple and effective classification algorithm that works by finding the K closest data points in the training set to the test point and using their labels to predict the label of the test point. TfidfVectorizer is a feature extraction method that converts text into numerical feature vectors based on the term frequency-inverse document frequency (TF-IDF) weighting scheme. 


## ALGORITHM
This movie genre classification model uses the K-nearest neighbors (KNN) algorithm for classification. The KNN algorithm works by finding the K closest data points in the training set to the test point and using their labels to predict the label of the test point. 

The K-Nearest Neighbors (KNN) algorithm is a popular machine learning algorithm used for classification and regression tasks. It is a simple and effective algorithm that relies on the concept of similarity between instances. Given a new data point, the algorithm searches for the K nearest data points in the training dataset and predicts the label or value of the new point based on the labels or values of the K nearest neighbors. The value of K is a hyperparameter that can be tuned to optimize the performance of the algorithm. KNN is a non-parametric algorithm, which means it does not make any assumptions about the underlying distribution of the data. It is also an instance-based algorithm, meaning that it stores the entire training dataset and does not build a model or learn any parameters. KNN has been applied to a wide range of applications, including image classification, recommender systems, and natural language processing. 


## LIMITATIONS
There are several limitations that you may face when using the above model for movie genre classification. Some of these limitations include: 

Data quality: The accuracy of the model is limited by the quality of the dataset used for training and testing. If the dataset is biased or contains errors, the model may not perform well on unseen data. 

Data quantity: The performance of the model may be limited by the quantity of data available for training. If the dataset is small, the model may not be able to learn the complex patterns required to accurately classify movies into their respective genres. 

Ambiguity in movie genres: Some movies may not fit neatly into a specific genre or may have elements of multiple genres. For example, a movie may be classified as both a comedy and a drama, or as a thriller and a horror movie. This ambiguity can make it difficult for the model to accurately classify the movie into a specific genre. 
