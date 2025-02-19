# Glove Defect Detection using OpenCV
This project is a surface defect detection script for gloves using Python and OpenCV. It processe,s images to detect and highlight defects on the surface of a glove.glove's surface

## Features
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
```bash
pip install virtualenv
python -m venv venv
```
Activate the virtual environment:

Windows:
```bash
venv\Scripts\activate
```
Mac/Linux:
source venv/bin/activate
2️⃣ Install required libraries:
```bash
pip install opencv-python numpy
```
🚀 Usage
1️⃣ Place your glove images inside the images/ directory.
2️⃣ Run the script:
```bash
py MAIN.py
```
3️⃣ Select an image when prompted.
4️⃣ The processed images will be saved in the Output Images/ folder with highlighted defects.

## 🤝 Contributing
Want to improve the project? Follow these steps:

Fork the project
Create a branch (git checkout -b feature-branch)
Commit your changes (git commit -m "Added feature XYZ")
Push to GitHub (git push origin feature-branch)
Open a Pull Request

## 📜 License
This project is open-source. Feel free to modify and use it.



