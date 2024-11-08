# poisonous-mushroom
Analysis of the UC Irvine (UCI) Mushroom dataset (Mushroom, 1981) to investigate relationships between mushroom attributes and toxicity for predictive model training.

<u>Description</u>\
This report analyses the UC Irvine (UCI) Mushroom dataset (Mushroom, 1981) to investigate relationships between mushroom attributes and its toxicity. Thereafter, it aims to train supervised and unsupervised models capable of properly identifying poisonous mushrooms based on its attributes, and critically evaluate the effectiveness of these models.

<u>Evaluation (Unsupervised)</u>\
K-means and agglomerative hierarchical clustering techniques were used. Principal Component Analysis (PCA) was used to reduce the dimensionality of the dataset for improved clustering results. Both clustering methods were evaluated using the following metrics: Silhouette Score, Calinski-Harabasz Index, Homogeneity, and Completeness. K-means and agglomerative hierarchical clustering both performed suboptimally, and the results were comparable to each other.

K-means clustering achieved the best results after performing PCA, achieving the following metrics:
* Silhouette Score: 0.59
* Calinski-Harabasz Index: 6932.83
* Homogeneity: 0.57
* Completeness: 0.60

Agglomerative hierarchical clustering achieved the best results using Euclidean distance measure and after performing PCA, achieving the following metrics:
* Silhouette Score: 0.46
* Calinski-Harabasz Index: 6086.42
* Homogeneity: 0.59
* Completeness: 0.62

<u>Evaluation (Supervised)</u>\
Logistic regression, K-nearest neighbours, decision tree, random forest and Naïve Bayes were used. They were evaluated using the following metrics: Accuracy, Precision, Recall, and F1 score. All methods, except for Naïve Bayes, achieved perfect classification results, yielding 100% across all four metrics. Naïve Bayes achieved the following metric scores:
* Accuracy: 98.81%
* Precision: 98.80%
* Recall: 98.84%
* F1 Score: 98.81%

<u>Comments</u>\
I have linked the Kaggle notebook to this repo, but a preview may not be rendered due to the large file size. Hence, I have uploaded the .ipynb and .pdf files as well.
