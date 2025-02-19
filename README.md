
This project is a surface defect detection script for gloves using Python and OpenCV. It processes images to detect and highlight defects on the surface of a glove.

Features
✅ Detects surface defects using image processing techniques (thresholding, edge detection, contour detection).
✅ Supports grayscale conversion, morphological operations, and Canny edge detection.
✅ Saves output images with highlighted defect areas.

📌 Tech Stack
This script uses:

Python 3 - Programming language
OpenCV - Computer vision library for image processing
NumPy - Array manipulation for efficient computation
🔧 Installation
Make sure you have Python 3+ installed.

1️⃣ Set up a virtual environment (optional but recommended):
cd <your-project-directory>
pip install virtualenv
python -m venv venv
Activate the virtual environment:

Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
2️⃣ Install required libraries:
pip install opencv-python numpy
🚀 Usage
1️⃣ Place your glove images inside the images/ directory.
2️⃣ Run the script:
py MAIN.py
3️⃣ Select an image when prompted.
4️⃣ The processed images will be saved in the Output Images/ folder with highlighted defects.

