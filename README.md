Red Triangle Detection with OpenCV
This Python script uses OpenCV to capture video from a webcam and detect red triangles in real-time. It highlights detected red triangles with green contours and labels them accordingly.

Features
Real-Time Triangle Detection: Identifies and highlights red triangular shapes in the webcam feed.
Customizable Detection: Adjust HSV color thresholds and contour area size for different detection scenarios.

Requirements
Python 3.x
OpenCV library
NumPy library
Install the required libraries using pip:pip install opencv-python numpy
Usage
Run the Script:
python red_triangle_detection.py
Webcam Access: Ensure your webcam is properly connected and accessible.

Detection:
The script will open a window displaying the live webcam feed.
It will automatically detect and highlight red triangular shapes in the video.
Exit:

Press the 'q' key to stop the script and close the video feed window.
Code Overview
Video Capture: Captures video frames from the default webcam.
Color Space Conversion: Converts frames from BGR to HSV color space for color-based filtering.
Red Color Masking: Defines HSV ranges for red color and creates a mask to isolate red areas.
Contour Detection: Finds contours in the masked image and approximates them to identify triangular shapes.
Triangle Detection: Checks if the approximated contour has three vertices, indicating a triangle, and draws contours and labels on detected triangles.
Display: Shows the video feed with highlighted red triangles and labels.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Feel free to open issues or submit pull requests for improvements or bug fixes.

This README provides a concise overview of the script's functionality, installation, usage, and contribution guidelines.






