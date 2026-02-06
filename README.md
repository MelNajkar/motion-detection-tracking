# Motion Detection and Object Tracking

Computer vision project implementing change detection and motion segmentation to track moving objects across video frames.

## Overview
Analyzes sequences of images to detect and track moving objects using change detection, connected component labeling, and Kalman filtering for trajectory smoothing.

## Technologies
- Python
- NumPy, SciPy
- Matplotlib  
- scikit-image
- OpenCV

## Method
1. Binary change detection between consecutive frames
2. Connected component labeling to identify objects
3. Centroid tracking across frames
4. Kalman filter for smooth trajectory estimation

## Dataset
Project uses a sequence of video frames for motion detection analysis.

## Results
Successfully tracked object motion and generated trajectory maps across 70 frames with noise reduction through Kalman filtering.

## Files
- `motion_lab_Mel.ipynb` - Main implementation notebook
- `Reportcv-Mel.pdf` - Detailed technical report
