# notmnist-exploration

Exploration of Udacity's notMNIST dataset which consists of 28x28 images of letters in various fonts. We employ PCA and t-SNE to reduce the dimensionality of the data and visualize it. A neural network is trained and we observe what features and structure it detects to differentiate letters, and which inputs confuse it. Many font variations and non-letters are found in the training set (even within the same class) which can guide next steps for cleaning the data and improving future classification models. 

Inspired by recent research on adversarial examples, we also demonstrate that the network's learned weights can be used to generate inputs which it misclassifies with a high confidence.

This analysis was done in Winter 2018 for an end-of-semester project (ST4240) at the National University of Singapore.
