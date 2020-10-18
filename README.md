#### Implementation-of-K-means
    sklearn implementation
> Pseudecode guide

###### K-Means Clustering 

    1. Choose the number of clusters(K) and obtain the data points 
    2. Place the centroids c_1, c_2, ..... c_k randomly 
    3. Repeat steps 4 and 5 until convergence or until the end of a fixed number of iterations
    4. for each data point x_i:
       - find the nearest centroid(c_1, c_2 .. c_k) 
       - assign the point to that cluster 
    5. for each cluster j = 1..k
       - new centroid = mean of all points assigned to that cluster
    6. End 
    
 > Gif Simulation Explaining K- means
 
 <img align="" alt="Visual Studio Code" width="350px" src="https://miro.medium.com/max/480/0*f9HcysjkU6XyM1hb.gif" />
 > How to choose value of the value of K if isn't given:
Some instances where the number of clusters are not well known. Therefore when choosing the value for K, we have to use the elbow method. Where, you choose a different number of clusters and start plotting the within-cluster distance to the centroid.

###### Elbow method illustration

<img align="" alt="Visual Studio Code" width="26px" src="<img align="left" alt="Visual Studio Code" width="26px" src="https://miro.medium.com/max/2808/1*dChOocbcsLLT1fcxTxj2Ng.png" />

From the above graph we infer that at k=4, the graph reaches an optimum minimum value. Even though the within-cluster distance decreases after 4, we would be doing more computations. Which is just analogous to the law of diminishing returns. Therefore, we choose a value of 4 as the optimum number of clusters. The reason it is named the elbow method is that the optimum number of clusters would represent an elbow joint!

###### Applications of K-Means Clustering Algorithm

    1. Behavioural Segmentation
    2. Anomaly Detection
    3. Social Network Analysis
    4. Market Segmentation
    
 ##### More Reference 
 https://www.kaggle.com/jchen2186/machine-learning-with-iris-dataset/data
 
