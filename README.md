# This is my repository for module CE888. 

# The CE888 Project 1 - Final is the file to be viewed for assignmnet one of the coursework. 

# The first part of my code sets a path to where the FLAME images are stored on my desktop and uses the glob.glob. function and a for loop to iterate through the images and the cv2. function reads the images and stores them into a list. This is repeated for each sub folder of images. 

# MatPlot is then used to visualise some random images which quickly highlighted that they are in the wrong colour format. This is not essential but I have left these on the script to demonstrate my progression with the task 

# The images are then loaded again using tensorflow, first specifying some augmentation using the ImageDataGenerator and importing them with flow from my directory, importing the images, spliting them into a test/validation set, and augmenting the training set silmaltaneously. 

# Another version of this of this is explored later in the script but is commented out. 

# In retrospect I have spent a significant amount of time trying to run the data in a CNN and perhaps should have spent more time focusing on EDA and visualisation of the data. 

