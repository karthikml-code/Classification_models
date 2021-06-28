It’s simply assigning the new data points to a category based on the knn. First, pick a k number of neighbours (usually 5). 
Now take the k nearest neighbours of the data point based on the Euclidean distance. 
Among the k neighbours, count the number of data points in each category. 
Finally assign the new data point to the category which counted most neighbours. 

Euclidean distance between two points p1 and p2 = √((x_2-x_1 )^2+(y^2-y_1 )^2 )
