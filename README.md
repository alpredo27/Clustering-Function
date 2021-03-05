# Clustering-Function-

### Objective:
   Create a python function that (1.) makes use of the approriate clustering algorithm based on the data types of the input dataframe, and  (2.) outputs the optimal count of cluster, assigned cluster for each observation, and centroids of each cluster.

### Details:
   #### Data Input: 
   1. **Data**: this is the main input dataframe where each row pertains to each observation, and each column pertains to each feature. 
   2. **Data Mapping**: this maps each feature if it's categorical or numerical. Also,the  **factor** column can be used for categorical feature that covers multiple columns after label encoding process. 
   #### Summary: 
   With clean data and data mapping both in dataframe as inputs, this function does the following:
   1. Calculate the number of categorical and numerical features in the data.
   2. Choose the appropriate clustering algorithm among the three (**K-means, K-mode, K-Prototype**.)
   3. Fit the data into the chosen clustering algorithm.
   4. Choose the optimal number of clusters based on the calculated inertia using the **elbow method.**
   5. Output the data with additional column of the cluster, and the centroids of each cluster
    
   #### For Improvement: 
   1. Automate the data mapping as well and omit it as an input to the function.
   2. Add more descriptive information about the centroid for easy differentiation.
   3. Consider other approach on getting the optimal count of clusters.
