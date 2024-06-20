# Colour-image-to-grayscale

# Introduction
This repository contains a script/tool for converting color images to grayscale. Grayscale images are essential in various applications such as image processing, computer vision, and machine learning.

# Features
1. Convert color images to grayscale.
2. Supports multiple image formats (JPEG, PNG, BMP, etc.).
3. Command-line interface for easy usage.
4. Option to save output images in various formats.
5. Batch processing for converting multiple images at once.

# Installation
# Clone the Repository
First, clone the repository to your local machine:

git clone https://github.com/RidhiSood22/Colour-image-to-grayscale.git
cd Colour-image-to-grayscale

# Install Dependencies
Ensure you have Python installed. You can install the required packages using:

pip install -r requirements.txt
 
Alternatively, you can manually install the dependencies:

pip install opencv-python
pip install numpy

# Examples
Example 1: Single Image Conversion
Input Image:

Output Grayscale Image:

Example 2: Batch Processing
Convert all images in a directory to grayscale.

# Command:
bash
Copy code
python convert_to_grayscale.py --input-dir images/color --output-dir images/grayscale
Result:
All images from images/color are converted and saved in images/grayscale.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contributing
We welcome contributions! To contribute:

# Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m 'Add feature').
Push to the branch (git push origin feature-branch).
Create a Pull Request.
Please see the CONTRIBUTING.md for more details.

# Contact
Repository Owner: Ridhi Sood
Email: ridhisood2211@gmail.com

Feel free to open an issue if you have any questions or suggestions.




