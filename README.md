# Myopia Clusters

![Myopia](myopia-image.jpg?raw=true "Myopia")

## Background

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

* Part 1: Prepare the Data
    * Load, evaluate, clean and scale data (see jupyter notebook)
* Part 2: Apply Dimensionality Reduction
    * Use PCA and t-SNE methods for reduction (see jupyter notebook)
* Part 3: Perform a Cluster Analysis with K-means
    * Find the optimal amount of classes (clusters) (see jupyter notebook)
* Part 4: Make a Recommendation
    * Based on the elbow curve, the optimal number of clusters for this analysis is three.
    * **Recommendation**: Use the 3 separate clusters for further analysis to see if the distinct groups provide better results than the whole dataset.
