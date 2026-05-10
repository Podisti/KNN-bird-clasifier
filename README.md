# KNN-bird-clasifier
An implementation of a CNN for bird detection and classification for the FIT VUT course KNN.

## usage
The project is designed to run in google colab, leveraging their GPU. 

When running the notebook, the top cell is used to specify whether to train a new model (ResNet18 or ResNet50), or to run a pretrained model. Both options require google drive to be connected and when using a pretrained model, its path needs to be specified in the testing cell.

After running the training, or after loading the model, the test script will run automatic tests and will generate an evaluatuion report including all relevant quantitative information. (one report is attatched in the `/evaluation` folder)