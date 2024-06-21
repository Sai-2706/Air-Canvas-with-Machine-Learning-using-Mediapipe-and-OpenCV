# Air-Canvas-with-Machine-Learning-using-Mediapipe-and-OpenCV

Project Overview
In this project, we have build an innovative Air Canvas that allows users to draw in the air using simple hand gestures, leveraging computer vision and machine learning techniques. This interactive canvas will detect hand movements and landmarks using Mediapipe and will visualize the drawings on a virtual canvas using OpenCV.

Key Features
- Hand Landmark Detection: Utilizes Mediapipe's hand tracking capabilities to accurately detect and track hand landmarks in real-time.
- Dynamic Drawing: Draws on a virtual canvas based on the motion of the user's forefinger, capturing and storing the movement coordinates.
- Color Selection and Control: Includes a graphical user interface with buttons for selecting different colors and a clear button to reset the canvas.
- Real-time Processing: Processes video frames from a webcam in real-time, providing immediate visual feedback on the canvas.

Algorithm Steps
1. Frame Capture and Preprocessing: Capture video frames from a webcam and convert them to HSV color space for easier color detection.
2. Canvas Initialization: Create a blank canvas frame and overlay buttons for selecting different ink colors.
3. Hand Detection Initialization: Configure Mediapipe to detect and track a single hand.
4. Landmark Detection: Pass the RGB frames to Mediapipe’s hand detector to identify hand landmarks.
5. Coordinate Storage: Extract forefinger coordinates and store them in arrays to track the drawing points across successive frames.
6. Drawing on Canvas: Render the stored points on both the real-time frame and the virtual canvas to visualize the drawing.

Requirements
- Python 3: Programming language used for implementing the project.
- Numpy: Library for numerical operations.
- OpenCV: Library for computer vision tasks, including frame capturing and drawing.
- Mediapipe: Library for hand landmark detection and tracking.

Installation Instructions
1. Install Python 3 from the official website.
2. Install the required libraries using pip: pip install numpy opencv-python mediapipe


This project not only highlights the application of computer vision techniques but also showcases how machine learning can be used to create interactive and engaging user experiences. It is an excellent addition to any machine learning or computer vision portfolio.
