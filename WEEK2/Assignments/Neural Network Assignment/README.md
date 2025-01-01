Assignment 2
In this assignment, you need to classify images into 2 classes using simple Neural Network.

Download the [Images](https://github.com/VarunSriTeja/WIDS--FaceCipher/blob/main/WEEK2/Assignments/Neural%20Network%20Assignment/homer_bart.zip) file.

Suggestions:

The images are of different dimensions, while importing/preprocessing convert all into (64x64) images.
Distribute them into batches (e.g. batch_size = 32).
Since the amount of images is less, no need to create validation dataset, go with training and test dataset only. Prefer 9:1 split between training and test dataset.
Use Dense i.e. Fully-Connecetd Layers with activation = 'relu' in each layer. Use activation = 'sigmoid' in the last layer.
metrics = 'accuracy' of test dataset will be checked only.
Mandatory:

Don't use Conv2D, MaxPool2D layers.
For passing the assignment, test dataset accuracy should be more than 90%. [Test Accuracy > 0.9]
BEST OF LUCK
