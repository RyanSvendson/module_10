# module_10 - Crypto Clustering

Uses unsupervised learning focused on clustering data to find patterns. 


## Technologies

Pyton 3.9
Jupyter Lab and Jupyter Notebooks
Python libraries: Pandas, Pathlib, hvPlot
scikit-learn


## Usage

After loading in the data, we want to see what's in the dataframe. 

![market data line plot](Starter_Code/Images/mod_10_1.jpg)

Then we prepare the data for use in using the Elbow method of finding the best value for 'k'

![Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.](Starter_Code/Images/mod_10_2.jpg)

Now that we have the best value for 'k', we can use the KMeans algorithm to cluster the cryptocurrencies according to the price changes of the cryptocurrencies provided.

![scatter plot of price change segments by price % change in 7days and price % change in 24hrs ](Starter_Code/Images/mod_10_3.jpg)

Now we Optimize Clusters with Principal Component Analysis and we repeat the process of finding the best value for 'k' and clustering. 

We can then compare the results side by side. 

## Contributors

Ryan Svendson
rsvendson@gmail.com