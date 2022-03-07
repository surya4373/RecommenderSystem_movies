# RecommenderSystem_movies
Recommendations Based on Content
 Recommendations systems are a class of machine learning alogrithms which imputes similariteis between users and items of recommendation.They are useful in real world such as

Personalised content 2.Identify products which are similar to the user
Helps websites to improve user engagement suggestions to users.They are two types of filtering

content based system

collabrative filtering --- (Model based,Memory based) Items are ranked according to their relevancy the most relevant ones are shown to the users. Relevancy is something that the recommender system must determine and is mainly based on historical data.

Collabrative filtering Systems: collabrative filtering methods for recommender systems that are solely based on past interactions between user and target items.The data is stored in a matrix where the rows are the users and the columns are the items. Memory based methods: They are most simplistic models which doesn't use any model. They use past data to make predictions. They apply a simple distance measurement approach like K-Means. Model based methods: So, there is a underlying model which is used to make sure what predicition is coming out of the model fits in.

SVD also called as singular value decompostion is an algorithm which is used in collabrative filtering. It is a matrix factorisation method which is used to reduce the features in the data by reducing the dimensions from N to K(K<N) Regularisation is a method which is used in order to avoid overfitting which reduces the accuracy.

Content Based filtering: It uses content based approach will use additional information from the user or items to make the predictions. So, in content based filtering we calculate the distance between the items and find its similarities. The distances are calculated using euclidian distance and consine similarity '''
