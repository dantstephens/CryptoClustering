# CryptoClustering
Completed by Daniel Stephens

## About this project
This project demonstrates the deployment of unsupervised learning models to predict whether cryptocurrencies are affected by 24 hour or 7 day price changes. 

There are two parts to the project. The first uses the StandardScaler module to normalize data, which is then clustered using the K-means model. In the second part, the scaled data is optimized using Principal Component Analysis(PCA), before being clustered. Optimal k values to use with the models were determined using the elbow curve method. 

*Note: visualizations plotted in the notebook using hvPlot do not render when viewing the notebook in GitHub. To view visualiatons, the notebook will need to be downloaded from the repo and ran using VSCode.*

#### Running the app

To run the app: 
* Download the Crypto_Clustering.ipynb and Resources folder from this repo.
* Ensure that the Crypto_Clustering.ipynb notebook and Resources folder are located in the same folder before running. The app uses a static path to import data from a file in the Resources folder.
  

