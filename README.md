# Image_processing

## What is Image Processing?
Mage processing is a method to perform operations in images in order to enhance them, extract useful information and analyze them for making decisions.Image processing is a subset of computer vision.

## Purpose of Image processing-
1.Visualization - Objects that are not visible.\
2.Image sharpening and restoration - A better image\
3.Image retrieval - seek for the image of interest\
4.Measurement of pattern - measures various objects\
5.image recognition - Distinguish objects in an image

## What is image? 
A digital image is an array or a matrix of square pixels arranged in columns and rows ,in others words 2d matrix.This pixels contains informations about colors and intensity.

## RGB Channels
Two dimensional colour images are also represented in RGB - 3 layers of 2 dimensional where thre layers represents res, blue and green.
## Numpy for images

For fliping, extracting features and for analyzing them Numpy is the most important library.

##  Thresholding

Thresholding is used to partition the background and foreground of grayscale images, by essentially making them black and white. We compare each pixel to a given threshold value. If the pixel is less than that value, we turn it white. If it's greater; we turn it black.Thresholding is the simplest method of image segmentation, a topic we will cover in more detail later. Thresholding let us isolate elements and is used in object detection, facial recognition, and other applications.It works best in high-contrast grayscale images. To threshold color images, we must first convert them to grayscale.

## Try more thresholding algorithms

What if I want to try more algorithms? Well scikit-image includes a function that evaluates several global algorithms, so that you can choose the one that gives you best results: the try_all_threshold function from filters module. Here we import it, use the function by passing the image and set verbose to False so it doesn't print function name for each method. And show results.

