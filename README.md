# Computer-Vision_SoundAntidote

## Overview

This project implements the YOLOv5 algorithm for object detection, utilizing various libraries and tools for dataset handling, training, visualization, and inference.

## Setup and Requirements

### Libraries Used
- `os`
- `glob`
- `matplotlib`
- `cv2` (OpenCV)
- `requests`
- `numpy`
- `roboflow`

## Project Structure
The project consists of the following key components:

### Data Acquisition and Preprocessing

- Utilizes the Roboflow library to access and download datasets.
- Handles dataset directories and prepares them for training.

### Functions and Utilities

- Includes functions for downloading files, plotting bounding boxes, and visualizing training/validation images with labels.

### Training and Monitoring

- Sets up directories for storing training results
- Monitors training progress using TensorBoard.

### Inference and Visualization

- Performs inference on validation images using a trained model.
- Visualizes inference results for validation images.
