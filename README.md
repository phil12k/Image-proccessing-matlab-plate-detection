# Image-proccessing-matlab-plate-detection
Given an image, you can preprocess it, do edge detection and remove noise . 
Objective of this project is to recognize vehicle number plate license .
View the methodology in the Matlab ppt 2 file 




Template_creation.m : Used to call the saved images of alphanumericals and save them as new template in MATLAB memory

Letter_detection.m : Reads the characters from input image and finds the highest matched correspondinhg alphanumerical

Plate_detection.m  : Process the image and calls the Letter_detection.m and Template_detection.m M-files to detect the number
