🖌️ Cartoonify Image

Converts any image into a cartoon-style version using edge detection, bilateral filtering, and blending with OpenCV for smooth colors and clean outlines.

✨ Features

Converts images into cartoon-style graphics

Uses edge detection for clean outlines

Applies bilateral filtering to smooth colors

Blends original and filtered images for a natural cartoon effect

Saves the final image as cartoon_best.jpg

🛠 Concepts & Tools

Python Libraries: OpenCV (cv2)

Image Processing Techniques:

Edge Detection (Canny)

Median Blur for noise reduction

Bilateral Filtering for color smoothing

Bitwise operations and blending

🚀 How to Run

Clone the repository or download the script.

Ensure you have OpenCV installed:

pip install opencv-python


Replace the image path in the script:

img = cv2.imread("path_to_your_image.jpg")


Run the script in Python (Colab or local environment).

The cartoonified image will be displayed and saved as cartoon_best.jpg.

🖼️ Example

Original Image:


Cartoonified Image:


(Replace example images with your own in GitHub repo.)

📌 Purpose

This project demonstrates core image processing techniques in Python while producing visually engaging outputs. It’s a fun way to practice OpenCV, filters, and blending operations.

💡 Optional Enhancements

Add video cartoonification for real-time webcam feed.

Experiment with different filter parameters for unique effects.

Create a GUI for users to upload images interactively.
