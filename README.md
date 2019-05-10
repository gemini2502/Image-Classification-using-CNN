# Image-Classification-using-CNN

The Folder contains training and testing dataset in Train and Test folders respectively.
Each subfolder in Train directory contains 4 classes - A,B,C,D with their annotations as bounding box in labels.txt

The format of annotations is as follows:

> path/to/image.jpg,x1,y1,x2,y2,class_name

where x1,y1 represents the top left coordinate of the BBox and x2,y2 represents the bottom right coordinate of the BBox.


The task is to train a deep learning model using any of the frameworks like pytorch,tensorflow,keras etc which can classify the images in one of the category as A,B,C,D

Evaluate their trained model on the images present in the subfolders t1,t2,t3 and t4 of Test folder.

The output images should be written in the same folder t1,t2,t3,t4 with the prefix "pred_"  before it.


Should only use deep learning architectures to train the model.


The accuracy will be measured by the following performance metric: 
(Total No of Truly classified Images/ Total No of Images) *100
