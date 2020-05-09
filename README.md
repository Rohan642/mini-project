# MiniProject
 Origin of the Project : (Technicality and motivation behind this work should be elaborated)
 
               In this fast-moving world where digital media has become an important aspect of every citizen’s life, images play an important role in every field. Whether it be authentication, elaboration, or even as proof, images have been proven to be an important tool. But with the increase in usage of images in digital media, the crimes have also emerged and increased by manipulating the images using various image editing software. The manipulations can be small or on a large level like replacing hair to even the whole object or body from the image. With images being used to make decisions with heavy consequences, there exists a clear need for reliable forgery detection methods.


Other Similar ideas available on the internet (Please mention the origin of sources like website addresses, FTP address, etc): 

	Image splicing in one part of the image forgery detection in the cyber world, along with this we have several other techniques and work done on this field like Digital image forgery detection using passive techniques [1], Image forgery detection using adaptive over-segmentation and feature point matching [2], Image forgery detection using steerable pyramid transform and local binary pattern [3] and many more which all have a similar goal and that is to detect the manipulations done on the images.
	Facebook is working on DeepFake Detection [4]
	BelkaSoft makes software for the same [5].

The proposed project is definitely going to detect and decrease the cyber crimes that are occurring due to the abuses of images in the various fields where images are being treated as important part such as: in courtrooms as evidence of a crime, by car insurance agencies to evaluate damage after an accident, in magazines to sell products or brands, etc. Blindly trusting on the social media forwarded messages will be stopped.


Methodology: 	The task of the Machine Learning Model is to take input in the form of images and predict whether the input image is faked or real.
Based on the CASIA 2.0 dataset of 12389 images. 
a) Feature Extraction - Using GLCM, LBP, CSLBP 
b) Classification - Using SVM, Logistics Regression, and Random Forest
Training features are used to train the classifier model and test features are used to predict the class using the trained classifier model.
c) Improvements - Done using Normalisation of obtained data and Then using the Hybridisation of features. (Achieved 94% Accuracy )
d) Future Work - In the field of image recognition or image classification, deep learning is widely used. For the classification of images, CNN takes images as input, processes it on different layers, and classifies it into different categories.(Already Implemented the first file)


