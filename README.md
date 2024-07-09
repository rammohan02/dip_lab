# dip_lab
Lab and project work of digital image processing

# Lab1:

**Objective:** Humans can recognize the person even with different facial expressions and different styles like with and without specs, bread, and mustache. But it is difficult to build a system to recognize the person.

Problem statement:
Using the same camera, take 100 images of your face with  
* different face angles
* different distance from the camera to the face
* different illuminance 
*  different facial expressions
* different facial styles (as far as possible)
Try to take 10 images in each category. 

Then keep one image as a reference image and compute the root mean square error (RMSE) with the remaining 99 images. Plot the values in the graph with the number of images in the X-axis and RMSE score in the Y-axis. Convert the color images to grayscale images and plot one more graph.

# Lab2:

**Objective:** To understand the concept of aliasing and false contouring.

1. Convert the given Lena image to a grayscale image. Use the cv2.resize() to downsample the image with 4 sizes  (128*128, 64*64, 32*32, and 16*16).  Display  the original image, and down-sampled images with the same display size. Observe what happens
2. Downsample the grayscale Lena image with  8 different intensity ranges of values (0-255, 0-127, 0-63, 0-31, 0-15, 0-7, 0-3, and 0-1). (Note: Size of images are the same). And display all those 8 downsampled images  in the same size display area on the screen. Observe what happens


# Lab3:
1. Take a Lena image and convert it into grayscale. Create 10 noisy versions of the Lena image by adding additive Gaussian noise with the original image. Take the average of noisy images and display the same. Report the observation made.
2. Take a Lena image and scale it by factors of 1,2,0.5 using bilinear and nearest neighbor interpolation methods. Display the scaled images. Also, display the output of built-in functions for doing scaling by factors of 0.5,1 and 2. Compare the results.

Note: 
1. Write the user-defined function for image averaging (problem 1)
2. Implement bilinear and nearest neighbor interpolation methods using user-defined functions as well as built-in functions  (problem 2)


# Lab4:
Download the leaning tower of the PISA image and find the angle of inclination using appropriate rotations with bilinear interpolation.

# Lab5:
1. Do histogram equalization on pout-dark and display the same
2. Do histogram matching (specification) on the pout-dark image, keeping pout-bright as a reference image<br>
Note: Use predefined as well as user-defined functions for the above problems

# Lab6: 
Download Lena color image, convert it to a grayscale image and add salt and  pepper noise with noise quantity 0.1,0.2 upto 1 and generate 10 noisy images.

1. Do average filtering ( by correlating with the average filter ) of varying sizes for each image. Filter size can be 3*3, 5*5, 7*7. (In 3*3 filter all the values are 1/9, in 5*5 filter all the values are 1/25 and in 7*7 filter all the values are 1/49)
2. Similarly, repeat question 1 by replacing the average filter with the median filter.

# Lab7:
1. Swap the phase of the dog image and the magnitude of the Lena image and display the output.
2. Swap the phase of the Lena image and the magnitude of the dog image and display the output.

Note:
* Write a function to implement FFT for 1D signal.
* Implement the DFT function for an image using the FFT for a 1D signal using question 3.
* Consider the images of Lena and the dog images attached. Find the phase and magnitude of the dog and Lena images using the DFT function (in b).
* Compare the results with a predefined function

# Lab8: 
Image restoration
1. Consider the Lena grayscale image as f(x,y) and apply the Gaussian filter using the built-in function(let it be h). Call the resultant as g(x,y). Now find f(x,y) from g(x,y) using the formula g(x,y) = f(x,y) *h(x,y) (Hint: go through the solution of g = f*h given in the class apply the same for finding f)
2. In problem 1, find f(x,y) using g(x,y) = f(x,y)*h + n where n is the noise term. Add noise n using the inbuilt function of salt and pepper noise and find f. Display the results obtained.

# Lab9:
Create a concentric square image, with inner square pixel intensity values as 125 and outer square as 0 everywhere. Find the projection along the row, column, and diagonal with 45 degrees and 135 degrees. Reconstruct the image by applying a back projection algorithm using the following ways
1. the row projection only 
2. the row and column projections 
3. the row and column and diagonal 45-degree projections 
4. the row and column and diagonal 45 and 135-degree projections

# Project
Number Plate detection

