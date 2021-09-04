# Titanic-Machine-Learning-from-Disaster
This dataset is found on the Kaggle website which is an online platform where you can learn a lot about machine learning with Python and R, do data science projects, and join machine learning competitions.  
The Titanic sank on April 15, 1912, during her maiden voyage, after colliding with an iceberg, killing 1502 of the 2224 passengers and crew on board. Translated 32% survival rate. There were insufficient lifeboats for the passengers and crew, which contributed to the shipwreck's high death toll. Although there was a degree of luck involved in surviving the sinking, particular groups of people, such as women, children, and the upper class, were more likely to survive than others.  

In this project I would explore the data and identify a few stages to describe the data science project 

First and foremost, I want to ask a question, weather the model can determine the survival information based on the dataset and check who survived and did not survive in the Titanic disaster. I started by acquiring training and testing datasets into Pandas Data Frames and using Scikit-Learn libraries. Pandas helped me in describing and answering a few questions in the project, for example which features are present in the dataset, identify numerical and categorical features, features which contain Null values, help is identifying the datatypes. 

After collecting several assumptions and decisions regarding the dataset and solution requirements I decided to drop few features, to ease the data analysis, some of the features which I dropped are "Ticket", "Cabin", "PassengerId", "Name" and converted features which contained strings to numerical values.(Pclass, Sex, Embarked) 

 Using visualization techniques, I analyzed the data to check the missing values, identify correlation, check the number of passengers survived using Pclass, Gender, Embarked and Age feature. 

 Model Prediction and solution 

This dataset is a classification and regression problem. I had to identify the relationship between output (Survived or not) with other variables or features (Gender, Age, Port...). Lastly, I am also performing a category of machine learning which is called supervised learning while training the model with a given dataset. 

With these two criteria - Supervised Learning plus Classification and Regression, I narrowed down and chose a few models. These include Logistic Regression, KNN or k-Nearest Neighbors, Support Vector Machines, Naive Bayes classifier, Decision Tree, Random Forrest, Perceptron, Artificial neural network and RVM or Relevance Vector Machine 
