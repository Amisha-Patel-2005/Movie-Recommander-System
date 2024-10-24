# Movie-Recommander-System

A movie recommender system is a machine learning model that suggests movies to users based on their past preferences or behavior. 
These systems are crucial for platforms like Netflix, Amazon Prime, and Hulu, as they enhance user experience and increase engagement.

# Abstract

Recommender systems have become an integral part of modern entertainment platforms, providing personalized suggestions to users. 
This project aims to develop a robust movie recommender system using deep learning techniques. 
By leveraging the power of neural networks, the system will be able to effectively capture complex patterns in user behavior and movie characteristics, leading to more accurate and relevant recommendations.

The proposed system will employ a hybrid approach combining collaborative filtering and content-based filtering techniques. 
Collaborative filtering will analyze user-item interactions to identify similar users and movies. 
Content-based filtering will consider the attributes of movies, such as genre, actors, and director, to recommend similar content. Deep learning models, including neural networks and autoencoders, will be employed to learn latent representations of users and movies, enhancing the accuracy of recommendations.

The system will be evaluated using standard metrics such as precision, recall, F1-score, and mean squared error. 
The goal is to develop a system that outperforms traditional recommender systems and provides a superior user experience.

# Method

The model uses 
Steps involved the model are:
- Import Libraries
- Import dataset
- Get feature selection
- Get feature text conversion to tokens
- Get similarity score using cosine similarity
- Get movie name as input from user and validate for closet spelling
- Get all movies sort based on recommandation system with respect to favourite movie
- Top 10 movie recommands

# Result

System is successfully able to recommand top 10 movies of user interest.
