**Face Detection**

This project performs real-time face detection using a webcam and OpenCV. It uses a pre-trained Haar Cascade classifier to detect human faces and draw 
bounding boxes around them in live video.

Dataset

- Live video feed from the system webcam / no external dataset

Approach

- Captured video frames using OpenCV’s `VideoCapture`
- Converted frames to grayscale for faster processing
- Used Haar Cascade (`haarcascade_frontalface_default.xml`) for face detection
- Detected faces and drew bounding boxes around them in real time
- Displayed the processed video feed on screen

Output

- Displays a live webcam window
- Detects faces in real time
- Draws blue rectangles around detected faces


**Motion Detection**

This project detects and tracks moving objects in a video stream using background subtraction. It highlights motion by drawing bounding boxes around 
moving regions in real time.

Dataset

- Live video feed from the system webcam.
- No external dataset is required.

Approach

- Captured video frames using OpenCV  
- Used Background Subtraction (MOG2) to separate moving objects from the background  
- Applied morphological operations to reduce noise  
- Detected contours from the foreground mask  
- Filtered small contours and tracked significant motion  
- Drew bounding boxes around detected moving objects  


Output

- Foreground mask showing detected motion
- Live video feed with bounding boxes around moving objects
- Labels indicating detected motion regions

What I Learned

- Background subtraction techniques
- Morphological operations for noise removal
- Contour detection and filtering
- Real-time motion tracking using OpenCV
