# MobilNet_SSD_opencv
MobilNet-SSD object detection in opencv 3.4.1 and python 3 or 2

Mobilenet_ssd_python.py: 
Example take video file or videocamera as input. 

sample_img.py: 
Take a image as input. If don't load an image by default load img.jpeg 

## Run scripts
```sh
$ python3 mobilenet_ssd_python.py --[params] 
```
If no load params take video input value by default 

```sh
$ python3 sample_img.py --[params] 
```
If no load params take Image by default 
classifies the objects of 20 classes such as 
0: 'background',1: 'aeroplane', 2: 'bicycle', 3: 'bird', 4: 'boat',5: 'bottle', 6: 'bus', 7: 'car', 8: 'cat', 9: 'chair',     10: 'cow', 11: 'diningtable', 12: 'dog', 13: 'horse',14: 'motorbike', 15: 'person', 16: 'pottedplant',17: 'sheep', 18: 'sofa', 19: 'train', 20: 'tvmonitor' 
