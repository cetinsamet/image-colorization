# image-colorization
Simple image colorization with Pytorch to colorize black-and-white landscape images 
A convolutional neural network is trained with 800 grayscale landscape images to perform image colorization on gray images.
  
## Usage  
  
$**python3**  color_img.py  input-image-path  output-image-path  
*or*  
$**python3**  -W ignore color_img.py  input-image-path  output-image-path  
*(-W ignore can be used to avoid warning messages)*  
  
### Example  
  
$**cd**  src  
$**python3**  -W  ignore  color_img.py  ../test.jpg  ../out.jpg  
**->** Result image is saved to ../out.jpg  
  
![Test Image](https://github.com/cetinsamet/image-colorization/blob/master/test.jpg) ![Out Image](https://github.com/cetinsamet/image-colorization/blob/master/out.jpg)  
*Above two images are showing the performance of the model on a given random test image.*  
*Image on the left is a grayscale input image.*  
*Image on the right is the colorized output version.*  
  
*Whereas the groundtruth image(64x64) looks like this:*  
![Groundtruth Image](https://github.com/cetinsamet/image-colorization/blob/master/test_gt.jpg)  
  
*Still pretty good, huh :)*  
  
*P.S.* Model performs well on grayscale images of landscapes because almost all of the training data used are grayscale landscape images that you can see from the data folder with their groundtruth images (color64 folder).
