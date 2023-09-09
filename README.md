# Driver Drowsiness Alarming Project
 
This Python project's goal is to create a sleepiness detection system that can recognize when someone's eyes are closed for a brief period of time. When fatigue is found, this system will warn the driver.

We produced the dataset that was utilised to develop this model. We built a script that records the eyeballs from a camera and saves them to our local disc in order to construct the dataset. We divided them into their corresponding categories, "Open" or "Closed." The undesired photos that were not required for creating the model were manually removed from the data. About 7000 photos of people's eyes in various lighting environments make up the data. We have attached the final weights and model architecture file "models/cnnCat2.h5" after the model was trained using our dataset.


**The Model Architecture**
Convolutional neural networks (CNN), developed using Keras, were utilised to create the model that we employed. Convolutional neural networks are a specific kind of deep neural networks that excel at classifying images. In essence, a CNN is made up of three layers: an input layer, an output layer, and a hidden layer with potential for more layers. These layers are put through a convolution operation with a filter that multiplies their 2D matrices together.
