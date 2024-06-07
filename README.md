# TFIDF-PCA-KMeans
## News Articles Clustering and Visualization
This project performs clustering on news articles related to AI using K-means clustering after transforming the text data into TFIDF vectors and reducing dimensionality with PCA. The optimal number of clusters is determined using the elbow method, and the results are visualized with scatter plots.


## Main Workflow
- Data Collection: Fetches news articles related to AI using the NewsAPI.
- TFIDF Transformation: Converts the content of the articles into a TFIDF matrix.
- PCA: Reduces the dimensionality of the TFIDF matrix to 2 components for visualization.
- Elbow Method: Determines the optimal number of clusters.
- K-means Clustering: Applies K-means clustering to the TFIDF matrix.
- Visualization: Plots the PCA results with clusters and centroids.

## Dependencies

- [newsapi](https://newsapi.org/docs/client-libraries/python)
- [scikit-learn](https://scikit-learn.org/stable/)
- [pandas](https://pandas.pydata.org/)
- [requests](https://docs.python-requests.org/en/latest/)
- [seaborn](https://seaborn.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [scipy](https://scipy.org/)
