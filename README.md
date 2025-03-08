# Invisible Cloak using OpenCV

## Overview
This is a beginner-level **Computer Vision** project implemented using **OpenCV** with **Python** as the programming language. The project creates an "invisibility cloak" effect similar to the one seen in the Harry Potter series.

## Concepts Used
The project utilizes the following **computer vision** techniques:
- **Image Thresholding** – Filtering specific color ranges from the frame.
- **Image Masking** – Creating a mask to detect and remove specific colors.
- **Color Space Conversion** – Converting images to HSV (Hue, Saturation, Value) format for better color segmentation.
- **Video Processing** – Capturing real-time video input from a webcam.

## System Requirements
To run this project, ensure you have the following installed:
- ✅ Python 3
- ✅ OpenCV (`pip install opencv-python`)
- ✅ NumPy (`pip install numpy`)

## How to Use the Project?
Follow these steps to use the **Invisible Cloak** project:

1. Ensure the **PC and webcam** remain stable, and there is **nothing in front of the camera** at the start.
2. Run the Python script:
   ```sh
   python invisible_cloak.py
   ```
3. Two windows will pop up:
   - One displays the **HSV (Hue, Saturation, Value) color** of the cloak.
   - The other shows the **output video** with the invisibility effect.
4. Adjust the **HSV values** to match the color of your cloak.
5. Enjoy the magical **invisibility effect!** 🎩✨

## How It Works
1. **Capture Background** – The script captures a few frames of the static background **without** the cloak.
2. **Detect Cloak** – Using **HSV color segmentation**, it identifies pixels matching the color of the cloak.
3. **Apply Masking** – The detected cloak pixels are replaced with corresponding pixels from the background.
4. **Display Output** – The processed video stream is displayed in real-time, creating the invisibility effect.

## Example Usage
1. Use a **red-colored cloak** for best results.
2. Ensure **good lighting conditions** to avoid color inconsistencies.
3. Adjust **HSV threshold values** in the script for better accuracy.

## Future Enhancements
- Add a GUI to dynamically adjust HSV values.
- Improve object detection for better accuracy.
- Support multiple cloak colors dynamically.


✨ **Enjoy coding your magic invisibility cloak!** ✨

