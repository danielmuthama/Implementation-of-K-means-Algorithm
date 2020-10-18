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
    
 > Visual Simulation
 <img align="left" alt="Visual Studio Code" width="326px" src="https://miro.medium.com/max/480/0*f9HcysjkU6XyM1hb.gif" />
