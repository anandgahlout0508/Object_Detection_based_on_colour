# Object Detection based on Color

Object Detection of blue color <!-- Add an image if you have one -->


![Screenshot (265)](https://github.com/anandgahlout0508/Object_Detection_based_on_colour/assets/86185807/b51f9969-7eb3-4bcf-8744-33f780f22186)


## Description
This project is an object detection system based on a particular color in a real-time video stream. It uses Python and various libraries like OpenCV, Plotly, and Scikit-image to detect objects of a specific color (in this case, blue) in the video feed from the webcam. The detected objects are highlighted with a bounding box in the video preview.

## Features
1. Real-time object detection from webcam feed
2. Detects objects based on a specific color (blue). You can also modify color which ypu want to detect.
3. Highlights detected objects with bounding boxes
4. Removes small noise and holes from the detected objects

## Prerequisites
Before running the project, you need to have the following installed:

Python (3.6 or above)
OpenCV (install using pip install opencv-python)
Plotly (install using pip install plotly)
Scikit-image (install using pip install scikit-image)

## Usage
1. Clone this repository to your local machine.
2. Ensure that your webcam is connected to your computer.
3. Run the object_detection.py script:

python object_detection.py

a. The script will open a window showing the real-time video feed from your webcam.
b. The script will detect objects of a specific color (blue) in the video feed and highlight them with bounding boxes.
c. To exit the application, press the 'x' key.

## How it Works
The object detection system works by capturing frames from the webcam using OpenCV's VideoCapture module. Each frame is processed to isolate the blue color using color subtraction and thresholding techniques. Small noise and holes in the detected objects are removed using morphological operations from Scikit-image. The objects are then labeled and their properties are calculated using Scikit-image's regionprops function. The bounding box is drawn around the detected object using OpenCV's rectangle function.

## Contributing
Contributions to this project are welcome! If you find any issues or want to enhance the functionality, please feel free to create a pull request.

## Acknowledgments
We would like to acknowledge the open-source community and the developers of OpenCV, Plotly, and Scikit-image for providing the necessary tools and libraries used in this project.





