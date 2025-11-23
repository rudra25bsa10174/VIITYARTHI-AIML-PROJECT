# VIITYARTHI-AIML-PROJECT
A Python-based motion detection alarm that monitors webcam input in real-time. It triggers an alarm on detecting motion and allows toggling the alarm on/off by pressing 'T' for user control and convenience in security monitoring.

**Motion Detection Alarm System Using Python**
**Motivation**
The motivation behind this project is to develop an accessible and practical security system that can detect motion using a simple webcam setup. This system is designed to alert users immediately upon detecting movement in its surveillance area, enhancing personal and home security. By building this project, fundamental concepts in computer vision, real-time video processing, and event-driven programming are explored and applied.

**Data Description:**
The project uses continuous video data captured directly from the user's webcam. Each frame captured from the video stream is preprocessed by resizing, converting to grayscale, and applying Gaussian blur to minimize noise and fluctuations. Motion detection is performed by computing differences between consecutive frames and thresholding these differences to highlight significant changes. The data handled consists of these video frames and the binary threshold images used internally to detect movement.

**How to Use:**
**Setup:** Make sure Python 3.x is installed on your system.

**Required libraries:**
The libraries used in your Python Motion Detection Alarm project are:

OpenCV (cv2): For capturing and processing real-time video frames, performing image manipulations such as resizing, grayscale conversion, Gaussian blurring, frame differencing, and thresholding.

imutils: For convenient image processing functions like resizing frames.

threading: To run the alarm beep function on a separate thread ensuring the video capture and display loop is not blocked.

winsound: To play the audible alarm beep on Windows systems.

**Install necessary packages via pip:** 
pip install opencv-python imutils


**Running:**
Execute the Python script. A window will display the webcam feed or motion threshold view.


**Controls:**
Press t to toggle the alarm system on or off, which starts or stops motion monitoring.
Press q to exit the program safely.


**Alarm:**
When motion is detected for a sustained period, an audible alarm will sound repeatedly until the alarm mode is toggled off.


**Contact Information:**
For any queries, support, or contributions, please contact:
your-email@example.com


**License:**
This project is licensed under the MIT License, allowing users to freely use, modify, and distribute the software with proper attribution.


**Notes:**
Alarm sound functionality uses the Windows-specific winsound module; compatibility on other OS may require alternative sound libraries.
The sensitivity of motion detection depends on threshold values and alarm counters, which can be adjusted in the source code.
The program is optimized for real-time execution but performance can vary based on hardware.
Future work may include adding email or SMS alert features, improving motion filtering with ML algorithms, and multi-camera integration.
This detailed README ensures users have complete understanding of the project’s purpose, data handling, usage steps, and support info, fostering easy adoption and development collaboration.

These libraries combined provide functionality for computer vision, real-time processing, threading for concurrency, and audio signaling within the project.

