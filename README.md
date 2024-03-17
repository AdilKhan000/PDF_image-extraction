# PDF_image-extraction

#This script was written to automate the process of extracting images from a textbook pdf and write it to a pdf file.
#This script was written when my brother who is a medical student requested me to help him separate only images from his textbook.
 
Usage:
 Takes an input pdf.
 Gives the output images into a pdf file and stores all the images that generated an error into a separate folder.

Improvements: 
 #Can add a condition to separate the images with low pixels to be discarded as they can be useless images.
 #Sorting and labeling the images with the text below the images.
 #Creating a Rect of the image and then capturing all the contents inside the rect including text to capture images that include text content and images created with tinier images.