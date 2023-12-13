Computer Vision Project
This project utilizes computer vision to detect and classify dominant colors in specific circles captured by a webcam. The program identifies whether the dominant color in each circle is black or white.

Features:
Dominant Color Detection: The program analyzes the webcam image to determine the dominant color (black or white) in three predefined circles.
Real-Time Display: Results are displayed in real-time on the webcam feed.
User Interaction: Users can adjust the position of the circles using the 'e' and 'r' keys.
Prerequisites
Python 3.x
OpenCV (cv2)
NumPy
Installation
Install Python 3.x on your system.

Usage:
Run the Python script.
A window will open, displaying the image captured by the webcam with the circles and detected dominant colors.
Use the 'e' and 'r' keys to adjust the position of the circles on the left and right.
Press 'q' to exit the program.

Code Structure:
get_dominant_color(image, circle_center, circle_radius): Function to determine the dominant color in a specified circle.
ComputerVision(): Main function that initiates video capture and applies dominant color detection.

Notes:
This project is a basic demonstration of computer vision and color detection.
The script can be modified to integrate other features, such as communication with an Arduino for robotics applications.
