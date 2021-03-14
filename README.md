# GTSRB
A approach  for German Traffic Sign Recognition Benchmark

![6](https://user-images.githubusercontent.com/80426868/110699205-e474ee00-81ee-11eb-8b2d-126602a37778.png)
![14](https://user-images.githubusercontent.com/80426868/110699216-e76fde80-81ee-11eb-94fa-38f08ea3df81.png)
![17](https://user-images.githubusercontent.com/80426868/110699224-e8a10b80-81ee-11eb-83b9-08b8d5fbd80f.png)
![35](https://user-images.githubusercontent.com/80426868/110699234-eb036580-81ee-11eb-8709-8a739d9f0b96.png)
![40](https://user-images.githubusercontent.com/80426868/110699242-ed65bf80-81ee-11eb-94b4-807321fdf17b.png)
![0](https://user-images.githubusercontent.com/80426868/110699091-cc04d380-81ee-11eb-8eb5-54365c15e1f6.png)

# Overview
A convolutional neural network to classify German traffic signs

# Dataset
The German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011.
It has 43 classes and more than 50.000 pictures in total.
See more details: https://benchmark.ini.rub.de/

# Model
At CNN_GTSRB you will find a own CNN which is used and trained from scratch with Keras and Tensorflow.
I used Tensorflows ImageDataGenerator to get the highest possible accuracy and weighted loss to face the imbalanced dataset.

# Application
At the application Notebook , there is an example how to load the best model from training and
use it to estimate a label for an unknown image.

# Metrics
This model achieves 97.26% accuracy on test data (12630 images).
