# Corn Disease Detection
Prediction of Diseases in Corn Plants

# Research Paper

Other modern techniques to detect the plant disease - [Research Paper](https://github.com/SriDharshana/Corn-disease-detection/blob/main/plant_disease_detection_research_paper.docx)

# Abstract

Diseases affecting in corn are common nowadays . Suitable precaution need to be taken for preventing disease affecting the corn plants . Diagnosis of diseases by humans is time consuming and expensive . So using deep learning, diseases affected in corn plants can be detected and necessary reemdies can be taken soon. Leaf of corn plants is categorised as Blight disease/ Comman Rust disease/Gray Leaf Spot disease/Healthy Corn Plant. Model is built using convolutional layered architecture.

# Libraries and Functions used

1.Tensorflow - for numerical computations that makes the neural network faster and easier 

2.Numpy used for working with arrays

3.OS - for fetching contents from the directory

4.ImageDataGenerator - getting inputs for original data

5.Sequential - to create models layer by layer

6.Conv2D - applies sliding convolutional filters to 2-D input. 

7.MaxPool2D - Max pooling operation for 2D spatial data

8.Flatten - Convert multi-dimensional arrays into a 1-D array

9.Dense -  classify image based on output from convolutional layers

# Datasets
Leaf of various corn plants are taken as samples to classify them into 4 classes mentioned below:
_1.Blight disease_

_2.Gray leaf spot disease_

_3.Comman rust disease_

_4.Healthy corn plant_

# Visualization

Below images represent the visualization of Conv2D and Maxpool2D layer

**Conv2D**

![image](https://user-images.githubusercontent.com/86719672/210127737-d8aa7852-519a-4f15-bb4b-f985b679b251.png)

**Maxpool2D**

![image](https://user-images.githubusercontent.com/86719672/210127755-7c46dffc-b7bc-426c-9e5f-1684163b89f2.png)

**Evaluation Accuracy**

0.75
