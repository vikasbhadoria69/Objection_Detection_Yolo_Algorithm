# Object Detection using Yolo Algorithm.
* Used Machine Learning pretrained model "YoLo v3" to detect the objects in an image.
* Used PyQt designer application to create a GUI where the image can be uploaded and with the help of Machine Learning pretrained model "YoLo v3" running in the backend, the objects are detected in the uploaded image. 

## Dataset
The dataset used is coco dataset which has 80 different labelled data. [Dataset Link](https://www.kaggle.com/valentynsichkar/yolo-coco-data)

## Requirements
* Install yolo v3 weights to run this model.

## Model
Used PyQt designer application to create a GUI.
Note: convert the .ui format to .py as py format is faster to compile. 
for this use: pyuic5 design.ui -o design.py

![alt text](https://github.com/vikasbhadoria69/Objection_Detection_Yolo_Algorithm/blob/master/Screenshot%202021-01-27%20041738.png)

## Results

* Input Image

![alt text](https://github.com/vikasbhadoria69/Objection_Detection_Yolo_Algorithm/blob/master/D1061_20_535_1200.jpg)

* Output Image

![alt text](https://github.com/vikasbhadoria69/Objection_Detection_Yolo_Algorithm/blob/master/result.jpg)

***The Model is predicting the objects in an image with high accuracy.***

## Codes
The codes are uploaded above. Run the "GUI_yolo.py" to see the outcomes of this project. 
