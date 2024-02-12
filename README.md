# Neural Style Transfer Implementation Walkthrough

Neural Style Transfer is a way to combine the artistic style of one image with the content of another image in order to produce a singular image (e.g. A picture of an elephant done with Picasso's cubist style, given through an image of one of his paintings)

This idea is relatively easy to understand and has very visual outputs which help us understand more of what is happening intuitively.

In this scenario we want to define two loss functions and minimise them. The first loss function being the distance between the content image and the target image. The second loss function being the distance in style between the style image and the style of the content image.

