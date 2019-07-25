# Single-Class_Classification-Using-Autoencoder

+ A convolutional autoencoder is created and trained on images of person with dimension 28x28.

+ Architecture was used from [Keras Convolitional Autoencoder](https://blog.keras.io/building-autoencoders-in-keras.html).

+ The network is trained end to end using only positive class samples.

+ To check whether a test sample belong to positive class or not, it is passed through the trained network and cosine similarity is calculated between the input and predicted output.

+ The output for cosine similarity should be high for the positive class test sample and should be low for negative class sample.
