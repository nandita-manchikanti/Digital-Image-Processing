# Digital-Image-Processing

# Week1

Objective:
Human can recognize a person even with different facial expressions and different styles  such as  with and without specs, beard and  mustache. But it is difficult to build a system to recognize the person as the images taken of the same person are different( the corresponding pixel values are different). To understand the  difference between any two images of the same person's face, the following experiment may be done.

Problem statement:
Using the same camera, take 100 images of your face with
    1. different face angles
            2. different distance from the camera to the face
            3. different illuminance
            4. different facial expressions
            5. different facial styles (as far as possible)
Try to take 10 images in each category.

Then keep one image as a reference image and compute the root mean square error (RMSE) with the remaining 99 images. Plot the values in the graph with the number of images in the X-axis and RMSE score in the Y-axis. Convert the color images to grayscale images and plot one more graph.

# Week2

Objective: To understand the concept of aliasing and false contouring.

Convert the given Lena image to grayscale image. Use the cv2.resize() to down sample the image with 4 sizes  (128 * 128, 64 * 64, 32 * 32, and 16 * 16).  Display  the original image, and down sampled images with the same display size. Observe what happens
Down sample the grayscale Lena image with  8 different intensity ranges of values (0-255, 0-127, 0-63, 0-31, 0-15, 0-7, 0-3, and 0-1). (Note: Size of images are the same). And display all those 8 downsampled images  in the same size display area on the screen. Observe what happens

# Week3

1. Take a Lena image and convert it into grayscale. Create 10 noisy versions of the Lena image by adding additive Gaussian noise with the original image. Take the average of noisy images and display the same. Report the observation made.
2. Take a Lena image and scale it by factors of 1,2,0.5 using bilinear and nearest neighbor interpolation methods. Display the scaled images. Also, display the output of built-in functions for doing scaling by factors of 0.5,1 and 2. Compare the results.

Note:

1. Write the user defined function for image averaging (problem 1)
2. Implement bilinear and nearest neighbor interpolation methods using user defined functions as well as built-in functions  (problem 2)

# Week4

Download the leaning tower of the PISA image and find the angle of inclination using appropriate rotations with bilinear interpolation.

# Week5

1. Do histogram equalization on pout-dark and display the same
2. Do histogram matching (specification) on the pout-dark image, keeping pout-bright as a reference image.

Note:

Use predefined as well as user defined functions for the above problems
