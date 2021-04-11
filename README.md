# Gender-Recognition-and-Age-Estimator
Face and gender detection using keras and tensorflow
We have  pertained model which is weights.18-4.06.hdf5( which could not be uploaded since its size is 186mb larger than 25mb which is allowed in github) which has been trained on more than 10,000 images so it will be easily able to classify images based on gender and age. 
We use resnet neural network and opencv.
In the code we first give the for haarcascade_frontalface_alt which is present in our pertained model.
We used classes to create different functions.
we first call the main() function  which calls the def main() which calls the facecv() method as soon as facecv() method is called it picks up the haarcascade_frontalface_alt and weights.18-4.06.hdf5
after that we call the def init where we will load all the weights of the neural network and the neural network code that is the wide_resnet.py which is 2 layer convolutional neural network in which we use batch normalization and averagepooling not maxpooling or minpooling
which helps us to give a good result
