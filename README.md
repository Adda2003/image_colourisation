# image_colourisation
# AIM: take a black and white image as an input and producing its coloured version as an output
# we here will use LAB colourspace as here we will give input of L channel and model will predict its corresponding a and b channel and concatinate the a and b channel with the L channel and we will get our desired output
#for this we will use GAN model which is a competitive model between the generator and the discriminator to get an output image as close to being a real image
#STEPS TO ACCESS THE PROJECT:
 1) download python and in the google colab download fatsai==2.4 
 2) download image from coco dataset for our training and testing sample
 3) rest instructions are provided in the code using the comments
# credits: https://towardsdatascience.com/colorizing-black-white-images-with-u-net-and-conditional-gan-a-tutorial-81b2df111cd8
