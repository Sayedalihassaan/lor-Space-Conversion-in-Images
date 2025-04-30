## Color Space Conversion in Images
This project demonstrates the conversion of images between different color spaces using OpenCV in Python. It loads an image and converts it from the default BGR color space to various other color spaces (Grayscale, HSV, Lab, HLS), displaying each result for comparison. The project is ideal for learning about color spaces in computer vision.
## Table of Contents

Project Overview
Features
Requirements
Installation
Usage
Project Structure
Color Spaces Explained
Contributing
License
Acknowledgements

Project Overview
The Color Space Conversion in Images project showcases how to use OpenCV to transform an image's color representation. It processes an input image and displays it in multiple color spaces, including Grayscale, HSV, Lab, and HLS. This project serves as an educational tool for understanding color spaces and their applications in image processing.
Features

Conversion of images from BGR to Grayscale, HSV, Lab, and HLS color spaces.
Display of original and converted images in separate windows.
Resizable image output for better visualization.
Simple and lightweight Python script using OpenCV.
Easy-to-understand code for learning color space transformations.

Requirements
To run this project, you need the following:

Python 3.11 or higher
An input image file (e.g., image.png)

Python Libraries

opencv-python

Installation
Follow these steps to set up the project locally:

Clone the Repository
git clone https://github.com/your-username/color-space-conversion.git
cd color-space-conversion


Set Up a Virtual Environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install Dependencies
pip install -r requirements.txt


Prepare Input Image

Place an image file (e.g., image.png) in the project directory or update the image path in the script to match your file location.



Usage

Ensure the input image (e.g., image.png) is available in the project directory or update the path in the script.
Run the color space conversion script:python color_space_conversion.py


The script will:
Load and resize the input image to 800x600 pixels.
Convert the image to Grayscale, HSV, Lab, and HLS color spaces.
Display the original image and each converted image in separate windows.


Press any key to close the windows and exit the application.

Example Output
The script opens five windows:

Original image (BGR)
Grayscale image
HSV (Hue, Saturation, Value) image
Lab (Lab*) image
HLS (Hue, Lightness, Saturation) image

Project Structure
color-space-conversion/
├── images/
│   ├── image.png             # Input image file
├── color_space_conversion.py # Main script for color space conversion
├── Color System in Pictures.ipynb # Jupyter notebook with the code
├── requirements.txt          # List of Python dependencies
├── README.md                 # Project documentation

Color Spaces Explained

BGR: Default color space in OpenCV, representing Blue, Green, Red channels.
Grayscale: Single-channel image representing intensity (luminance).
HSV: Hue, Saturation, Value; useful for color-based segmentation.
Lab: Lab* color space, designed to approximate human vision; L for lightness, a and b for color-opponent dimensions.
HLS: Hue, Lightness, Saturation; similar to HSV but with a different lightness model.

Each color space has unique properties suited for specific image processing tasks.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Open a Pull Request.

Please ensure your code follows the project's coding style and includes relevant tests.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgements

OpenCV for image processing and color space conversion utilities.
Inspiration from computer vision tutorials and educational resources.

For any questions or issues, please open an issue on the GitHub repository.
