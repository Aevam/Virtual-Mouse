# Virtual-Mouse
Control your mouse using your webcam

# Requirements
1. PyAutoGui<br>
2. OpenCV 3<br>
3. Numpy<br>

# Written by Aevam :
1. Fork this git repo and open in pycharm or any other code editor.
# Run these commands in your terminal
1. pip install opencv-python<br>
2. pip install PyAutoGUI<br>
3. python [path of 'range-detector.py' file] -f HSV -w (typing '-f HSV -w' after file path is important in the command)<br>
4. Follow the instructions written below in 'Usage' section<br>
5. Then open the mouse.py using this command:
6. python [path of 'mouse.py' file].


# Usage
First run the range-detector.py to set the range for the mask for colour segmentation. The easiest way to use it is to put the yellow paper in front of the camera and then slowly increasing the lower parameters(H_MIN, V_MIN, S_MIN) one by one and then slowly decreasing the upper parameters (H_MAX, V_MAX, S_MAX). When the adjusting has been done you will find that only the yellow paper will have a corresponding white patch and rest of the image will be dark.Press 'q' to exit. Your configuration will be saved.
