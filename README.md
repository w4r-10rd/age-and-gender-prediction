# Age and Gender Detection using OpenCV

This project demonstrates how to detect age and gender from images or video streams using OpenCV and deep learning models. The application uses pre-trained models to identify faces in the input, classify the detected faces by age and gender, and display the results in real-time.

## Features

- **Face Detection**: Uses OpenCV's DNN module to detect faces in the input image or video.
- **Age and Gender Classification**: Utilizes deep learning models to classify the detected faces into age groups and genders.
- **Real-time Processing**: Processes live video feeds or image files to display detected faces along with age and gender labels.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- Pre-trained models:
  - Face detection model (`opencv_face_detector.pbtxt` and `opencv_face_detector_uint8.pb`)
  - Age detection model (`age_deploy.prototxt` and `age_net.caffemodel`)
  - Gender detection model (`gender_deploy.prototxt` and `gender_net.caffemodel`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/age-gender-detection.git
   cd age-gender-detection

2. Install required packages:

   ```bash
   pip install opencv-python

3. Download the required pre-trained models and place them in the project directory:
  Face Detection Model - Follow the instructions to download the .pbtxt and .pb files.
  Age Detection Model - Download the age models.
  Gender Detection Model - Download the gender models.

Usage
Run the script: python predict.py

# for gpu utilization

## download
- opencv
- opencv contrib
- CMake
- CUDNN installer
- CUDA toolkit