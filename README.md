# image_rotation
Image Rotation , built using OpenCV library in c++

# Description:
This is a C++ program to rotate the input file(image) by the use of wrafAffine funtion which is inbuilt in the opencv library. wrafAffine takes 4 parametres. First is source image file , second is destination image file ,  third parameter is mat object that is ouput after rotating with some point taking into reference and last is taking the size.

#Applications:
- Face Recognition
- Count - people, objects, vechicles
- Object Recognition
- Anomaly Detection

#Steps to be followed:
1) Install openCV with Visual Studio
2) Include all necessary header filesfor your application
3) Using namespace cv
4) read and load the image and display/output image

# Header Files Used
 * #include<opencv2/opencv.hpp>
 * #include <opencv2/core/core.hpp>
 * #include <opencv2/highgui/highgui.hpp>
 * #include <opencv2/imgproc.hpp>
 * #include <iostream>
  
 #Functions Used:
 * imread()
      This will read your image
 * image.empty()
      If anyhow image is not found at the time of processing then it will go to this block
 * named window(windowname)
      For creating a image you need to open a window, so we create a new window
 * imshow(windowname, image)
      
  

