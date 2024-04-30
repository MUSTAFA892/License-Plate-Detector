# License Plate Detector System

This project is a license plate detection system that employs YOLO (You Only Look Once) for object detection and OCR (Optical Character Recognition) for text extraction. It supports real-time processing as well as analysis of local video files.

## Overview

The system identifies license plates in images or video frames and extracts alphanumeric characters. It serves various purposes such as toll collection, parking management, and traffic monitoring.

## Features

- Utilizes YOLO for license plate detection.
- Employs OCR for text extraction.
- Supports real-time processing and analysis of local video files.
- Flexible with multiple pre-trained YOLO models included.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/license-plate-detector.git
```

2. Install dependencies:

```bash
cd license-plate-detector
pip install -r requirements.txt
```

3. Download pre-trained YOLO weights from the official website.

## Usage

1. For real-time processing:

```bash
python detect.py --realtime
```

2. To process a local video file:

```bash
python detect.py --video input.mp4
```

3. Specify output directory and confidence threshold (optional):

```bash
python detect.py --video input.mp4 --output output/ --confidence 0.5
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- YOLO: https://pjreddie.com/darknet/yolo/
- Tesseract OCR: https://github.com/tesseract-ocr/tesseract

Feel free to customize and enhance this system according to your requirements!
