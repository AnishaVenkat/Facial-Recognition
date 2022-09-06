# Facial-Recognition

This project i have implemented facial recognition using siamese one shot neural networks.

Libraries used:

OpenCv
Tensorflow
Numpy

Siamese one-shot Neural network:

1.One-shot learning are classification tasks where many predictions are required given one (or a few) examples of each class, and face recognition is an example of one-shot learning.
2.Siamese networks are an approach to addressing one-shot learning in which a learned feature vector for the known and candidate example are compared.

We take 3 types of samples 
1. positive images --> true images used in training
2.anchor images --> real time images fed from the web-cam
3. negative images --> False images used in training

Here we construct an embedding layer for input and verification and output from embedding layer is passed distance layer , where distance is calculated between input and verification image and passed to Dense layer.

Loss function : BinaryCrossEntropy
Optimizer:Adam
Activation:Relu

The model is build with Kivy application in python.


![image](https://user-images.githubusercontent.com/26068822/188318107-472640db-9183-44cf-904b-b77b965265f8.png)
![image](https://user-images.githubusercontent.com/26068822/188318591-0278c5fe-77cc-48ff-aed1-074ec8a85d6b.png)
![image](https://user-images.githubusercontent.com/26068822/188319246-4d5f7529-8d7b-4167-bbeb-40542aac8478.png)
