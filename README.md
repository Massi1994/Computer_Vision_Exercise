## Computer_Vision_Exercise

## This repository was created to contain all the exercises done in this field of DEEP Learing.

1. Esercitazione1 - This is the first file and it contains some base functions to read .wav files and audios with python. Inside the notebook are present functions like the Furier Transformation, or the function to make a convolution of a sound with another.
2. Esercitazione2 - Inside this notebook there is the first application of an alghoritm to classify audios. In the first training set and test set are prepared shuffling the audios present inside a repository and associating to them a classification label. Then different type of feature are created, like the duration, avg or mfcc.
In the second part different combinations of features are combined to find out which is the best one and which one helps us more to classify corretcly the audios.
3. Esercitazione3 - In this notebook we can see different ways to show an image. There are different libraries that can be used to show images; in our case we will use the skimage library, but also the Pillow or OpenCV libraries can be used.
In this notebook we see how to show just one of the different RGB canals, we can reshape an image or change the colors of an image from RGB to black and white.
At the same time inside the notebook we make an exercise to improve the definition of the image using an Unsharping Mask:
  1. First we calculate the blurred image using a gaussian filter
  2. Then we subtract this from the original image
  3. Then we add the result to the original image to obtain the result with better definition.
