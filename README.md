# Restricted-Boltzmann-Machine-and-Deep-Belief-Network-on-MINIST
Intelligent Systems for Pattern Recognition Midterm 2 (2021) : 

## Restricted Boltzmann Machine(RBM):
* Load the MINIST dataset.
* Define RBM model.
* Train RBM model.
### Define a classification model by placing a softmax layer after the RBM.
  * Train the classifier.
  * Build the confusion matrix.
### Define a classification model taking the RBM hidden states as embbedings.
  * Train the classifier.
  * Check the pretrained RBM layer weights to make sure it is updated.
  * Build the confusion matrix.
## Deep Belief network(DBN) :
* Define DBN model.
* Train DBN.
* Visualising DBN layer.
### Train a classification model by placing a softmax layer after the DBN.
* Build the confusion matrix.
### Train a classification model taking the DBN hidden states as embbedings.
* Build the confusion matrix.
## Plot the results.
* Plot raw last batch.
* Plot reconstructed last batch with propbalitys.
* Plot reconstructed last batch with sampled data.
* Plot the reconstruced first batch of test dataset.
## Try to apply affine transformation to the raw img, in result the classifier will make a wrong prediction on the new img.
* Define a composed transforms.
* Apply affine transforms.
* Check the prediction.
* Reconstruct the new img by RBM.
* Plot the reconstructed new img.
## Gibbs sampling (from random initial status) on Particular mnist.
## Reconstruct the uploaded images.
