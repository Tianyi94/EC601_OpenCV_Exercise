# Question 1: 
ColorImage.cpp is a program that takes a look at colorspace conversions in OpenCV. Run the code in ColorImage.cpp and comment on the outputs. Implement the same thing in Python and save each image.<br />
The outputs are 10 images, including the original image, and the images of each channel in RGB, HSV, YCbCr. The python code and the pictures are in this folder.<br />
# Question 2: 
Print out the values of the pixel at (20,25) in the RGB, YCbCr and HSV versions of the image. What are the ranges of pixel values in each channel of each of the above mentioned colorspaces?<br />
The outputs for image Lenna are as follow: <br />
---
('RGB part', array([106, 122, 225], dtype=uint8))
('HSV part', array([  4, 135, 225], dtype=uint8))
('YCC part:', array([151, 181, 103], dtype=uint8))
---
Range of R,G,B : 0~255, 0~255, 0~255<br />
Range of Y,U,V : 16~235,16~240,16~240<br />
Range of H,S,V : 0~180,0~255,0~255<br />
