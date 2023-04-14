# 3D-shape-recognition

## 1. Task ##

The task is to identify Multi-view 3D shape objects. The problem can be solved using Deep Learning Method such as CNN.

## 2. Import Data ##

First the dataset is imported and explored through the OpenCV module to get the overview of the image.

## 3. Data Generator ##
 
 Using pre-defined data generators from tensorflow and pytorch has it's own limitation and cannot be used for difficult task such as identifying objects from multiview. Hence a **custom data generator** has been built to solve the data processing task. The data is passed as batches into array containing all the four views of the object.
 
## 4. Model Building ##

For this task CNN architecture has been used to solve the problem where all the **four views** are combined to identify the object. The architecture consist of 3 layers of neural network.

## 5. Evaluate Model ##

The model has been evaluated using accuracy and the performance of the model is carried out on the unseen data.
 
