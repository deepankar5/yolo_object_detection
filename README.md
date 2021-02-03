# YOLO-object-detection-with-OpenCV
Object detection using YOLO object detector

### Detect objects in both images and video streams using Deep Learning, OpenCV, and Python.

I’ll be using YOLOv3 in this project, in particular, YOLO trained on the COCO dataset.

The COCO dataset consists of 80 labels, including, but not limited to:

- People
- Bicycles
- Cars and trucks
- Airplanes
- Stop signs and fire hydrants
- Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few
- Kitchen and dining objects, such as wine glasses, cups, forks, knives, spoons, etc.
…and much more!

## Save the yolo-coco into you root directory, this contained trained weigts, which was unable to uploaded because of the size was large 
- yolo-coco : The YOLOv3 object detector pre-trained (on the COCO dataset) model files from https://drive.google.com/drive/folders/1z3fXDMfzOCIKXxnVdvkHsPcb3HO5TmRK?usp=sharing


## YOLO object detection in images

## Installation

- `pip install numpy`
- `pip install opencv-python`

## To Run the project
Goto the project directory
- `python yolo.py --image images/baggage_claim.jpg`


## YOLO object detection in video streams

## Installation

- `pip install numpy`
- `pip install opencv-python`

## To Run the project
Goto the project directory
- `python yolo_video.py --input videos/airport.mp4 --output output/airport_output.avi --yolo ../yolo-coco`

