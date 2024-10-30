# MyImageClassifier Command Line
A Python application that can train an image classifier on a dataset, then predict new images using the trained model.

Train.py and Predict.py works from the command line too.

Training a network
train.py successfully trains a new network on a dataset of images and saves the model to a checkpoint

Training validation log
The training loss, validation loss, and validation accuracy are printed out as a network trains

Model architecture
The training script allows users to choose from at least two different architectures available from torchvision.models

Model hyperparameters
The training script allows users to set hyperparameters for learning rate, number of hidden units, and training epochs

Training with GPU
The training script allows users to choose training the model on a GPU

Predicting classes
The predict.py script successfully reads in an image and a checkpoint then prints the most likely image class and it's associated probability

Top K classes
The predict.py script allows users to print out the top K classes along with associated probabilities

Displaying class names
The predict.py script allows users to load a JSON file that maps the class values to other category names

Predicting with GPU
The predict.py script allows users to use the GPU to calculate the predictions
