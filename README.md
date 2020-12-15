# MultilingualScriptIdentification
Identification of script from natural images and to study on methods of handling images of variable size.


### Data Source: 
We have a collection of images containing short texts in a particular script.

This dataset of images are downloaded from : https://rrc.cvc.uab.es/?ch=8&com=downloads

The dataset has total 61,768 images and 6 type of scripts labelled as: Latin, Korean, Japanese, Arabic, Bangla, and Chinese.


### Approach:

Used three strategies for inputting images, which include squaring of the images to fixed size, padding the images to squares maintaining aspect ratio and with varying input sizes. The models proposed in this study are single-layer CNN model, Inception model, ResNet model and fully-convolutional network(FCN) model and did performance evaluation of these models using metrics of Precision, Recall and f1-score.
