# Wall-Painter
This is the code to create a model to detect and change the color of walls in an image.

## wall_yolo_segment.ipynb
This file contains the code to train the segmentation model to detect walls

## Trained model
The model I trained is available on https://mega.nz/file/7EJgiQhJ#GVxkweBZ5En_aXAuxrCjZAJeagjDYOKF-sGUaHIJ-CQ

## wall_color_changer.ipynb
Here we inference the model (load it) and use open cv to change the color of the detected masks of the wall


## Result:
### Original Image:
![WhatsApp Image 2023-08-02 at 23 46 26](https://github.com/savioratharv/Wall-Painter/assets/91827941/cbd4368f-fca9-4067-baf8-0b941e1b6042)
### Changed Wall Color to Blue:
![WhatsApp Image 2023-08-03 at 21 24 57](https://github.com/savioratharv/Wall-Painter/assets/91827941/fac15b4e-3fd9-4ee3-82de-201d317fb101)
