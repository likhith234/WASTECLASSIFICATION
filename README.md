#Introduction
This repo is for building an AI mode  to develop a CNN model to classify images of plastic waste into different categories 
This project is been done by myself and with the help of edunet virtual internship project 
#Data Set
The link of the data set is being provided, because of the large size of the data i am unable to upload it in the github

link: https://www.kaggle.com/datasets/techsash/waste-classification-data/data

#Week 1
So for my week 1 project is based on data visualization of the data set 
1) Displaying the image with its lable
2) Displaying the images with its labels in the form of grid to know the diversity
3) Visualization of the image dimension distribution in histogram
4) Visualization of the data proportion using the bar chat
5) Visualization of the data proportion using the pie chat(demonstrated in master class)
6) Visualization of image width and height  using the Scatter plot

Observation:
1)The images consists of recyclable and organinc materials
2)The images pixels comprises from 100 to 400
3)In pie chat we can see that the organic images occupy 55.69% and the recyclable images occupy 44.31%
4)In the histogram we can that the organic images are above 12000 and recyclable images are around 10000


#Week 2
1) So fist we visualized the images with its height and width
2) The second task was to find the best model for tarining the data
3) So for images we can use KNN and CNN but for better accuracy we use CNN
4) CNNs are specifically designed to extract features from images by leveraging their spatial structure, leading to significantly higher accuracy in complex image 
   recognition tasks.
5) While KNN struggles with high-dimensional data like images and may not effectively capture intricate relationships between pixels.
6) So we divided the model in 3 variations the 32 neurons, 64 neurons and 128 neurons in 2D.
7) Their after we flattened the image and used Dense to classify the images in 256 and 64 neurons varition
