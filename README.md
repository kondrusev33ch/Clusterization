# Clusterization
The purpose of this project is to learn clusterization techniques.

## Project 
Project consists of two jupyter notebooks:
* **Popular clasterization methods**
  * KMeans
  * DBSCAN
  * Gaussian Mixture Model
  * BIRCH
  * Affinity Propagation
  * Mean-Shift
  * OPTICS
  * Agglomerative Hierarchy
  * Fuzzy Analysis
* **Kaggle ["Tabular Playground Series - Jul 2022"](https://www.kaggle.com/competitions/tabular-playground-series-jul-2022/overview) competition approach**
  * *Target*: a data set with 29 unlabeled features is given, you need to clusterize this data. The number of clusters is uknown.
  * *Approach*: I found semi-supervised approach very interesting, especially if you will tune models parameters (resource-intensive), score can be much better. The main idea is to train clusterization model, then take the most confident results of it, and train classification models using these results. After this you can implement iterative classification to improve score even further.
  * *Results*: My best score = 0.808 (which is pretty good, current leader score is 0.831).
