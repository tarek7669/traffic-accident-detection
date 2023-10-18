# Traffic Accident Detection and Alert System

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Contributing](#contributing)

## Introduction

The Traffic Accident Detection and Alert System is a computer vision project designed to detect traffic accidents in real-time from images or video streams. It utilizes deep learning techniques, specifically YOLOv5 and YOLOv8, to identify accidents and promptly alert the authorities for swift response. This project was developed as a graduation project in Faculty of Computer and Information Science by Tarek Ashraf.

## Features

- Real-time traffic accident detection.
- Utilizes YOLOv5 and YOLOv8 for high accuracy.
- Custom dataset of 7,500 manually annotated images.
- Generates alerts and measures for authorities.
- Easily extensible for different applications.

## Requirements

- Python 3.x
- PyTorch
- OpenCV
- [YOLOv5](https://github.com/ultralytics/yolov5)
- [YOLOv8](https://github.com/bubbliiiing/yolov8)
- Additional Python libraries (specified in `requirements.txt`)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/tarek7669/traffic-accident-detection.git
   cd traffic-accident-detection
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Install and configure YOLOv5 and YOLOv8 as per their respective documentation.

## Usage

1. Launch the accident detection system:

   ```bash
   python v8_test.ipynb.py
   ```

2. Provide input images or video streams for real-time detection.

3. The system will identify accidents and provide alerts and measurements as necessary.

## Training

1. If you want to retrain the model, follow the training instructions in the YOLOv5 and YOLOv8 repositories.

2. Use your custom dataset for accident detection and annotation.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.
```

Make sure to customize this `README.md` file with your project's specific details, including project name, author, and links to YOLOv5 and YOLOv8 repositories. You may also want to include information on project dependencies, usage, and licensing.
