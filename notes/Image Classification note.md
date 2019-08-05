
Image Classification 

The image classification pipeline
- Input : a set of N images, each labeled with one of K different classes.
- Learning = learning a model = training a classifier
- Evaluation : we evaluate the quality of the classifier by asking it to predict labels for a new set of images that it has never seen before. (true answers = ground truth)

Nearest Neighbor Classifier - basic approach to an image classification problem.
The nearest neighbor classifier will take a test image, compare it to every single one of the training images, and predict the label of the closest training image.

ex. CIFAR-10 
training set of 50,000 images
we wish to label the remaining 10,000 images

How we compare two images?
compare the images pixel by pixel and add up all the differences
= given two images and representing them as vectors I1, I2, L1 distance.

