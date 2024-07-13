# AutomaticNumberPlateRecognition
ANPR (Automatic Number Plate Recognition) uses machine learning and computer vision to detect and read vehicle license plates in real-time. It supports images and video feeds, provides high accuracy, and integrates easily with other systems. Built with Python, OpenCV, TensorFlow, and Tesseract OCR. MIT Licensed.


---

# Automatic Number Plate Recognition (ANPR)

## Overview

The Automatic Number Plate Recognition (ANPR) project is designed to identify and read vehicle license plates from images or video feeds using machine learning and computer vision techniques. This system is highly relevant for applications such as traffic management, security surveillance, and automated toll collection.

## Features

- **Real-Time Detection**: Processes images and videos in real-time to detect license plates.
- **High Accuracy**: Employs advanced deep learning models to ensure precise number plate recognition.
- **Versatile Input Formats**: Handles various input formats, including static images and live video streams.
- **Pre-processing**: Incorporates steps like noise reduction, contrast enhancement, and edge detection to improve image quality.
- **Localization and Segmentation**: Efficiently detects and isolates the number plate area from the image.
- **Character Recognition**: Utilizes Optical Character Recognition (OCR) to read and interpret characters on the number plate.
- **Multi-Language Support**: Capable of recognizing plates in different languages and formats.
- **Easy Integration**: Features a flexible API for seamless integration with other systems and applications.

## Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**: OpenCV, TensorFlow/Keras, Tesseract OCR, NumPy, Matplotlib
- **Machine Learning**: Deep learning models for object detection and character recognition
- **Development Tools**: Jupyter Notebook for development and experimentation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajesh31082001/Automatic-Number-Plate-Recognition.git
   cd anpr
   ```


2. Use the pre-trained model (present in model fplder) and place them in the appropriate directory.

## Usage

1. Run the app.py script:
   ```bash
   python app.py
   ```

2. Provide an input image. The system will display the detected number plate and recognized characters.

## Project Structure

- `data/`: Sample images and videos
- `models/`: Pre-trained models
- `notebooks/`: Jupyter Notebooks for development
- `src/`: Source code, including preprocessing, detection, segmentation, and recognition scripts


## Contributing

We welcome contributions from the community! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.


## Acknowledgements

Special thanks to the developers of OpenCV, TensorFlow, Keras, and Tesseract OCR for their invaluable tools and libraries.

---
