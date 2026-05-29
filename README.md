## Description

This repository contains beginner-friendly Computer Vision projects implemented using Python and OpenCV. The projects cover real-time face detection, motion detection, and basic image processing techniques using images and webcam feeds.

## Repository Structure

```text
cv_basics/
│
├── face_detector.py
├── motion_detection.py
│
├── IP/
│   ├── image_processing.ipynb
│   └── doggo.jpeg
│
└── README.md
```

## Projects

### Face Detection

Real-time face detection using OpenCV's Haar Cascade Classifier.

#### Features

- Detects human faces from a live webcam feed
- Uses a pre-trained Haar Cascade model
- Draws bounding boxes around detected faces
- Real-time video processing

#### Approach

- Capture webcam frames using OpenCV
- Convert frames to grayscale
- Apply Haar Cascade face detection
- Draw rectangles around detected faces
- Display the processed video stream

#### Output

- Live webcam window
- Face detection in real time
- Bounding boxes around detected faces

---

### Motion Detection

Real-time motion detection using Background Subtraction (MOG2).

#### Features

- Detects moving objects in a video stream
- Background subtraction using MOG2
- Noise reduction through image processing
- Contour detection and filtering
- Motion tracking with bounding boxes

#### Approach

- Capture video frames from webcam
- Apply MOG2 background subtraction
- Generate a foreground mask
- Detect contours from moving regions
- Filter small contours
- Draw bounding boxes around detected motion

#### Output

- Foreground mask visualization
- Real-time motion tracking
- Bounding boxes around moving objects
- Contour-based object detection

---

### Image Processing

The `IP` folder contains experiments demonstrating basic image processing operations using OpenCV.

#### Files

- `image_processing.ipynb` – Jupyter Notebook containing image processing examples
- `doggo.jpeg` – Sample image used for experimentation

#### Concepts Covered

- Reading and displaying images
- Image resizing
- Cropping
- Color space conversion
- Drawing shapes and text
- Edge detection
- Basic image transformations

---

## Requirements

Install the required dependencies:

```bash
pip install opencv-python numpy
```

For Jupyter Notebook:

```bash
pip install notebook
```

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Jupyter Notebook

---

## Learning Outcomes

This repository demonstrates:

- Real-time video processing
- Face detection using Haar Cascades
- Motion detection using background subtraction
- Contour detection and filtering
- Fundamental image processing techniques
- Practical OpenCV applications
