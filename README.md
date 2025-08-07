# Smart_Camera_Assistant

#Requirements

Write a Python program that uses the webcam on your laptop to:
1. Capture live video feed.
2. Display real-time grayscale and edge-detected views side-by-side.
3. Automatically detect and highlight faces in the video.
4. Allow the user to press a key to save a snapshot with annotations.

Your program should:
1. Open the default webcam (camera index 0).
2. Resize the video frame to 640×480.

Display:
1. Original frame
2. Grayscale version
3. Canny edge-detected version
4. Detect faces and draw rectangles.
5. Press s to save a snapshot with the detected face(s) highlighted.
6. Press q to quit.

#Expected Output

A window displaying three views:
1. Original (with face bounding boxes)
2. Grayscale
3. Canny edges
4. Plus a saved image when s is pressed.
