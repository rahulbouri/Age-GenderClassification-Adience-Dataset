# Age-GenderClassification-Adience-Dataset

##ADIENCE DATASET ZIPPED FOLDER:
'https://drive.google.com/file/d/1QpvTFJrsJlqnJ1oF7_iXdj0ub1iun8xq/view?usp=sharing'

##TRAINED MODEL:

The model has been trained with different number of epochs. The model
trained for 3 epochs is at the risk of overfitting the data and hence
users have been given both options. Model trained on just 1 epoch has a
training accuracy of 98% and Validation Accuracy of 100%.

The trained models have their PyTorch weight files uploaded to the
repository itself.

##CONTENTS OF JUPYTER NOTEBOOK:

-Downloading and root the Audience Dataset folder

-Follow preprocessing steps as mentioned in the notebook attached

-Concatenate all csv files and add columns for their respective image
paths

-Bin the age groups into 8 classes (mentioned in the code file)

-Now factorise and create 16 classes (since 8 age groups x 2 gender
groups)

-Construct CustomDataset Class

-Extracts images from directory for training

-Performs appropriate transformations to the images

-Extracts the respective label for each image from the csv file

-Create a 80-20 training and validation split and create data loaders
for training and validation set

-Perform one hot encoding of the labels for the training set

-Construct Model Architecture (reference:
'https://talhassner.github.io/home/projects/cnn_agegender/CVPR2015_CNN_AgeGenderEstimation.pdf')

-The model has 3 convolutional layers

-Followed by 3 fully connected layers

-Define the optimiser, scheduler and loss function

-Start the training process and evaluate the training and validation
accuracies
