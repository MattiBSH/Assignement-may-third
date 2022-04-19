# Assignement-may-third
2
The K means and db scan algorithm are good to use with very large datasets.

k means assumes that the data is roughly equal, so it's a good idea to use data with similar category sizes or somehow normalize the data. DB scan is very fast and can therefore handle large amounts of data.v

3. 
Clustering is when you take data and divide it into groups so that the data points of data have more in common with other group members than the other groups of data.

4. 
The elbow method is the first one.
The elbow method is done by calculating the wss(within cluster sum of squared errors)
After plotting you pick where it looks like an elbow and choose that value. Sometimes it might be hard to determine but then you can just try multiple out and see what works the best.


Example 1
Here you can see that k is 3

Silhouette score method
The silhouette method calculates the similarities and dissimilarities between clusters.
In the silhouette method it's all about getting the highest number so whichever number is the highest should be the k in k means. 

Example 2

Here you can see that k should be 3 as it is the highest point


5. 
Kmeans is good for large datasets.
DB scan is good for regions of high density

6.
Density, in terms of DBSCAN, means the number of points that are located in a given area. The closer the points are to each other, the greater the density will be.

7. 
If you have similar groups and have a high number of k. That group can become one with a lower value of k even though they are distinctly different groups. Therefore having more can benefit the precision of the model. The same is also true of having less, therefore having methods as shown before in choosing the right amount is very important.
