# FraudDetectionUsingAutoencoders
Fraud detection is a technique to identify unusual patterns that do not conform to the expected behaviors, and are called outliers.

Autoencoders are unsupervised Neural Networks. They compress the input data to a lower dimension representation. It is a neural network that learns to predict its input. 

The dataset used is the Kaggle dataset for Credit Card Transactions which have some anomalies reported (fraud transactions). It has 284,807 transactions and among them, 492 transactions are labeled as frauds.

The Autoencoder will learn to identify the pattern of the input data. If an anomalous test point does not match the learned pattern, the autoencoder will likely have a high error rate in reconstructing this data, indicating anomalous data.

The same task is done using two different frameworks:
1. Keras 
2. H2O

Since the dataset is highly imbalanced, we see a good accuracy but bad precision and recall value. 

Credits and reference links:
https://bit.ly/2EFaVHC
https://bit.ly/2Ygab6C
https://bit.ly/2s2T6xr

![Plot of reconstruction loss, Data instances above the red threhold are classified as fraudulent transactions](https://miro.medium.com/max/846/1*Qx9SYp04dkhf4YOHNfg2iA.png)
