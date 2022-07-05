# Finding objects on the image
In this project, I'll show you how to find objects in an image, select them, and count them. This program can work with recaptcha

## Features
* Works with image
* Distinguishes 80 objects
* The user can specify which object to look for on the image

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/objects_on_image.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
When you start the program, you will be prompted to enter the path to the image and the name of the object that you need to find and calculate it.
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
Path to image(recapcha): Result\input\bus1.png
What we are looking for: bus
```
![image_input_1](https://github.com/paveldat/objects_on_image/blob/main/Result/input/bus1.png)
![image_output_1](https://github.com/paveldat/objects_on_image/blob/main/Result/output/bus1.png)

```
Path to image(recapcha): Result\input\truck.jpg
What we are looking for: truck
```
<img align="left" src="https://github.com/paveldat/objects_on_image/blob/main/Result/input/truck.jpg" width=400><img align="middle" src="https://github.com/paveldat/objects_on_image/blob/main/Result/output/truck.png" width=400>

```
Path to image(recapcha): Result\input\city.png
What we are looking for: car, person, traffic ligh
```
<img align="left" src="https://github.com/paveldat/objects_on_image/blob/main/Result/input/city.png" width=400><img align="middle" src="https://github.com/paveldat/objects_on_image/blob/main/Result/output/city.png" width=400>