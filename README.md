# Anime Recommendation System
# How It Works
The system takes advantage of the following key components:

User Ratings Data: It utilizes user-generated ratings for various anime titles. This data is used to understand individual preferences.

Collaborative Filtering: By analyzing the ratings and preferences of multiple users, the system identifies patterns and suggests anime titles that are likely to be of interest to a particular user.

Cosine Similarity: To calculate the similarity between your selected anime title and others in the dataset, the system employs the cosine similarity algorithm. Cosine similarity measures the angle and proximity between feature vectors, allowing for the identification of titles with similar characteristics to your input.

Graphical User Interface (GUI): The application features a user-friendly GUI that allows you to input an anime title of your choice. Afterward, it provides you with a list of anime recommendations that are closely aligned with your selection.

Dependencies
Before you can run the Anime Recommendation System, make sure you have the following Python libraries installed:

numpy
pandas
matplotlib
seaborn
scikit-learn
Usage
Ensure that you have the required dependencies installed on your system.

Run the Python script to launch the GUI interface for anime recommendations.

In the provided text field, enter the title of an anime you enjoy or are curious about.

Click the "Get Recommendations" button.

The system will then display a list of anime titles that it believes you might find appealing, based on your input.

Code Structure
main.py: This is the main Python script that powers the recommendation system.

rating.csv: A dataset containing user ratings for various anime titles.

anime.csv: A dataset containing information about the anime titles, including details like genre, type, episodes, rating, and more.

Author
This Anime Recommendation System was created by Bruhadev. If you have any questions, suggestions, or feedback, please feel free to reach out.

