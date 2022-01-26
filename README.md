# Cryptocurrencies

## The purpose of this analysis was to use unsupervised machine learning to analyze and cluster a dataset of cryptocurrencies to prepare a senior manager for writing a report to an Investment Bank for future offerings of a new investment portfolio options for its customers. 

## Project Overview:
1. Perform preprocessing on the dataset
2. Use PCA to reduce data dimensions
3. Cluster the cryptocurrencies using K-means
4. Create a visualization of the results

## Resources
- Source of data: [crypto_data.csv](https://github.com/mthalken/Cryptocurrencies/blob/main/data/crypto_data.csv)
- Software: Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0, Visual Studio Code 1.60.2
- Please see the refactored code [here](https://github.com/mthalken/Cryptocurrencies/blob/main/crypto_clustering.ipynb).

## Results 

After preprocessing, creating dummies, standardizing the data, and creating three principal components we used a elbow curve to find the best K value. We then used that value to create a K-Mean model with predictions. 

![png](https://github.com/mthalken/Cryptocurrencies/blob/main/images/3D_scatter_plot.png)

![png](https://github.com/mthalken/Cryptocurrencies/blob/main/images/tradable_cryptocurrencies_table.png)

![png](https://github.com/mthalken/Cryptocurrencies/blob/main/images/final_scatter_plot.png)


Using the dataset provided with 1252 cryptocurrencies we were able to identify a classification of 532 to use for the report and visualizations. 

Further analysis would need to be completed to determine their performance, investment potential, and quality fit for clients' needs. 

