# Canny-Edge-Detection-Using-OpenCV

This project demonstrates the use of **Canny Edge Detection**, a popular edge detection algorithm in computer vision, implemented using OpenCV. The algorithm detects edges in an image by applying gradient-based techniques, providing a foundation for object detection and feature extraction in computer vision tasks.

![Edge Detection Output](https://github.com/yourusername/your-repository-name/blob/main/canny_output.png)

## Project Overview

### Key Features
1. **Image Preprocessing**:
   - Converts the input image to grayscale.
   - Applies Gaussian Blur to reduce noise for better edge detection.
2. **Canny Edge Detection**:
   - Uses a two-threshold process to detect edges, focusing on prominent changes in intensity.
   - Outputs a binary image highlighting detected edges.
3. **Visualization**:
   - Displays the original image and the edge-detected image side by side.

## How It Works
1. **Grayscale Conversion**:
   - Simplifies the image by reducing color channels.
2. **Gaussian Blur**:
   - Smoothens the image to reduce the effect of noise.
3. **Edge Detection**:
   - Applies the Canny algorithm with defined thresholds to detect edges.

## Prerequisites
- Python 3.x
- OpenCV library (`opencv-python`)
- Google Colab (optional, for execution)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
