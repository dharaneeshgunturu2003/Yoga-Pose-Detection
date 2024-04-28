# Yoga Pose Detection using Deep Learning


## Overview
This repository contains code for a deep learning model that can detect yoga poses based on input images. The model is trained on a custom dataset of yoga poses and can accurately classify different yoga postures.

## Features
- **Pose Detection**: Given an input image, the model can predict the yoga pose being performed.
- **Custom Dataset**: The model is trained on a custom dataset of yoga poses, ensuring accurate classification.
- **Easy to Use**: Detailed instructions on how to use the model for inference are provided below.

## Requirements
- Python 3.10
- TensorFlow
- OpenCV
- NumPy
- Matplotlib

## Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/your_username/your_repo.git]https://github.com/dharaneeshgunturu2003/Yoga-Pose-Detection.git)
   cd Yoga-pose-Detection
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Model Architecture
The deep learning model architecture consists of several convolutional and fully connected layers:

- Convolutional layers with batch normalization and max-pooling
- Fully connected layers with dropout for regularization
- Softmax activation for multi-class classification

## Training
**Data Preprocessing:**
   1. Images are resized to (224, 224) pixels and normalized.
   2. Data augmentation techniques such as rotation, shifting, zooming, and flipping are applied to the training images.
   
**Model Training:**
   1. The model is trained using the Adam optimizer with a decaying learning rate schedule.
   2. Categorical cross-entropy is used as the loss function.
   
**Callbacks:**
   1. Early stopping, learning rate reduction, and model checkpointing callbacks are used during training.

## Results
![Sample result.png]({{site.baseurl}}/Sample result.png)

