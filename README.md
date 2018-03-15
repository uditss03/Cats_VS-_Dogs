# Cats_VS_Dogs

Cats and Dogs images are classified using Keras with tensorflow-gpu backend.

![tomand dog](https://user-images.githubusercontent.com/34382779/37469000-54fcf242-288a-11e8-82d3-e986ef4af395.jpg)

Other library used are ->

* cv2
* numpy
* matplotlib.py
* os

2000 training images and 500 validation images are resized to 100(img_width) X 100(img_height) X 3(BGR channels) dimension and 

Image is passed through 3 layer before flattening each involves->

* Convolving of image
* Activation of node with relu function
* MaxPooling of image

Flattening of all images
 
* 3 FC layer(relu) 
* Droupout of 0.5
* Softmax classifier for last layer

![conv](https://user-images.githubusercontent.com/34382779/37472678-ae3ec2a6-2892-11e8-99b2-890ba892daa5.png)



