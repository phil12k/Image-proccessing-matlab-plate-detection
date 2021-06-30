# Image-proccessing-matlab-plate-detection
Given an image, you can preprocess it, do edge detection and remove noise . 
Smart parking system was created using vehicle number plate detection .

refer to matlab ppt for block diagram and methodology used in the project

Tempate_creation.m : Used to call the saved images of alphanumericals and save them as new template in MATLAB memory

Letter_detection.m : Reads the characters from input image and finds the highest matched correspondinhg alphanumerical

Plate_detection.m  : Process the image and calls the above 2 M-files to detect the number
