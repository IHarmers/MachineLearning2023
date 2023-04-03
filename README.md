This repository contains the code that I had written for the course Machine Learning of the University of Groningen, as well as the corresponding group report. 

## Project Abstract

We have compared the performance of linear regression, ridge regression, random forests, k-nearest
neighbors (k-NN) and a convolutional neural network (CNN) on the CEDAR-CDROM database of
handwritten digits with a 50-50 split for the training and test sets. Moreover, we have implemented
principal component analysis (PCA) and prototype matching as our two preprocessing techniques in
addition to fitting the models on the unprocessed dataset. Linear regression was designated as our
baseline model and found to be the worst performing model overall with its misclassification rate
varying between 9.1% to 15%. The CNN was only trained and tested on the unprocessed dataset
and produced an error of 1.8%, which is the lowest misclassification rate achieved in this report. For
future work, we recommend performing cross-validation on the hyperparameters which were left on
their default settings during our runs and researching the possibility of data augmentation on the
training data fed into the CNN to increase the variability in the input data.
 
