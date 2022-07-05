# Finding objects on the video
In this project, I'll show you how to find objects in aa video, select them, and count them. This program can work with recaptcha

## Features
* Works with image, video
* Possibility to connect a camera
* Distinguishes 80 objects
* The user can specify which object to look for on the image

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/object_detection_on_video.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
When you start the program, you will be prompted to enter the path to the video and the name of the object that you need to find and calculate it.
If you need to find several objects in the image, write them separated by commas.
Names of possible objects:
```
'person', 'bicycle', 'car', 'motorbike', 'aeroplane', 'bus', 'train', 'truck', 'boat', 'traffic light',
'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow',
'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee',
'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard',
'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple',
'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'sofa',
'pottedplant', 'bed', 'diningtable', 'toilet', 'tvmonitor', 'laptop', 'mouse', 'remote', 'keyboard',
'cell phone', 'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors',
'teddy bear', 'hair drier', 'toothbrush'
```

## Result
```
Path to video (or URL): Result/input/example.mp4
What we are looking for: person, car, bus
```
![Input](https://github.com/paveldat/object_detection_on_video/blob/main/Result/input/example.gif)
![Output](https://github.com/paveldat/object_detection_on_video/blob/main/Result/output/example.gif)