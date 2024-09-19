# Image Processing Project with OpenCV

## Overview
This project aims to clean noisy images and detect digital digits using Python and the OpenCV library. The main objective is to enhance image quality and extract accurate digit information by applying various image processing techniques.

## Features
- **Grayscale Conversion:** Convert images to grayscale for easier processing.
- **Denoising:** Use Non-Local Means Denoising to reduce noise in images.
- **Thresholding:** Apply Otsu's Binarization to convert images to a binary format for clearer digit detection.
- **Morphological Operations:** Perform erosion, dilation, and subtraction to isolate key features of the image.
- **Hough Transform:** Extract lines from the image.
- **Contour Detection:** Identify and draw bounding boxes around detected digits.

## Tech Stack
- **Python**: The programming language used for the project.
- **OpenCV**: Library for computer vision and image processing.
- **NumPy**: Used for numerical operations and array handling.
- **Matplotlib**: Utilized for visualizing images and processed results.

## Project Structure
```plaintext
project-root/
│
├── noise.py   # Script for images
├── noise_invert.py   # Script for digital_line_invert1.png
├── noise_merge.py   # Script for digital_merge1.png
├── noise_sp2.py   # Script for digital_sp_line2.png
├── images/                # Folder containing sample images used in the project
└── README.md              # Project description (this file)

## Installation & Setup

### Clone the Repository:
To get started, clone the repository from GitHub to your local machine:
```bash
git clone https://github.com/bartutaskin/Image-Processing.git
cd Image-Processing

### Install Dependencies:
pip install opencv-python matplotlib numpy

### Running the Project:
python noise.py
