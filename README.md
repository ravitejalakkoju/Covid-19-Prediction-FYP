## Covid-19 Prediction using X-Rays

###### ABSTRACT
The **Covid-19 (also known as SARS-COV-2)** that first occurred in Wuhan, 2019 which spread around the whole world like a wildfire. This contagious disease spreads from person to person through direct contact to another. The effects of Covid-19 can be classified into different scales from mild to severe. At the time of writing this paper a total of 148 million cases and 3.1 million deaths are confirmed. Most of the Covid-19 detection are done with RT-PCR tests which generally take time. Depending the critical scenarios and demands it might even take longer. For a contagious disease like covid-19 the main goal is to restrict it’s spread. So, with the help of Machine Learning and Deep Learning Algorithms that are built on Radiology images could help in making the decisions for diagnosis of Covid-19 patients. We proposed in using Transfer-Learning based model for Covid-19 Detection using chest x-ray, because of the scarcity of available data. We performed Transfer Learning approach in order to obtain reliable results which could help us with smaller dataset. Though the x-rays do not provide maximum confirmation we rely the minimal percentage of chance that could help in reducing the spread of Covid-19. The process consists of two phases where in the first we pre-process the images and in the second we train and finetune the model to achieve desirable accuracy of the model.

Publicly available **X-ray images (1583 healthy and 712 confirmed COVID-19) AND (712 COVID-19, 4273 Pneumonia and 1583 Normal)** were used in the experiments, which involved the training of deep learning and machine learning classifiers. 5 custom CNN (Convolution Neural Network) experiments were, and 5 experiments for both categorical and binary were performed using Transfer Learning Models with ImageNet set as weights.

> Keywords: Covid-19, SARS-COV-2, Deep Learning, Pre-Processing, Transfer Learning, Pandemic

The link for the documentation -> [click here](https://drive.google.com/file/d/1IftheSnUZDSqjPzqzxi2SbK6JBuHV-6p/view)

###### Getting Started
To use our model, first, clone our repository to your local machine.

> git clone https://github.com/ravitejalakkoju/covid-19-prediction-fyp.git

###### Prerequisites
Our code is written in Python, and the following packages are required for running our code:

```
TensorFlow
Keras
OpenCV
NumPy
Matplotlib
```

To install these packages, run:

> pip install tensorflow keras opencv-python numpy matplotlib

###### Usage
Our repository contains the code for pre-processing the images, training the model, and testing the model. Follow the instructions in the Jupyter notebook to perform these tasks.

###### Results
Our proposed Transfer-Learning based model achieved an accuracy of X percent, demonstrating its effectiveness in Covid-19 detection. The model can be used to make quick and accurate diagnoses, which is crucial for controlling the spread of the disease.

###### Acknowledgments
We would like to thank the authors of the datasets used in our experiments, as well as the developers of the packages we used in our code.
