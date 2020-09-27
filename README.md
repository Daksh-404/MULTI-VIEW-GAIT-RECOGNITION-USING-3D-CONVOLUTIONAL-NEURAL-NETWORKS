# MULTI-VIEW-GAIT-RECOGNITION-USING-3D-CONVOLUTIONAL-NEURAL-NETWORKS

## Introduction
I have written this code for this [research paper](https://mediatum.ub.tum.de/doc/1304824/1304824.pdf). It uses Keras with Tensorflow as backend. It uses CASIA-B [Dataset](http://www.cbsr.ia.ac.cn/english/Gait%20Databases.asp) to do subject subject\person classification using 3-D Convolution Networks on Gait Silhouette images obtained from the mentioned dataset. I will be adding the images of results and graphs in the coming future as my experiments with this model are completed.

## Main Goal
The objective of the research paper as given above can summarized as :
                              *Creating a model for maintaining view invariance in Gait Analysis*
                              
## Prerequisites
* Keras, Tensorflow, Python, Numpy, Matplotlib, pandas
* Reading and analysing the research papers
* Knowledge of 3D convolution neural networks
* CASIA-B Dataset and it's ordering and structuring inside the given zip file
* A lot of faith in one's self and willing to take risk with one's time!

So if you have done this, cheers! Let's go!

## Important Points
1. Referring to [this medium article](https://towardsdatascience.com/step-by-step-implementation-3d-convolutional-neural-network-in-keras-12efbdd7b130). Use Incognito to access the complete article!

1. I am taking 20 images out of the 6 walking sequences from each of the 11 viewing angles in 
normal/cooperative conditions for 124 total subjects

1. I have taken 20 more images out of the same above given categories for my testing data

__NOTE: the above method for taking inputs is going to be changed in the upcoming updates.__

## Upcoming Updates
* LSTMs (Spatio-Temporal feature extraction)
* SVMs
* with OU-ISIR [Dataset](http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitTM.html)
* ` .py ` script files will be available soon.
* Structure of the input data

__IMPORTANT: It is still under development. I will be trying the model with raw video clips instead of provided silhouette images__
