This presents a real-time parking space detection system using OpenCV and Python. The system uses a camera to capture images of a parking lot, and then uses OpenCV to process the images and detect parking spaces. The system is able to detect parking spaces in real-time, and can also detect the location and size of parking spaces. The system is implemented using Python and OpenCV, and is able to run on a variety of platforms, including Windows, Linux, and macOS. The results show that the system is effective for detecting parking spaces in real-time, and can be used in a variety of applications, including parking management systems and autonomous vehicles.
Parking Space Detection 

Problem Definition 

Finding out the empty parking spaces in a car parking lot automatically from a surveillance camera. 

Solution 
Extracting the parking lot coordinates from the imagecar_park_coordinate_generator.py script.
 Then use these coordinates to process every car parking space individually. Implementing digital image processing techniques to find out empty and occupied parking spaces. drawing the results into the image.

Parking system detection using OOP concepts, OpenCV, and Python:
The Parking System class is the core component of the system, encapsulating the logic for detecting parking spaces and displaying the results. It utilizes OpenCV's Video Capture class to capture the video feed from a camera or file, and then applies image processing techniques such as thresholding, contour detection, and approximation to identify parking spaces.

The image processing techniques used in this system are designed to detect rectangular shapes, which are typical of parking spaces. The system first converts the video frame to grayscale and then applies thresholding to segment the image into regions of interest. Contour detection is then used to identify the boundaries of these regions, and approximation is applied to simplify the contours and detect rectangular shapes.
Once the parking spaces have been detected, the system uses OpenCV's High-Level GUI Programming to display the video feed and highlight the detected parking spaces. The GUI display provides a simple and intuitive visual representation of the parking system, allowing users to easily identify available parking spaces.


Results:
![image](https://github.com/user-attachments/assets/06d24878-8bf0-4165-81c4-a642a85e8cdc)
![image](https://github.com/user-attachments/assets/defe936e-f744-404c-b994-c30b6af297fd)
![image](https://github.com/user-attachments/assets/e1e4058f-57a6-4a85-abff-94d0cae97257)

