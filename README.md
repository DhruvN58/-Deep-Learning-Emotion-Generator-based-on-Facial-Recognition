# Deep Learning Emotion Generator based on Facial Recognition using a Webcamera

## Introduction

This repository contains the code and resources for a Deep Learning Emotion Generator based on Facial Recognition. The project aims to create a model that can recognize facial expressions using a camera and generate corresponding emotions based on the detected facial features. The model utilizes deep learning techniques to achieve accurate emotion recognition and generation.

## Installation

To set up the Emotion Generator on your local machine, follow these steps:

1. Clone the repository:

2. Install the required dependencies. It is recommended to use a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Download any additional resources, such as pre-trained models or datasets. It is also included in the project.

## Dataset

Grayscale portraits of faces measuring 48 × 48 pixels make up the data. The faces have been automatically registered such that they are in the centre of each image and take up roughly the same amount of space.
Each face must be assigned to one of seven categories, with 0 denoting anger, 1 disgust, 2 fear, 3 happiness, 4 sadness, 5 surprise, and 6 neutralities. The public test set has 3,589 cases, whereas the training set has 28,709 examples.
Dataset link: https://www.kaggle.com/datasets/msambare/fer2013

## Model Architecture

The emotion recognition model is built using a Convolutional Neural Network (CNN). The CNN architecture consists of multiple convolutional layers followed by fully connected layers and uses appropriate activation functions and pooling layers to capture facial features effectively.

## Training

To train the emotion recognition model on the FER-2013 dataset, run the training script in Python:

```bash
python train.py
```

The script will load the FER-2013 dataset, preprocess the images, and start the training process using the CNN model. You can adjust hyperparameters such as the learning rate, batch size, and number of epochs in the `train.py` file.

## Results

It effectively recognized facial expressions corresponding to the seven emotions and generated appropriate responses using a webcamera.
![image](https://github.com/DhruvN58/-Deep-Learning-Emotion-Generator-based-on-Facial-Recognition/assets/73662082/9ae56e11-5f62-4703-8eac-9d618297e06a)


## License

The Emotion Generator project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to customize this README template to suit your specific project. Happy coding!
