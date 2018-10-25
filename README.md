# Number-2-Image-using-GAN
Takes a number and generates the images of those numbers. Trained on MNIST using DCGAN(Deep Convolutional GAN) .

Notebook has been created with markdowns and comments to make it self-explainable. Still, I'll try uploading a detailed explanation of the code.

If the given number is 85481, we convert that to [8,5,4,8,1] and create a batch of numbers and pass it through generator. Images generated for each number are stitched through matplotlib. Output for 85481 is 

![alt text](https://github.com/Murali81/Number-2-Image-using-GAN/blob/master/images_numb_Gan_mse_sftmx_cc_cc/output_img.PNG)

Generator outputs during Training

![alt text](https://github.com/Murali81/Number-2-Images-using-GAN/blob/master/images_numb_Gan_mse_sftmx_cc_cc/output_gif.gif)

Explanation:

The major difference you'll find here is the **Discriminator** part, i.e instead of classifying the image as real/fake, it classifies the image into real (10 classes)/ fake. Number of classes for the model are changed from 2 (real, fake) to 11 (0,1,2,...,9, fake)

# References

[1] O'Shea, O'Shea Research <a href="https://www.kdnuggets.com/2016/07/mnist-generative-adversarial-model-keras.html">MNIST GAN</a>
