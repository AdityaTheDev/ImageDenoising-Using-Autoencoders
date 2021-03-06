# ImageDenoising-Using-Autoencoders
I built a Denoising Autoencoder to remove noise from the image. Image Denoising is the process of removing noise from the Images  The noise present in the images may be caused by various intrinsic or extrinsic conditions which are practically hard to deal with. The problem of Image Denoising is a very fundamental challenge in the domain of Image processing and Computer vision. Therefore, it plays an important role in a wide variety of domains where getting the original image is really important for robust performance. 

Denoising autoencoders are a stochastic version of standard autoencoders that reduces the risk of learning the identity function. Autoencoders are a class of neural networks used for feature selection and extraction, also called dimensionality reduction. In general, the more hidden layers in an autoencoder, the more refined this dimensional reduction can be. However, if an autoencoder has more hidden layers than inputs there is a risk the algorithm only learns the identity function during training, the point where the output simply equals the input, and then becomes useless.
Denoising autoencoders attempt to get around this risk of identity-function affiliation by introducing noise, i.e. randomly corrupting input so that the autoencoder must then “denoise” or reconstruct the original input.

I built an Autoencoder using the images of Brazilian model Adriana Lima which I found online. To the orginal image, I added GAUSSIAN NOISE and corrupted the pixels. Then passed the corrupted images as the input to the AutoEncoder, trained for 150 epochs and Predicted the output image which is denoised(Noise removed) image. The output images has removed a large volume of GAUSSIAN NOISE which is apparent from the output given below. 
The first row image represents the orginal images,
The second row represents the Noise added images,
The third row repressents the Denoised images(Predicted).

![Output images](denoised.png)
