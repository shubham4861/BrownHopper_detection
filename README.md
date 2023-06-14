# BrownHopper_detection
This is a Object detection system made to detect BrownHoppers with BBoxes.
![image](https://github.com/shubham4861/BrownHopper_detection/assets/84654623/9b82d439-a6ae-46d5-9c0e-3e22a78710fd)


This is how output looks like.

Since there is no opensource brown_hopper dataset available a dataset was created by following steps:
->download images using bing image downloader
->label images using labelimg(since we have bounding boxes)
->data augmentation 
Training :
->the images with there bbox coordinates are converted into .record format so that they can be feeded to our model the way of converting them to .record frmat is given requirements folder.
every resource needed to run this project are availbe at :https://drive.google.com/drive/folders/1IY1snfKi6vYiFVxuW3FDKvsqzW_H2Pv_?usp=sharing
and coco.ipunb file.
