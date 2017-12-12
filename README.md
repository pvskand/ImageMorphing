# ImageMorphing
Image morphing

## Team
Aakarshan Gupta (2014CSB1001)
Skand Vishwanath Peri (2014CSB1034)
This is the README File
It contains the following :

1) DIP4_2014CSB1001_AakarshanGupta 1.cpp
2) images -  A folder in which the morphed images are stored
3) Make file
4) report.html - A html report showing gif images.
5) Three Morphing - A folder containing sample input for morphing between 3 images.
6) Two Morphing - A folder containing sample input for mophing between 2 images.
7) Report Images - A folder containing images that are used in the report.
8) This README

-----------------------------------------------------------------------------------------------------------------------------
## Compile Instructions: 
In order to compile the code type the following statements in the terminal:
1) cmake .
2) make

## Run Instructions :
Now in order to run the cpp code, there are 2 types of input format:

For morphing between 2 images
`./DIP4_2014CSB1001_AakarshanGupta 1 image1.jpg image2.jpg`

For morphing between 3 images 
`./DIP4_2014CSB1001_AakarshanGupta 2 image1.jpg image2.jpg image3.jpg`

###### Here 1 and 2 are the experiment numbers i.e 2 image morphing or 3 image moprhing.
-----------------------------------------------------------------------------------------------------------------------------
## Input format for Tie Points:
##### The tie points are to be kept in a text file with the name "input.txt".
##### For morphing between 2 images : The format should be "x_1 y_1 x_2 y_2" where x_1, y_1 are the coordinates of the point in image1 and x_2 y_2 are the coordinates of the point in image2 corresponding to the image1.
##### For morphing between 3 images : The format should be "x_1 y_1 x_2 y_2 x_3 y_3" where x_1, y_1 are the coordinates of the point in image1 and x_2 y_2 are the coordinates of the point in image2 corresponding to the image1 and x_3 y_3 are the corresponding tie points in the image3.
-----------------------------------------------------------------------------------------------------------------------------
### NOTE : 
- All the image size must be the same. 
- Between two images we have considered 30 frames.
-----------------------------------------------------------------------------------------------------------------------------
## Sample Output GIFs

![Morphing of 3 images](ReportImages/three.gif)

![Morphing of 3 images](ReportImages/two.gif)

