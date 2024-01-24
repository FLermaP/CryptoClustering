# CryptoClustering
- In this homework we used from the [scikit-learn](https://scikit-learn.org/stable/) (sklearn) library on the price change of certain crypto currencies at different intervals ranging from 24 hrs to 1 year :
  - KMeans(),
  - PCA() and
  - StandarScaler()

## About the Homework
- Data graphing does not always show a clear picture of what to is part of one group vs another, sometimes the values are too far apart or to close together.
- The following machine learning algorithms where used to try to find the right groups:
  - [KMeans](https://scikit-learn.org/stable/modules/clustering.html#k-means): used to create groups based on a defined number of clusters
  - [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html#sklearn.decomposition.PCA) used to reduce the number of dimensions/columns without losing a substantial amount of information.

- Another tool used is :
  - [StandardScaler](https://scikit-learn.org/stable/modules/preprocessing.html#preprocessing-scaler) :This tool finds the mean of the values, uses that as the center and the rest of the values are deviations or distances from that center 
- The **Elbow** method was used in conjunction with KMeans to determine a better number of clusters
