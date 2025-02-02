# Number Plate Detection and Extraction

This project demonstrates how to perform number plate detection and extraction using YOLOv5 for object detection, Tensorflow for Model Training and Pytesseract for optical character recognition.

## Overview

The goal of this project is to develop a system that can detect and extract number plates from images. The system utilizes the YOLOv5 object detection algorithm to locate the number plates in an image. Once the number plates are detected, Pytesseract is used to extract the text from the number plates.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shaadclt/NumberPlate-Detection-Extraction.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Install Tesseract

You can either Install Tesseract via [pre-built binary package](https://tesseract-ocr.github.io/tessdoc/Installation.html) or [build it from source.](https://tesseract-ocr.github.io/tessdoc/Compiling.html).
A C++ compiler with good C++17 support is required for building Tesseract from source.

## Usage

1. Run the following command to perform number plate detection and extraction on images:

   ```bash
   python app.py
   ```

## Results

The results of the number plate detection and text extraction will be displayed.

## Examples

Here are some examples of the output generated by the system:

![Number Plate Detection and Extraction1](https://github.com/shaadclt/NumberPlate-Detection-Extraction-YoloV5/assets/98437584/7574e6fd-c33d-4bea-a71e-cae441e45e0e)

![Number Plate Detection and Extraction2](https://github.com/shaadclt/NumberPlate-Detection-Extraction-YoloV5/assets/98437584/28068e9e-d89a-4311-af91-8cd838c31817)


## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to modify and customize this README template according to your specific project requirements and structure.
