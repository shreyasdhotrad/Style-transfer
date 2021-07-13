# Style-transfer
### Style transfer is the technique that allows us to apply the style of one image to the content of another image. Here we use image representations derived from Convolutional layers of the pre-trained model, which extracts certain features from the image helpful for style transfer.
### The principle is to generate an image with the same "content" as a base image, but with the "style" of a different picture (typically artistic). This is achieved through the optimization of a loss function that has 3 components: "style loss", "content loss", and "total variation loss".
### A simple to use android application to apply adaptive art filters on your photos. This app uses TFLite to run the neural style transfer MobileNet V3 model on edge device (Android).


<p align="center">
  <img width="220" height="416" src="https://i.stack.imgur.com/AfYNn.jpg">
</p>

<h2><p style="text-align:center;">App Demonstration</p></h2>

![](https://i.stack.imgur.com/G5tXC.jpg)
![](https://i.stack.imgur.com/PzDq3.jpg)\
![](https://i.stack.imgur.com/r7C9H.jpg)
![](https://i.stack.imgur.com/yBiCf.jpg)

Steps-
* Select Content Image from either camera or existing image from files
* Crop the selected image 
* Choose from a list of 10 style images
* Tap on Save image to save style transffered image 

 
Drive link for Android source code
<https://drive.google.com/file/d/1Lf5SYc79olkEgJvCzFG8AXD449Ky8QaF/view?usp=sharing>
