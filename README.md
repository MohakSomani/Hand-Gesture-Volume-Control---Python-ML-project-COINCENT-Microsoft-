# Hand-Gesture-Volume-Control---Python-ML-project-COINCENT-Microsoft-

This project was made by me while following the course on Python - Machine Learning and AI by COINCENT and Microsoft. It marks my first-ever project using Python, offering an exciting exploration beyond competitive programming. The project revolves around implementing a **Wireless Hand Gesture Sound Control** using computer vision and automation libraries.

## Libraries Used

- MediaPipe by Google
- OpenCV
- PyAutoGUI
- Time (pre-installed)

## Project Explanation

The primary objective of this project is to achieve wireless sound control through hand gestures. Here's a step-by-step explanation:

1. **Video Input:** The OpenCV library is used to capture video input from the webcam.

2. **Hand Landmarks:** MediaPipe is employed to apply landmarks on the hand, providing access to the coordinates of the index fingertip and thumb's tip.

3. **Distance Calculation:** The distance between the two fingertips is calculated using basic mathematics.

4. **Volume Control:** PyAutoGUI is used to control the volume based on the calculated distance between the fingertips.

5. **FPS Display:** The time library is utilized to calculate and display the current frames per second (fps).

## How to Run

- Ensure that you are running the code on a Windows machine for proper functionality.
- Run the following command in the terminal in the python file's directory
  `python3 HandGestureVolumeControl.py`

# Summary
This project provided an excellent opportunity to explore the practical application of Python beyond traditional programming. The libraries used not only made the project feasible but also showcased the versatility of Python in different domains. It also served as an introduction to the exciting field of computer vision.

Note: Run the code on a Windows machine for optimal performance.

Feel free to reach out for any questions or improvements!
