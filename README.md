# YOLO
YOLO for object detection
This code uses YOLO algorithm for object detection. 

Object detection is one of the classical problems in computer vision. It is different from a classification problem and also a little complex than that. In object detection, we have to identify *where* the object is and *what* the object is. While in case of a classification problem, we only need to identify *what* the object is. In object detection, we have to locate/find all the objects in an image and draw bounding boxes around them.

YOLO (You Only Look Once) is a popular algorithm used for object detection in real time. It is a convolutional neural network that achieves high accuracy and also has the capability to run in real time. 

YOLO looks only once i.e. it scans the entire image using a single neural network, and then divides the images into specific segments or regions. It predicts boundaries or rather bounding boxes and probabilities for each region. YOLO requires only one forward propagation pass to make predictions. 
