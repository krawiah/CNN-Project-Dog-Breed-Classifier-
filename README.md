# CNN-Project-Dog-Breed-Classifier-
Dog Breed Classifier (Capstone Project Report ~ Machine Learning Engineer Nanodegree)

Identifying dogs according to breeds is a crucial issue for dogs’ buyers, sellers, and even for veterinarian doctors. Each dog breed has certain physical and behavioural characteristics. Furthermore, knowing the breed will provide information such as future size and required care. These all at the end are reflected on the price and value of your dog. 

Having a handy solution such as an application which can identify the breed will improve and facilitate this task. This project shows a machine learning model which can predict the breed when provided a dog image and even it can predict the most resemble breed when the provided image is for human utilizing Convolutional Neural Networks (CNNs) technique.

This project provides a solution to predict dogs’ breed when provided with a dog image and it can predict the most resemble breed when provided with a human image.

It involves the utilization of Convolutional Neural Networks (CNNs) technique to build image classifier to achieve this goal.

The project involves applying the following steps:
1.Detect human using OpenCV’s with Haar feature based cascade classifiers.
2.Detect dog using pretrained VGG16 model. 
3.Predict the breed: classified images are passed to CNN to return the best breed match.

In this project the following datasets provided by Udacity will be used:
•	Dog dataset contains 8351 images. 
•	Human dataset contains 5750 images. 

The project utilizes the following modules:
•	numpy 
•	glob
•	pandas
•	matplotlib
•	cv2
•	tqdm
•	torch
•	torchvision
•	PIL
•	torchvision.transforms
•	ast
•	requests
•	os


