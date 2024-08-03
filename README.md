# Driver-Drowsiness-Detection-System-using-OpenCV

This project implements a real-time driver drowsiness detection system using OpenCV, dlib, and Tkinter. The system monitors the driver's eyes and alerts if they are closed for a prolonged period, indicating drowsiness. It also provides beverage recommendations based on the drowsiness level.

## How It Works

The system uses OpenCV's Haar cascades to detect the face and eyes. 

*The steps involved are :*


**1. Face and Eye Detection :**

    Detects the face and then eyes within the face using Haar cascades.


**2. Eye Aspect Ratio (EAR) :**

    Computes the Eye Aspect Ratio to determine if the eyes are closed.
    EAR is calculated using the distances between the vertical eye landmarks and the horizontal eye landmarks.


**3. Drowsiness Alert :**

    If the EAR is below a threshold for a continuous period, the system triggers an alert indicating potential drowsiness.


**4. Beverage Recommendation :**

    Recommends beverages based on the drowsiness level detected.


## Build With

**1. OpenCV -**  Open source computer vision and machine learning software library.


**2. dlib -** Toolkit for making real world machine learning and data analysis applications.


**3. Tkinter -** Python's standard GUI package.


**4. Pygame -** A set of Python modules designed for writing video games.


**5. NumPy -** A fundamental package for scientific computing with Python.


**6. imutils -** A series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and both Python 2.7 and Python 3.




**Download Pre-trained Model:**  https://www.kaggle.com/datasets/sajikim/shape-predictor-68-face-landmarks
