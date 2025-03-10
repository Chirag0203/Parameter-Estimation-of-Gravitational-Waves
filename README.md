# Parameter Estimation of Gravitational Waves

We sought to utilize a machine learning approach to perform parameter estimation on GWs. In this project, a normalising flow was implemented using algorithms from the Lampe and Zuko packages. The signal data was generated on our end to which noise was added to simulate raw data from space. This was then used to train the neural network. Subsequently, the network was used to perform inference on previously unseen data, which it was able to do at a very quick pace.

We also looked into implementing Singular Value Decompostion(SVD) to significantly reduce training time by reducing the dimensionality of the training data while still keeping its major features intact. Ultimately, we did not include this step in our final project due to time constraints.
