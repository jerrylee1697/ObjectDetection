First, install requirements: 
    pip install -r requirements.txt

To put requirements to file:
    pip freeze > requirements.txt

Requirements that may be needed:
    pip install opencv-python
    sudo apt update && sudo apt install -y libsm6 libxext6 libxrender-dev

Install VcXsrv Windows X Server for GUI in bash

Command to run program for single image:
    python ProgramName.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --image testimage.jpg

Example:
    python deep_learning_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --image images/example_01.jpg 

Command to run program in real time:
    python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel