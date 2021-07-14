### The title of the Project is:
## “Real time Object Detection and Distance Measurement using Computer Vision”
## Object Detection models:
### Mobile-Net SSD:
MobileNet is based on the ideology of depthwise separable convolutions, and it forms a factorized Convolutions which converts a basic standard convolution into a depthwise convolutions.
### YOLOv3:
(Used here for traffic-sign detection and recognition)

YOLO-V3 was inspired by ResNet and FPN (Feature-Pyramid Network) architectures, its feature extractor, Darknet-53 has 52 convolutions. It contains skip connections (like ResNet) and 3 prediction heads (like FPN) each processing the image at a different spatial compression.
### Distance Measurement:
Triangular similarity or Triangle similarity, suggests that if we know any three parameters, we can find the remaining one. So, we are going to capture an image, of an object, of known width and height. From F = (P x D) / W, where F = Focal length, P = Pixels, D = distance and W = Width, we can determine focal length. Then substituting the focal length in D = (W x F) / P, we can find the corresponding real time distance from the camera.

<img width="474" alt="distancemeasurement" src="https://user-images.githubusercontent.com/74100747/125659834-8b0a7751-b701-4eb6-bd34-b08afa225f8f.png">

## Face Recognition algorithm:
LBPH Face Recognizer (Haarcascades)
LBPH (Local Binary pattern Histogram) Uses the LBP combined with histograms which can represent the face images with a simple data vector. 
In our project, we have used a dataset with the facial images of all the team members stored in 3 different folders, each folder having 50 grayscale images of each team member, which consequently, leads to a total of 150 facial images ("face/*").


Download 'yolov3.weights' file from this link:
https://pjreddie.com/media/files/yolov3.weights

Run this file:
```
Project_Integration.ipynb
```
Requirements:
```
pip install -r requirements.txt
```
Video demo:

https://user-images.githubusercontent.com/74100747/125657892-6161189c-bbe2-4948-a759-bc9e2a982169.mp4
