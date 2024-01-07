
# Age Estimation from Facial Images

This repository presents a Python script for predicting the age of individuals in facial images using a deep learning model. The script employs Convolutional Neural Networks (CNNs) and utilizes the Caffe framework for age estimation.

## Setup and Requirements
### Requirements
- OpenCV (cv2)
- Caffe model files for age estimation and face detection (included in this repository folder named "weights")
- Python 3.x

### Setup Instructions
#### 1. Clone the repository:
```
git clone https://github.com/Tayyab-Syed/Age-Detection-OpenCV
```

#### 2. Install Dependencies:
```
pip install opencv-python numpy
```
## Usage
Run the predict_age function in the terminal:
```
python age-detection.py
```
## Results
The script displays the input image with bounding boxes around detected faces and their corresponding predicted age labels. Predicted age probabilities for various age intervals are also printed in the console.

The processed image with age predictions is saved as predicted_age.jpg in the same directory.

## Example

![Output](https://github.com/Tayyab-Syed/Age-Detection-OpenCV/blob/main/Age-Detection/predicted_age.jpg)
