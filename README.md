# LSC
The SGD-auto notebook trains a network to generated alpha and s, and sends those alpha,s to the model described in the paper.
The SGD notebook saves alpha,s for each image individually for training, and updates the model params along with alpha and s during training. (validation is done with default code for the paper)
## TODO
* try whitening with MSE
* Try occlusion
* Try changing s values to see effect on generated images
* Fix omega generation for higher dim
* Try 3d projections
* Try rot-scale+translation dataset
