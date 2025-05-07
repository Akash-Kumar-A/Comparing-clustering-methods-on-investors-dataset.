
Topic :  
Comparing clustering methods on investors dataset. 

Dataset : 
● Features(4) : 
○ fixed_deposits 
○ bonds 
○ stocks 
○ cryptocurrencies 
● Classes(2) : 
○ 0 - low-risk investors 
○ 1 - high-risk investors  
Summary : 
● Investors dataset without class column is taken for clustering. 
● On plotting the inertia vs k (elbow plot) we find optimal no. of 
clusters k = 2, which corresponds to no. of classes. 
● On applying k-means clustering from the sklearn library and 
comparing the clusters with the actual classes, we get an 
accuracy of 99%. 
● On applying spectral clustering from the sklearn library and 
comparing the clusters with the actual classes, we get an 
accuracy score of 100%. 
● On manually applying spectral clustering, we get the same 
accuracy that we get when using libraries. 
Inference : 
● On plotting the boxplot of the two clusters, we can see significant 
differences in the amount of investments in the stocks and 
cryptocurrencies asset classes. 
● Cluster 1 has more allocation in those asset classes, while 
cluster 0 has very less allocation in the same.
 Conclusion : 
● Both k-means clustering and spectral clustering were able to 
successfully cluster the dataset. 
● There is no significant difference between the performance of 
k-means clustering and spectral clustering on the dataset. 
