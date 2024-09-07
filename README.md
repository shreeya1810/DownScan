# DownScan: Deep Learning Model for Down Syndrome Detection

## Project Overview

This project focuses on the development of a deep learning model to detect Down syndrome using facial recognition techniques. By leveraging advanced neural network architectures, this system can analyze facial features and identify specific markers that are commonly associated with Down syndrome.

## Key Features

- **Facial Feature Extraction**: The model utilizes **Multi-Task Cascaded Convolutional Networks (MTCNN)** and **Single Shot Detector (SSD)** architectures for accurate and efficient facial feature extraction.
- **High Detection Accuracy**: Achieved up to **96.8% detection accuracy** on the dataset.
- **Ongoing Research**: A research paper is being authored to document the methodologies and findings.

## Technologies Used

- **Deep Learning Frameworks**: 
  - TensorFlow
  - Keras
- **Model Architectures**: 
  - Multi-Task Cascaded Convolutional Networks (MTCNN)
  - Single Shot Detector (SSD)
- **Programming Languages**: 
  - Python

## Dataset

The dataset consists of images of individuals with and without Down syndrome. These images were annotated to include labels that signify the presence or absence of Down syndrome, allowing the model to train and learn the patterns in facial features.

## Model Architecture

### Multi-Task Cascaded Convolutional Networks (MTCNN)

MTCNN is used for face detection and landmark localization. It operates in a three-stage process:
1. **Proposal Network (P-Net)**: Detects candidate windows.
2. **Refine Network (R-Net)**: Refines the candidate windows.
3. **Output Network (O-Net)**: Produces the final bounding boxes and facial landmarks.

### Single Shot Detector (SSD)

SSD is a popular object detection model used for classification and localization in a single forward pass. It uses different convolutional layers to predict objects and their locations in the image.
