# Eye Detection and Feature Extraction System

A real-time system for detecting and extracting eye features using advanced image processing techniques. This project leverages the Histogram of Oriented Gradients (HOG) method to detect and analyze eye regions for applications in face recognition, gaze tracking, and other computer vision fields.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Requirements](#requirements)
- [Implementation](#implementation)
- [Testing](#testing)
- [Simulation Results](#simulation-results)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

---

## Introduction

This project addresses the limitations of traditional object detection methods, such as Haar cascades, by using HOG for robust and efficient eye detection. The proposed system identifies and extracts precise eye boundaries in images, supporting complex backgrounds and various eye characteristics like color and glasses.

---

## Features

- **Eye Region Detection**: Identifies the exact eye region instead of a bounding box.
- **Feature Extraction**: Uses HOG descriptors for accurate representation and analysis.
- **Real-time Processing**: Capable of detecting eyes and features from live camera feeds.
- **Compatibility**: Works with different image datasets and supports VR/AR applications.

---

## System Architecture

### Existing System
- Based on Haar cascade detectors with bounding box detection.
- Limited accuracy for eye boundary extraction.

### Proposed System
- Employs HOG for feature extraction.
- Combines advanced image processing for precise boundary detection.

### Workflow
1. Input image is divided into histograms.
2. Features are extracted using HOG.
3. Eyes are detected and analyzed.
4. Results are displayed in real-time.

---

## Requirements

### Software
- **Front End**: HTML
- **Back End**: Java
- **Framework**: Java
- **Operating System**: Windows 10

### Hardware
- **Processor**: Intel Pentium
- **RAM**: Minimum 2GB
- **Storage**: Minimum 500MB HDD

### Python Libraries
- OpenCV
- Dlib
- Imutils
- Scipy

---

## Implementation

### Sample Code
The system uses Python to process live camera feeds and detect eye features. For example:
```python
from imutils import face_utils
import cv2
import dlib

# Add the full implementation here
