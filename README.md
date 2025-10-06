# MNIST-Analysis

---------------

It is one of the most famous dataset in the field of Machine Learning and Computer Vision.

It is often referred to as the "HEllo World" of Image Recognition.

**Dataset:**
The MNIST dataset is a collection of 70,000 handwritten grayscale images.
* The images are of single digit from 0 to 9
* Each image is a small, square 28x28 pixels.
* pixel values ranging from 0 (white) to 255 (black).
* Every image is labeled with the corresponding digit it represents. This makes it an excellent dataset for **supervised learning** tasks.

**Division**
-----------

Training set : Contains 60,000 images

Test Set : Contains 10,000 images


The dataset is large enough to be non-trivial but small enough to be easily downloaded and processed on a standard personal machine, making it very accessible.


**Data Matrix**
------------

The MNIST training data matrix have 60,000 rows and 784 columns $(28 x 28)$ pixels
* Each row represent one handwritten letter.
* Each column represents a specific feature of the samples. For image data, the features are the individual pixel values. 
