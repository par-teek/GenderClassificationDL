# GenderClassification

traing.ipynb trains a binary classification model to classify a face as male or female.
This tensorflow model is based on deep learning.
It's cnn that's trained on a dataset consisting of 47k training images and 12k validation images
Achieved 96% accuracy in training and 95% on testing
Then saved it as a .h5 model to load in testing.ipynb
testing.ipynb is based on OpenCV and uses openCV haar cascode to detect a face in realtime
Then that face is classified as male or female on the basis of pretrained gc.h5 model in real time
