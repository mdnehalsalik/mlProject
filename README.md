# mlProject
This project implements a Support Vector Machine and convolutional neural network models of varying complexity to identify the most accurate modelto classify images of bees. 
The challenge is made difficult due to the fact that each image has a colorful background which is the flower the bee is pollinating.
Bombus and apis pollinate a variety of flowers and tend to be attracted to the same vibrant colors. The comparison shows that transfer learning and using a deep residual neural network architecture is by far the most effective way to classify this data.

# Achieved an overall accuracy of 89 percent with RESNET 50 Transfer Learning.

Group Authors: Md Nehal Salik,Tony Geglio, Alex Putman
Its a group project and we have created a different folder for each model.
Its an image classification project involving the bee image classification into different kind of bee.


# Instructions how to Reproduce the results:

EDA - Run Jupyter Notebook, data is in the EDA folder

SVM - the original bee image data is attached and will automatically load.

psuedo_resnet_20 - the original bee image data is attached and will automatically load. The augmented and black and white data sets must be created using the code. There are True False variables in the data loading section that can be modified to use the augmented and bw images. There are also models that can be loaded and plotted in tensorboard.

VanillaCNN - the original bee image data is attached and will automatically load. The augmented and black and white data sets must be created using the code. There are True False variables in the data loading section that can be modified to use the augmented and bw images.

Resnet50- the original bee image data is attached and will automatically load. The augmented and black and white data sets must be created using the code. There are True False variables in the data loading section that can be modified to use the augmented and bw images. Make sure the network is fed with rgb images without scaling.

Resnet20 - The weights can be loaded from the folder to reproduct the results.
