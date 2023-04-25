# K-Mean-Clustering

## The Data
Ratings from Google reviews dataset in the Review_ratings.xlsx file. It contains the ratings of 1000 users on attractions from 24 categories across Europe.

## The Code
1. Importing the necessary libraries: pandas, numpy, matplotlib, seaborn, KMeans, and StandardScaler.
2. Loading the data from an Excel file.
3. Checking for null and duplicate values in the data.
4. Detect and handle the outliers.
5. Preprocessing the data by scaling it using StandardScaler.
6. Defining the number of clusters.
7. Initializing the KMeans clustering model with the specified number of clusters.
8. Fitting the model on the preprocessed data.
9. Extracting the labels (cluster assignments) for each data point.
10. Adding the labels to the original dataset as a new column.
11. Plotting the data points with different colors for each cluster to visualize the clustering result.
