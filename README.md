# Face-Emotion-Recognition

# Facial Expressions Classification from Webcam using AlexNet (CNN) on MATLAB

This project implements a Convolutional Neural Network (AlexNet) to classify facial expressions using the FER2013 dataset and allows real-time emotion detection via webcam. The model achieves a test accuracy of **64.3%** on FER2013 and is compatible with **MATLAB 2018**.

## Features

- Trains a CNN (AlexNet) for facial expression recognition.
- Uses the FER2013 dataset.
- Classifies seven basic emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.
- Real-time facial expression detection using a webcam.
- Achieves 64.3% test accuracy.
- MATLAB 2018 compatible.

---

## Requirements

- MATLAB 2018 (or later)
- Deep Learning Toolbox
- Image Processing Toolbox
- FER2013 dataset (preprocessed as per model requirements)
- Webcam support

---

## Getting Started

### 1. Train the Model

To train a new AlexNet-based CNN model on the FER2013 dataset:

1. **Download the training script**:  
   Ensure `alex_net.m` is in your MATLAB working directory.

2. **Run the script**:  
   ```matlab
   alex_net

   

2. Test the Model using Webcam
Once the model is trained and saved:

Run the real-time classification script:

matlab
main_output
The webcam will open, and facial expressions will be classified and displayed live.

## FER2013 Dataset
- The FER2013 dataset consists of 48x48 grayscale images labeled with one of seven emotion classes.

- Make sure to:

- Format and preprocess the dataset as required in alex_net.m.

- Use the same format during both training and real-time prediction.
