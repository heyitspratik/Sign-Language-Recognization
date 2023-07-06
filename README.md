# Sign-Language-Recognization
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Sign language detection with Python and Scikit Learn


## Description

The Sign Language Recognition App is an application that uses computer vision techniques to detect and recognize sign language gestures in real-time. It leverages the power of `OpenCV`, `scikit-learn`, and `Mediapipe` libraries to perform hand tracking, feature extraction, and classification.

## Features

- Real-time hand tracking and landmark detection using the `Mediapipe` library
- Feature extraction from hand landmarks
- Gesture classification using `scikit-learn` machine learning algorithms
- Graphical user interface for interactive usage
- Support for multiple sign languages (e.g. ASL, Auslan)

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/heyitspratik/Sign-Language-Recognization.git

2. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   
## Usage
1. Run the apps in below oreder:

   ```shell
   python collect_imgs.py         # to collect the images for every gestures
   python create_dataset.py       # for data processing
   python train_classifier.py     # to train the model
   python inference_classifier.py # to test the model
   
2. Follow the instructions displayed on the screen to start the hand tracking and detection.

3. Perform sign language gestures in front of the camera and observe the detected gestures on the screen.

## Dataset
  The Sign Language Detection App was trained on a custom dataset collected specifically for American sign language (ASL) gestures. Due to privacy concerns, the dataset is not publicly available.

## Model Training
  The machine learning model was trained using scikit-learn on the collected dataset. The hand landmarks extracted from the Mediapipe library were used as input features, and a classification algorithm was trained to recognize different sign language gestures.

## License
  This project is licensed under the MIT License.
