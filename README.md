# Cryptocurrencies

## Overview 

The purpose of the analysis is to provide ***Accountability Accounting*** an investment profolio of currently of currently traded cryptocurrencies. We will be using data from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist) in order to perfrom a an unsupervised Machine Learning model which will enable us to perfrom a clustering algorithm in order to group these cryptocurriencies together for a new investment opportunity. 

## Libraries 
- Scikit-learn
- Plotly 
- hvPlot
- Pandas

## Software 
- Python 3 
- Anaconda
- Jupyter Notebook 

## Application 

- Data Processing 
- Principal Component Analysis (PCA)
- Clustering Algorithms 
- Visualization 

## Results 

The original dataset contained 1,252 entries
![table](https://github.com/schoolboycamel/Cryptocurrencies/blob/main/Resources/total%20currencies%20.png)

532 of the total entries were tradable
![tradable](https://github.com/schoolboycamel/Cryptocurrencies/blob/main/Resources/tradable%20currencies%20.png)

Our ***Elbow Curve*** method showed a slope of 4, thus we used that number of clusters for the k means algorithm 
![Elbow curve](https://github.com/schoolboycamel/Cryptocurrencies/blob/main/Resources/elbow%20curve.png)

Plotted clusters in our 3D graph for visualization
![cluster graph](https://github.com/schoolboycamel/Cryptocurrencies/blob/main/Resources/clusters%20.png)

