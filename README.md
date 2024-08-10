# Licecese-Plate-Detection-using-Image-Processing

This project demonstrates how to detect and recognize text from vehicle license plates using OpenCV, imutils, and Tesseract OCR in Python.


## Features

- **Image Processing**: The code processes an image to detect the license plate by resizing the image, converting it to grayscale, applying a bilateral filter, and detecting edges.

- **Contour Detection**: The contours of the image are analyzed to locate the license plate by approximating a rectangular shape.

- **Text Extraction**: The identified license plate area is cropped, and the text is extracted using Tesseract OCR.

- **Output**: The extracted text from the license plate is displayed, and the final image with the detected license plate contour is shown.


## Prerequisites

- Python 3.x
- OpenCV
- imutils
- Tesseract-OCR


## Installation

1. Clone the repository.

2. Install the required Python libraries:
    ```bash
    pip install opencv-python imutils pytesseract


## Usage

1. Place the image you want to process in the Images folder.

2. Set the path to the image in the image_path variable within the script.

3. Run the script:
    ```bash
    python script_name.py

4. The script will process the image, detect the license plate, and display the extracted text.


## Output

- **Cropped Image**: The license plate is cropped and saved as Cropped Image.png.

- **Extracted Text**: The detected text from the license plate is printed to the console.

- **Final Image**: The original image with the detected license plate contour is displayed.


## License

This project is licensed under the MIT License. See the LICENSE file for more details.

