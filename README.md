# Data Narrative: Tennis Major Tournaments Dataset
This repo presents forth a Data Narrative prepared as a part of a course project. The data analysis involves the use of **Clustering, Classfication**, and **Regression** using **machine learning models** in python's **Scikit-Learn** Library. The repo also includes a written report for the same as compiled in **LaTex**.
## The Overview
The Narrative was part of the **ES-114: Probability, Statistics, and Data Visualization** course offered to the first-year B.Tech students during the **April '23** for the first time at the **Indian Institute of Technology, Gandhinagar.**
The Machine Learning Course **ES-113: Data Centric Computing** here at **IIT, Gandhinagar,** was conducted in coherence with this course.
The Narrative allowed for the analysis of the the [Tennis Major Tournaments](https://doi.org/10.24432/C54C7K) dataset using **Clustering, Classification,** and **Regression**. Several of Probabilistic and Data Analystic tools like **Covariance Matrices, Correlation Factors,** and **Principal Components Analysis** were employed in the narrative.

## Libraries used and Analysis Approach
The following is the list of Python Libraries used for the narrative:
1. **Pandas**
2. **NumPy**
3. **Scikit-Learn**
> * sklearn.naive_bayes.GaussianNB
> * sklearn.preprocessing.StandardScaler
> * sklearn.decomposition.PCA
> * sklearn.cluster.KMeans
> * sklearn.metrics.accuracy_score
> * sklearn.model_selection.train_test_split
> * sklearn.model_selection.cross_val_score
4. **Plotly**
> * plotly.express.scatter()
> * plotly.express.box()
> * plotly.express.3d_scatter()
> * plotly.express.bar()

* The main aim of the analysis was to predict the target (win: 0/1) of the newer result based upon the features given to us to work with.
* To prepare our data for training, number of features had to be reduced down.
* Correlation among the features was analysed and redundant features having high correlation were shot-down.
* Now with the less features, the data was prepared for training on a **Gaussian Naive Bayes classifier**.
* Accuracy of this model was tested using a 5-fold cross validation score. The model actually gave a **high accuracy score of 0.9049230769230769**.
* Another way of unsupervised learning was the use of **KMeans clustering**.
* Two clusters were allowed to form and the accuracy was compared with original data.
* To visualize the clustering, the dimensionality of the features was reduced to 3 using **Principal Component Analysis (PCA)** so clusters were plotted in 3D.
* Finally, there were some ways using Pandas and NumPy to filter out important statistical data/stats and the same was plotted for using Plotly graphs.

Please refer to the [Colab link](https://colab.research.google.com/drive/1Z0mJhQlPfRp8m01fKYLkdour3K9RcWca?usp=sharing) to view the interactive Plotly graphs.
