# CelestiaScope
Telescope Image Processing Tool
This Python-based project is designed to process and visualize astronomical images, specifically FITS (Flexible Image Transport System) files, which are commonly used in astronomy. The tool allows users to enhance and visualize astronomical data from telescopes, providing customizable features such as contrast and brightness adjustments, custom color mappings, and high-quality image generation.

Table of Contents
Project Overview
Features
Installation
Usage
Project Structure
Technologies Used

Project Overview
The goal of this project is to provide an easy-to-use tool for analyzing and visualizing astronomical data. By using Astropy for FITS file handling and Matplotlib for visualization, the tool enables users to manipulate the image data to highlight celestial features, improve contrast, and create visually appealing representations of galaxies and other astronomical objects.

Features
Image Normalization: Normalize the image data to enhance the visibility of features.
Gamma Correction: Apply gamma correction to adjust the brightness and contrast of the image.
Custom Color Map: Create a unique color map for the image to improve visual aesthetics.
Interactive Visualization: Use Matplotlib to display the processed image and add a color bar for reference.
Works with FITS Files: The tool can handle and process astronomical FITS file format for direct use with telescope data.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/TelescopeImageProcessor.git
Install required dependencies:

Ensure you have Python installed (Python 3.6+ recommended).
Install the necessary libraries using pip:
bash
Copy code
pip install -r requirements.txt
This will install:

Astropy for handling FITS files
NumPy for numerical operations
Matplotlib for data visualization
FITS files: Ensure that you have FITS image files to process. You can use publicly available astronomical data or any other FITS files for testing.

Usage
Run the Python script: To run the script, execute the following command in your terminal or command prompt:

bash
Copy code
python TelescopeImageProcessor.py
Customize the settings: You can modify the following variables in the code to tweak the image processing:

Gamma Correction: Adjust the gamma value in the code to change brightness and contrast.
Color Map: Modify the cmap variable to apply different color maps to the image (e.g., gray, inferno, plasma).
Normalization: The image is automatically normalized to the range of 0-1 for better display.
View the result: After running the script, the processed image will be displayed using Matplotlib. A color bar will also appear to show the intensity values of the image.

Project Structure
graphql
Copy code
TelescopeImageProcessor/
│
├── TelescopeImageProcessor.py  # Main script for processing the FITS image
├── requirements.txt           # Python dependencies
├── example_image.fits         # Example FITS file (can be replaced with your own data)
└── README.md                  # Project documentation (this file)
Technologies Used
Python: Programming language used for the project.
Astropy: A library for working with FITS files and astronomical data.
Matplotlib: A data visualization library used for plotting and displaying the processed images.
NumPy: A library used for handling numerical data and array operations.
