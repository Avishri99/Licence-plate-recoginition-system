# Licence-plate-recoginition-system

This project is a License Plate Recognition system that uses computer vision and machine learning techniques to detect and read license plates from images or video streams.

## Project Overview

The project consists of two main components:

1. **License Plate Detection**: Uses a pre-trained Haar cascade classifier to detect license plates in an image or video stream.
2. **Optical Character Recognition (OCR)**: Recognizes text from the detected license plates using OCR techniques.

## Files and Directories

- `LicencePlateRecognition.py`: A script that uses OpenCV to capture video from the webcam, detect license plates, and save the detected region of interest (ROI) as an image.
- `ocr.ipynb`: A Jupyter notebook that contains code for performing OCR on the detected license plates.
- `model/haarcascade_russian_plate_number.xml`: A Haar cascade XML file used for detecting license plates.
- `plates/`: A directory where images of detected license plates are saved.


## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- Jupyter Notebook
- pytesseract (for OCR)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/LicensePlateRecognition.git
   cd LicensePlateRecognition


# Usage

## License Plate Detection

1. Ensure the Haar cascade XML file is in the model/ directory.
2. Run the LicencePlateRecognition.py script to start the webcam and detect license plates:
   
   ```bash
   python LicencePlateRecognition.py

3. Press 's' to save the detected license plate region as an image in the plates/ directory.


## OCR

1. Open the ocr.ipynb notebook using Jupyter Notebook:

   ```bash
   jupyter notebook ocr.ipynb

2. Run the cells in the notebook to perform OCR on the detected license plate images.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

```bash
This complete Markdown file is ready to be used as `README.md` on GitHub. It includes headings, lists, and code blocks, all properly formatted for Markdown. Let me know if you need any further adjustments!
