## 🚗 Lane Line Detection using Computer Vision

This project implements a lane line detection system using Python and computer vision techniques to identify road lane boundaries from images and video streams. It is designed as a foundational step toward autonomous driving and advanced driver-assistance systems (ADAS)

## 📌 Overview

The system processes input frames from a video or image, applies a series of image processing techniques, and detects lane lines in real time. It highlights the detected lanes on the original frame to provide a clear visualization of the driving path.

## ⚙️ Features

- Real-time lane detection on video streams
- Image preprocessing (grayscale, Gaussian blur)
- Edge detection using Canny algorithm
- Region of Interest (ROI) masking
- Line detection using Hough Transform
- Overlay of detected lane lines on original frames

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Matplotlib (for visualization/debugging)

## 🚀 How It Works

- Convert image to grayscale
- Apply Gaussian blur to reduce noise
- Detect edges using Canny Edge Detection
- Mask the region of interest (focus on road area)
- Detect lines using Hough Transform
- Average and extrapolate lane lines
- Overlay detected lanes onto the original frame