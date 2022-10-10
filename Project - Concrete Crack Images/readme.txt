Source: mendeley.com 

Crack detection is importance for structural health monitoring and inspection of buildings. 
The dataset is consisting of 2 classes - i.  Images of cracked concrete (y = 1) 
                                         ii. Images of concrete with no cracks (y = 0)

The dataset contains 40,000 RGB or color images. 20,000 images with cracks or positives and 20,000 images with no cracks or negatives.
75% of the images will be used for training and 25% of the images will be used for validation. 

There are few challenges in this dataset that has to be considered:
i.   Cracks can be confued with noise in the background texture or foreign objects. 
ii.  Inhomogeneous illumination.
iii. Irregularities such as exposure of joining.

Firstly, the data will be loaded from Object Storage(IBM Cloud) to the notebook. Then, the image processing will be done on the dataset to convert into a vector.
A pre-trained model will be used, a neural network architecture that has an excellent performance. 
