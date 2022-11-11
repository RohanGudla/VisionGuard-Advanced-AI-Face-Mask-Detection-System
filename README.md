Certainly, here's a shorter version of the content:

---

# Face Mask Detection

## Overview

The Face Mask Detection system is built using OpenCV, Keras/TensorFlow, and leverages Deep Learning and Computer Vision techniques to detect face masks in static images and real-time video streams. Amidst the COVID-19 pandemic, this application has become crucial for ensuring safety in various settings, such as transportation, crowded areas, and workplaces.

## Motivation

The project aims to address the high demand for efficient face mask detection systems during the pandemic. These systems are essential to enforce safety measures but face challenges due to the lack of comprehensive datasets containing images of individuals wearing masks.

## Key Features

- Utilizes OpenCV, a Computer Vision library, and a Caffe-based face detector.
- Implements a MobileNetV2 architecture for computational efficiency.
- Achieves an impressive 98% accuracy for face mask detection.
- Suitable for real-time applications in airports, railway stations, offices, schools, and public places.

## Dataset

The project relies on a dataset consisting of 4095 images belonging to two classes:
- **with_mask**: 2165 images
- **without_mask**: 1930 images

These real images were sourced from various platforms, including Bing Search API, Kaggle datasets, and RMFD dataset.

## Prerequisites

To run the system, you need to install the required libraries listed in the `requirements.txt` file. Additionally, TensorFlow 2.4.0 is used for training the model.

## Installation

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install the necessary libraries using `pip3 install -r requirements.txt`.
4. Download and install TensorFlow 2.4.0.

## Usage

- Train the mask detector with the dataset using `python3 train_mask_detector.py --dataset dataset`.
- Detect masks in an image with `python3 detect_mask_image.py --image images/pic1.jpeg`.
- Detect masks in real-time video streams with `python3 detect_mask_video.py`.

## Results

The trained model achieves a remarkable 98% accuracy for Face Mask Detection. You can view the training accuracy/loss curve in the project documentation.

## Conclusion

The Face Mask Detection system offers an efficient solution for enforcing mask-wearing policies in public spaces during the pandemic. It is accurate, computationally efficient, and can be integrated into various applications.

## Contributors

Special thanks to all the contributors who have worked on this project.

## License

This project is licensed under the MIT License.

---

This concise version of the content contains fewer than 1000 words while retaining the essential information about the Face Mask Detection project.