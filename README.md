# LSC
The SGD-auto notebook trains a network to generated alpha and s, and sends those alpha,s to the model described in the paper.
The SGD notebook saves alpha,s for each image individually for training, and updates the model params along with alpha and s during training. (validation is done with default code for the paper). The occlusion notebook uses the same network as SGD-auto to reconstruct real images from occluded input.
## TODO
* try whitening with MSE
* Fix omega generation for higher dim
* Try 3d projections
  * Make dataset
* Try rot-scale+translation dataset
* Try updating alpha and s in an inner loop on every W update
* Try adding an inner loop to update alpha and s, then do an update for W
