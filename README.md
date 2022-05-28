# Artistic-Image-Generation-using-Neural-Style-Transfer BE Project

## In this modern day, with advancement in Imaging technology immeasurable amount of images/pictures are generated per day. Photographs show the content as it is and what if we want this photographs to look as it was a piece of art?

## This project tries to perform the exact same thing as mentioned above. Style transfer means that the style (textures/strokes/shapes) from one image is applied to another image. The foundation is transfer learning where a model which is pre-trained to solve a purpose ‘A’ is actually used to accomplish a different purpose ‘B’ (for which the model was not explicitly trained).

## Thus for style transfer VGG 19 pre-trained model has been used, which is actually an object detection model. A style transfer pipeline is devised by adding various components & making modifications to the layers of the VGG19. This pipeline helps to capture the style and content representation of the images. Optimization is done in terms of style and content to generate an output image with the content of content image & style of style image.

## To preserve the overall color scheme of the content image in the output image an improvement was employed known as color histogram matching. Where the style image was transformed according to the content image in terms of color. 

## After doing histogram matching, visual improvement was observed in the output image. 
