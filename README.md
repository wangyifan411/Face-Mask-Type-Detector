# Face Mask Type Detector

![Example0](/test_snapshots/square_testing_GIF.gif)


This repository contains the code and Google Colab notebook for training a face mask type detector with [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection). 

The blog post of this project can be found on [Medium](). 

The model is used to detect face masks of 4 classes: homemade cloth covers, surgical mask, n95 mask and no mask. The corresponding labels are:
- homemade
- surgical 
- n95
- bare


### Dependencies on Windows 10
- Python 3.5
- TensorFlow 1.10

### [Notebook used for training on Google Colab](/face_mask_type_detection_ssdmobile.ipynb)


### Training image examples
The images used for training are from Google and Upslashe. There are 247, 197, 184 and 255 images for each class. 

- homeamde
![homemade](/test_snapshots/homemade_examples.png)


- surgical 
![surgical](/test_snapshots/surgical_examples.png)


- n95
![n95](/test_snapshots/n95_examples.png)


- bare
![bare](/test_snapshots/no_mask_examples.png)



### Model Output

- Testing on images from the Internet
![Example1](/test_snapshots/face_mask_testing_4.png)


- Testing with a friend in low light. All masks were labelled correctly!
![Example2](/test_snapshots/face_mask_testing_1.png)


- Test images from Raspberry Pi camera
![Example3](/test_snapshots/face_mask_testing_2.png)
