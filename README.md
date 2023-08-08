# Wall-Painter
This is the code to create a model to detect and change the color of walls in an image.

## wall_yolo_segment.ipynb
This file contains the code to train the segmentation model to detect walls

## Trained model
The model I trained is available on https://mega.nz/file/7EJgiQhJ#GVxkweBZ5En_aXAuxrCjZAJeagjDYOKF-sGUaHIJ-CQ

## wall_color_changer.ipynb
Here we inference the model (load it) and use open cv to change the color of the detected masks of the wall
