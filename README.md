# image-colorization
Simple image colorization with Pytorch  
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
  
