# Content-Based-Recommendation-for-Udemy-Course
 This project demonstrates the creation and use of a content-based recommendation system for the Udemy Course dataset from Kaggle. 
 The goal is to create a system that can recommend similar courses based on attributes such as the course title, tags, instructors, and categories. 

The project consists of analyzing the dataset, preprocessing the data, creating a feature matrix, and building the recommendation system. 
The feature matrix is created by leveraging topic modeling techniques such as TF-IDF Vectorization and Latent Dirichlet Allocation to identify topics from the course titles and descriptions.


The dataset used is publicly available at https://www.kaggle.com/andrewmvd/udemy-courses and can be downloaded directly from there.

 Prerequisites:
- Python 3.7
- Numpy
- Pandas
- Scikit-learn
- SpaCy
- Gensim 
- Matplotlib

Installation:
1. Install the required packages for this project 
2. Clone the repository from GitHub 
3. Navigate to the project folder and run the main.py script 

Usage: 
1. Run the main.py script to train the model 
2. Pass a course title to the get_recommendations() function to receive a list of recommended courses based on the model 


To find out more about the project, please refer to the README file included in this repository.
