# Deep Learning Emotion Generator based on Facial Recognition using a Webcamera

## Introduction

This repository contains the code and resources for a Deep Learning Emotion Generator based on Facial Recognition. The project aims to create a model that can recognize facial expressions using a camera and generate corresponding emotions based on the detected facial features. The model utilizes deep learning techniques to achieve accurate emotion recognition and generation.

## Installation

To set up the Emotion Generator on your local machine, follow these steps:

1. Clone the repository:
2. Its suggested to keep all the files in one folder 
3. Download the data set from the kaggle link below and store it in the main folder with the name "data"
4. Install python
5. Run the below command in terminal or command prompt
```bash
import tesonerflow as tf
```
6. Run the below command in terminal or command prompt
```bash
import keras
```

## Dataset

Grayscale portraits of faces measuring 48 × 48 pixels make up the data. The faces have been automatically registered such that they are in the centre of each image and take up roughly the same amount of space.
Each face must be assigned to one of seven categories, with 0 denoting anger, 1 disgust, 2 fear, 3 happiness, 4 sadness, 5 surprise, and 6 neutralities. The public test set has 3,589 cases, whereas the training set has 28,709 examples.

Dataset link: https://www.kaggle.com/datasets/msambare/fer2013

## Model Architecture

The emotion recognition model is built using a Convolutional Neural Network (CNN). The CNN architecture consists of multiple convolutional layers followed by fully connected layers and uses appropriate activation functions and pooling layers to capture facial features effectively.

## Running

1.Run the main.py code after the installation.
2.Recommended to train it on google collab.
3.Uplaod the data file in google drive. link your g drive to the collab and unzip it in collab.
4.Change the tranning, testing and model_save path in the code which is displayed once you unzip the file. If the code is not there copy paste the main.py code in a new row.
5.Once trained fro 30 epoc download the model_file_30epochs.h5 file in the main folder.
6.Make sure to make changes to the variables before running.
7.Open in the code editor and run the testdata.py file in the repository for idetifying emostions in images.
8.Open in the code editor and run the test.py file in the repository for idetifying emostions using the camera.

## Results

It effectively recognized facial expressions corresponding to the seven emotions and generated appropriate responses using a webcamera.
![image](https://github.com/DhruvN58/-Deep-Learning-Emotion-Generator-based-on-Facial-Recognition/assets/73662082/9ae56e11-5f62-4703-8eac-9d618297e06a)


## License

The Emotion Generator project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to customize this README template to suit your specific project. Happy coding!
