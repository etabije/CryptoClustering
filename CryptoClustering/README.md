# CryptoClustering
Cryptocurrency Clustering Analysis

This project uses K-means clustering and Principal Component Analysis (PCA) to group cryptocurrencies based on price changes over 24 hours and 7 days.

Tasks
Find the Optimal k Value
Implement the elbow method to determine the best value for k using inertia values and a plot.
Cluster Cryptocurrencies with K-means
Use the optimal k to cluster the data. Create a scatter plot with hvPlot, visualizing the clusters based on price change percentages, and include cryptocurrency names on hover.
Optimize Clusters with PCA
Reduce the features of the data to three principal components using PCA. Analyze the explained variance and create a new DataFrame with PCA-reduced data.
Determine Optimal k Using PCA Data
Apply the elbow method to the PCA data to find the best k. Compare this value to the one found using the original scaled data.
Cluster with K-means Using PCA Data
Fit the K-means model on the PCA data, predict clusters, and plot the results using hvPlot with principal components.
Visualize and Compare Results
Create composite plots comparing elbow curves and clustered results from both the original and PCA-reduced data. Analyze the effect of using fewer features for clustering.
Code Conventions and Formatting
Ensure proper file structure, use meaningful function and variable names, and follow best coding practices.
Deployment and Submission
Submit the project to GitHub with appropriate commit messages and documentation.
Code Comments
Provide clear and concise comments throughout the code for easy understanding and collaboration.
Resources
Professor Melissa Ingle
Cassidy Cruz (classmate)
ChatGPT
Stackoverflow
