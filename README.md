# Image-Classification-Experiments

In this notebook, we're going to explore the use of a few different ways of setting up an image classification model. The images and more details are available here: https://tiny-imagenet.herokuapp.com/. The training set contains 500 images for each of 200 different classes. The validation set contains 50 images for each of the 200 classes.  First, we're going to load images from the tiny-imagenet-200 folder into a flattened format that is suitable for training any of the scikit-learn classifier models, such as a support vector machine (SVM) or logistic regression.  Later, we'll take advantage of data loading functions included in PyTorch that will preserve the 2D-shape of images and load batches instead of the entire training or validation set all at once.

**Neural Networks**

Data can be downloaded from http://cs231n.stanford.edu/tiny-imagenet-200.zip, which must be extracted into the same directory as Helpers.py and Image Classification.ipynb.

