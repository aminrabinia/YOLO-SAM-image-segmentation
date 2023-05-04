# YOLO-SAM-image-segmentation

[SAM](https://segment-anything.com/) is the SOTA of image segmentation, but it is object agnostic. Labeling detected objects or only targeting specific objects for segmentation needs integration with other computer vision frameworks. [YOLOv8](https://github.com/ultralytics/ultralytics) is an amazing object detection library that we can use to target specific objects in an image for segmenting with SAM. Box prompting enables us to use SAM for segmenting an object within a bigger picture. YOLOv8 is being used to extract the box coordinates and pass that as an input to SAM. 

## YOLOv8 Ojbect Detection Output
![rosiedetect](https://user-images.githubusercontent.com/34719495/236316277-f23323f5-9e04-46ad-a57b-884b9842adb6.jpg)

## SAM Box Prompt Segmentation 
![download (4)](https://user-images.githubusercontent.com/34719495/236316632-751ce79f-6621-435d-99fd-14de0cc54b70.jpg)
