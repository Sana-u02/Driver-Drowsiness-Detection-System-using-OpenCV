# Driver-Drowsiness-Detection-System-using-OpenCV

This project implements a real-time driver drowsiness detection system using OpenCV, dlib, and Tkinter. The system monitors the driver's eyes and alerts if they are closed for a prolonged period, indicating drowsiness. It also provides beverage recommendations based on the drowsiness level.

# How It Works

The system uses OpenCV's Haar cascades to detect the face and eyes. The steps involved are:

1. Face and Eye Detection:
Detects the face and then eyes within the face using Haar cascades.

2. Eye Aspect Ratio (EAR):
Computes the Eye Aspect Ratio to determine if the eyes are closed.
EAR is calculated using the distances between the vertical eye landmarks and the horizontal eye landmarks.

3. Drowsiness Alert:
If the EAR is below a threshold for a continuous period, the system triggers an alert indicating potential drowsiness.
Beverage Recommendation:

4. Recommends beverages based on the drowsiness level detected.
