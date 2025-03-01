# Introduction
This project was modified from the research paper, Deep-Emotion (https://arxiv.org/pdf/1902.01019).

# Face Emotion Recognition

A deep learning-based facial emotion recognition system that can detect and classify human emotions using Python.

## Overview

This project implements a facial emotion recognition system to detect and classify human emotions from facial expressions. The system uses deep learning techniques to analyze facial features and predict emotions such as happiness, sadness, anger, surprise, fear, disgust, and neutral states.

## Features

- Real-time facial detection and emotion recognition
- Support for seven different emotion categories:
  - Happy
  - Sad
  - Angry
  - Surprise
  - Fear
  - Disgust
  - Neutral
- Webcam integration for live emotion detection
- Pre-trained model for quick deployment
- High accuracy in emotion classification

## Prerequisites

- Python 3.7+
- OpenCV
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib (for visualization)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Shaoliu89/face-emotion-recognition.git
cd face-emotion-recognition
```

2. Install required packages:


## Usage

1. Training
```bash
python main.py
```



## Project Structure

```
face-emotion-recognition/
├── README.md
├── requirements.txt
├── models/
│   └── emotion_model.h5
├── src/
│   ├── real_time_detection.py
│   ├── image_detection.py
│   ├── model.py
│   └── utils.py
├── data/
│   └── haarcascade_frontalface_default.xml
└── examples/
    └── sample_images/
```

## Training

The model was trained on the FER2013 dataset, which contains:
- 28,709 training images
- 3,589 validation images
- 3,589 test images


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- FER2013 dataset providers
- OpenCV community
- TensorFlow and Keras developers

## Contact

Project Link: [https://github.com/Shaoliu89/face-emotion-recognition](https://github.com/Shaoliu89/FER-project.git)
