# cf_testing

This subrepository contains the instructions and data required for the Computer Vision test.

### DESCRIPTION ###

IMPORTANT: The code should be written in Python v3+

The task is to make an image classifier which can detect if the given image is of Pikachu or not. 

You are free to consult the internet and use any libraries as needed. 

### DATA ###

You can find images of pikachu and not_pikachu in the attached dataset: "pikachu_dataset.zip"


### SUGGESTED APPROACH ###

You are suggested to follow the following steps for your image classification:

* divide the images into a train and test set
* normalize the data
* do feature extraction (think of which features can be more useful. example: colors, gradients, etc..)
* train your classification model based on your extracted features
* test it against the test set and get performance scores (accuracy, f1, etc ...)
* save your trained model as a pickle file
* design your code so that we can later use some external images to test on your saved model (IMPORTANT!)

Bonus:

* do k-fold validation
* train your model against adversarial attacks (images of other pokemon should not be classified as Pikachu) You can use more data from the web if need be.

### DELIVERABLE ###

Send an email to provisioned mail address athar@contract.fit with the following in 1 ZIP:

* Your code
* Instructions to run the code
* Your pickled/serialized model
* Achieved results (small report: use appropriate metrics!, max 1 paragraph)
