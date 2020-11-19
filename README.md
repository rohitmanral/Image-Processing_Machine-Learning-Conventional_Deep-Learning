# Image-Processing_Machine-Learning-Deep-Learning-

## Image Dataset and Task
For this, I'll be working with the CelebA dataset, a widely used dataset of celebrity faces. My task is to predict the hair colour of the celebrity, which will be one of black, brown, blond or gray.

I expect that, by default, I'll be developing solutions under Google Colab.  Images are relatively large data items, so I've produced a cut-down version of the dataset that should not cause any problems with Colab's memory limits.  It's cut down both in terms of image size, and number of items in the dataset.  I've also removed images that are labelled with more than one colour. Although we can use whatever data you like to train your model.  We also make available a devset that's separate from the training set.

For testing, there'll be a public test set and a private test set. The public test set is the standard one used for CelebA.  The private test set will stay private.

## Jupyter Notebook
This Jupyter notebook contains all the code I used to train my model(s) and make predictions on the test set, for both the conventional machine learning approach and the deep learning approach.

It also contains text blocks with comments explaining what each segment of code does. Besides, discussion of some reflection about the implementation and relative performance of my conventional machine learning and deep learning approaches.

## Image Dataset Details
### Dataset Format
As noted in the project Description, you'll be working with the CelebA dataset, a widely used dataset of celebrity faces.  We have produced a version that has been preprocessed from the original dataset in a few respects:

The labels have been set for the task in this assignment.
It contains a subset of the original images.
The images have been reduced in dimension, so they're now 48x48, but still with 3 colours (so 48x48x3 overall).
The preprocessed dataset has been split into train, val and public_test data that is consistent with the standard splits used for CelebA.

For each of the data splits, there are three files:

X_images.npy -- contains the images as a list of 48x48x3 tensors;
X_images.npy -- contains the labels as a list of integers from the set {0, 1, 2, 3};
X_files.npy -- contains the file names of the image files as a list of strings of the form xxxxxx.jpg.
where X in the npy filename is one of {train, val, public_test}.  The labels [0 1 2 3] correspond to hair colours ['black', 'blond', 'brown', 'gray'].

npy files are a standard format for files using numpy.  
