# Image-Processing_Machine-Learning-Deep-Learning-

## Image Dataset and Task
For this, I'll be working with the CelebA dataset, a widely used dataset of celebrity faces. My task is to predict the hair colour of the celebrity, which will be one of black, brown, blond or gray.

I expect that, by default, I'll be developing solutions under Google Colab.  Images are relatively large data items, so I've produced a cut-down version of the dataset that should not cause any problems with Colab's memory limits.  It's cut down both in terms of image size, and number of items in the dataset.  I've also removed images that are labelled with more than one colour. Although we can use whatever data you like to train your model.  We also make available a devset that's separate from the training set.

For testing, there'll be a public test set and a private test set. The public test set is the standard one used for CelebA.  The private test set will stay private.

## Jupyter Notebook
This Jupyter notebook contains all the code I used to train my model(s) and make predictions on the test set, for both the conventional machine learning approach and the deep learning approach.

It also contains text blocks with comments explaining what each segment of code does. Besides, discussion of some reflection about the implementation and relative performance of my conventional machine learning and deep learning approaches.
