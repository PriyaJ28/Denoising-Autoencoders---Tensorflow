# Denoising-Autoencoders
### Image Noise Reduction with Auto-encoders

![](https://github.com/PriyaJ28/Denoising-Autoencoders---Tensorflow/blob/master/keras_denoising_autoencoder_overview.png)

Autoencoders Tensorflow on MNIST dataset are Neural Networks which are commonly used for feature selection and extraction. However, when there are more nodes in the hidden layer than there are inputs, the Network is risking to learn the so-called “Identity Function”, also called “Null Function”, meaning that the output equals the input, marking the Autoencoder useless.

![](https://github.com/PriyaJ28/Denoising-Autoencoders---Tensorflow/blob/master/model%20pic.png)

>Denoising Autoencoders solve this problem by corrupting the data on purpose by randomly turning some of the input values to zero. In general, the percentage of input nodes which are being set to zero is about 50%. Other sources suggest a lower count, such as 30%. It depends on the amount of data and input nodes you have.

![](https://github.com/PriyaJ28/Denoising-Autoencoders---Tensorflow/blob/master/demo-%20initial.png)
![](https://github.com/PriyaJ28/Denoising-Autoencoders---Tensorflow/blob/master/demo-%20decoded.jpg)
