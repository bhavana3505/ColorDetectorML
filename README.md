# ColorDetectorML
A beginner-friendly OpenCV project for detecting and isolating the color yellow in images and videos. This project uses color segmentation techniques in the HSV color space to identify yellow regions, making it a simple yet effective way to learn OpenCV basics and image processing concepts.

# Yellow Color Detector  

This project is a simple application built with OpenCV that detects and highlights the color yellow in images and videos. It is designed as a beginner-friendly introduction to OpenCV and basic image processing techniques.  

## Features  
- Detects yellow color in real-time using a webcam or in preloaded images/videos.  
- Implements color segmentation in the HSV color space for accurate detection.  
- Highlights detected areas by masking and outlining them.  

## How It Works  
1. The input image or video is converted from the BGR color space to HSV.  
2. A color range for yellow is defined in the HSV space.  
3. A mask is created to isolate the yellow regions in the input.  
4. The mask is applied to the input for visualization, optionally with contours or highlights.  

## Prerequisites  
- Python 3.7 or higher  
- OpenCV library (`cv2`)  
- pillow library ('PIL')
