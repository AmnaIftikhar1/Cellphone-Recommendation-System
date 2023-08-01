# Cellphone-Recommendation-System

The Cellphone Recommendation System is a machine learning-based application that helps users find the most suitable 
cellphones based on their preferences for brand, screen size, and budget. The system uses a dataset of cellphones with various 
features, such as internal memory, RAM, camera specifications, battery size, and price.

The system's workflow consists of the following steps:

Data Preprocessing: The raw dataset is preprocessed to handle missing values, convert categorical variables to numerical 
using one-hot encoding, and normalize numerical features.

Model Selection: The k-Nearest Neighbors (KNN) algorithm is selected as the machine learning model for predicting cellphone ratings. 

Evaluation: The model's performance is evaluated using Mean Squared Error (MSE) on the test data. Lower MSE indicates better 
model performance.

Recommendation Generation: Based on user preferences for brand, screen size, and budget, the system filters the cellphones that 
match the criteria. 

Output: The system displays the Mean Squared Error (MSE) as a measure of the model's accuracy. It also provides a list of 
the top 5 recommended cellphones that best match the user's preferences.
