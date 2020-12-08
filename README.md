# Traffic_Sign_Detection
# DATA-602_1 Traffic Sign Detection#


*Contributors:*
  Rushabh Shah
  

#*Overview*:#

Self driving cars is the future at which the car industry is looking at. Lane-detection, Traffic-light detection, Traffic- signs detection etc. are the part of automation that are very essential for automation in self-driving cars. The automation in these fields are yet to be accurate and need more accuracy. We will use Convolutional Neural Networks for image classification in this project. In this project we will use keras to define a model, estimate model performance, improve and save model. We will also try to compare different models and decide which will be more appropriate for the task in hand. 


#*Project Goal*:#

The goal of this project is to use image classification that is a supervised learning technique using Convolutional Neural Networks to detect traffic signs. The secondary goal is to use different model to get the best results and achieve an accuracy of 95-99% for the same.


#*Motivation:*#

Automation is progressing in the information technology universe for making it easy for the mankind. Having a dream to work in an automation industry and being a data scientist this project will give me an opportunity to learn how to use image classification with the help of neural networks.


#*Methods Applied*#

1. OpenCV for transformation of dimension.

2. Imread for reading images.

3. Keras and Convolutions layers to define models for image classification.

4. Flatten, dense and soft max layers for fine tuning.

5. Two models used with different activation functions which are relu and tanh.


#*Data Summary:*#

The German traffic signs detection dataset is provided by [Benchmark](https://benchmark.ini.rub.de//) . 

Data summary is available [here](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

The dataset has 39209 images with 43 different classes. 

The images have been distributed unevenly between those classes and hence the model may predict some classes more accurately than other classes. There are no missing values or any discontinuties in the dataset.

We will be training the model on the original dataset and will see the accuracy of the model. Then we’ll be adding more data and making each class even and check the model’s accuracy.

License: CC0: Public Domain


#*Summary of files:*#

Data Source:

["Benchmark German traffic signs"](http://benchmark.ini.rub.de/)

Notebooks:

["EDA"](https://github.com/Rushabh771995/Traffic_Sign_Detection/blob/main/Notebooks/EDA.ipynb)

["Technical Notebook (Traffic sign detection)"](https://github.com/Rushabh771995/Traffic_Sign_Detection/blob/main/Notebooks/Traffic_Sign_Detection_Technical_Notebook.ipynb)
           
Images:

["Images"](https://github.com/Rushabh771995/Traffic_Sign_Detection/tree/main/images)


#*Softwares and Packages:*#

Project Info:

Contributors: Rushabh Shah.

Languages: Python.

Tools/IDE: Colab

Libraries: pandas, matplotlib, scipy==1.1.0, wget, opencv, tensorflow, keras, seaborn, os, imread, randomizer.

Duration: December 2020.
 
