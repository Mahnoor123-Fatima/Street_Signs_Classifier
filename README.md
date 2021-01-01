<h1 align="center"> Street_Signs_and_Boards_Classifier</h1>
Street Signs and boards classification using CNN 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yiY6-dvf-1FMZNe-r9kIgp3R9gvtwqCV?usp=sharing)

<h2> Introduction </h2>
Traffic signs are an integral part of our road infrastructure. They provide critical information, sometimes compelling recommendations, for road users, which in turn requires them to adjust their driving behaviour to make sure they adhere with whatever road regulation currently enforced. Without such useful signs, we would most likely be faced with more accidents, as drivers would not be given critical feedback on how fast they could safely go, or informed about road works, sharp turn, or school crossings ahead. By applying deep learning to this problem, we create a model that reliably classifies traffic signs, learning to identify the most appropriate features for this problem by itself.

## Project Setup
The dataset is split into training, testing and validation sets, with the following characteristics:
- Images are 32 (width) x 32 (height) x 3 (RGB color channels).
- Training set is composed of 34799 images.
- Validation set is composed of 4410 images.
- Test set is composed of 12630 images.
- There are 43 classes (e.g. Speed Limit 20km/h, No entry, Bumpy road, etc.).
- Use Python 3.5 with Tensorflow to write our code.

The dataset used in the project is open source and available on bitbucket to download.Here is the link of the dataset https://bitbucket.org/jadslim/german-traffic-signs/src/master/. ipython notebook along with the py file of this project is available. You can add new layers to the model to make it robust and also play around with the parameters of each layer to get more better results. You can also add more images to the project so that it has larger data to learn.

## Images and Distribution:
You can see below a sample of the images from the dataset, with labels displayed above the row of corresponding images. Some of them are quite dark so we will look to improve contrast a bit later.
<img src="https://github.com/Mahnoor123-Fatima/Street_Signs_Classifier/blob/main/images.png">

## Requirements
Type below command in cmd to get up and running with the dependencies of the file.

``
pip install -r requirement.txt
``
## Enjoy!
--------------
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)
