# Module-10-challenge

## Challenge: Crypto Clustering

![Crypto](https://tse4.mm.bing.net/th?id=OIP.W86wadZRcUBR-FP8NPKp0wHaEK&pid=Api&P=0&h=220)

In this Challenge, I combined my financial Python programming skills with the new unsupervised learning skills.

Ive created a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods, and plot the results so that we can visually show the performance to the board.

![PCA Crypto PCT Change](Module-10-challenge/Starter_Code/Resources/pca Crypto percentage change.png)
![Crypto PCT Change](Module-10-challenge/Starter_Code/Resources/Crypto percentage change.png)

I compared both Crypto percentage plots and PCA Crypto percentage plot and realized that using fewer features to cluster the data using k-means made the clusters appear more tightly grouped, the clusters also became more distinct and it was easier to spot outliers in cluster 1 and and 3.



![PCA Elbow Curve](Module-10-challenge/Starter_Code/Resources/pca elbow plot.png)
![Elbow Curve](Module-10-challenge/Starter_Code/Resources/elbow curve.png)

When finding the best value of k the PCA data did not differ from when using the original data in this instance, inertia decreases more slowly from value 4 of K!
