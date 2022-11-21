# Unsupervised Machine Learning with scikit-learn

In this repo is a jupyter notebook that demonstrates scikit-learns ability to perform unsupervised machine learning on a dataset. The dataset is cleaned and transformed using pandas, and modeled to fit utilizing different scikit-learn methods.

In this repo you will find:

|Notebook|Description|
|--------|-----------|
|[Unsupervised Learning](unsupervised%20learning.ipynb)| This notebook contains the scikit-learn modeling and methods used to create clusters out of myopia patient data, and the thoughts/analysis on the results of those methods.|

|Data|Description|
|----|-----------|
|[Myopia data](/data/myopia.csv)| This csv file contains the myopia dataset used to model the unsupervised machine learning models.|
|[TSNE Clustering](/data/tsne_clusters.png)| This image file is used in the notebook to demonstrate thoughts on potential clusters found from plotting a TSNE reduction|

## What is this?

This is a demonstration of scikit-learns unsupervised machine learning. This demonstration was accomplished by utilizing a dataset on myopia patients. The dataset was transformed and shaped to be sutible for the unsupervised machine learning process (Preprocessing). The methods done to achieve this are:

|Method|Description|
|------|-----------|
|[StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)| Ensure behavior of machine learning is not effected by variance, scaling towards normally distributed data|
|[Principle Component Analysis](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)| Used to reduce the dimensionality of the dataset for easier interpretation.|
|[TSNE](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)|T-distributed Stochastic Neighbor Embedding. A method for creating high-demensional data visualizations through similar object assosociation by way of probability.|
|[K-Means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)| An algorithm that clusters data with high potential interpretability. Used in conjunction with the Elbow method, which was utilized to determine the optimal k value.|

Ultimately, the goal for this unsupervised machine learning was to determine if myopic patients could be seperated into identifiable clusters based on the unsupervised machine learnings output. The analysis of the data can be found in the [Unsupervised Learning Notebook](unsupervised learning.ipynb).

## References

##### Reduced dataset from Orinda Longitudinal Study of Myopia conducted by the US National Eye Institute
##### © 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
##### Scikit-learn: Machine Learning in Python, Pedregosa et al., JMLR 12, pp. 2825-2830, 2011.
##### Wikipedia contributors. (2022, November 3). T-distributed stochastic neighbor embedding. https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding
