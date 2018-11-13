# Number-2-Image-using-GAN
Takes a number and generates the images of those numbers. Trained on MNIST using DCGAN(Deep Convolutional GAN) .

Notebook has been created with markdowns and comments to make it self-explainable. Still, I'll try uploading a detailed explanation of the code.

If the given number is 85481, we convert that to [8,5,4,8,1] and create a batch of numbers and pass it through generator. Images generated for each number are stitched through matplotlib. Output for 85481 is 

![alt text](https://github.com/Murali81/Number-2-Image-using-GAN/blob/master/images_numb_Gan_mse_sftmx_cc_cc/output_img.PNG)

Generator outputs during Training

![alt text](https://github.com/Murali81/Number-2-Images-using-GAN/blob/master/images_numb_Gan_mse_sftmx_cc_cc/output_gif.gif)

Refer to this <a href="https://medium.com/@kmanoharmurali/friendly-introduction-to-gans-357cf0a99a6e">article</a> for a better understanding of GANs.

# References

[1] O'Shea, O'Shea Research <a href="https://www.kdnuggets.com/2016/07/mnist-generative-adversarial-model-keras.html">MNIST GAN</a>

[2] <a href="https://datascience.stackexchange.com/questions/6107/what-are-deconvolutional-layers">Deconvolution(Unsampling and Conv) in Generator</a>

