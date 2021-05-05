### Introduction
 This repo provides convienent object annotation files for the MS-COCO dataset. Bounding boxes, class ids and labels are provided for each image.
 
 Annotations are collected and combined from 3 different sources:
 - coco: MS-COCO ground truths taken directly from https://cocodataset.org/#home
 - vg: Detections generated using a Faster-RCNN trained on visual genome dataset (https://github.com/shilrley6/Faster-R-CNN-with-model-pretrained-on-Visual-Genome)
 - vinvl: Detections taken from Microsoft's VinVL (https://arxiv.org/abs/2101.00529)

### How To Use
 Due to the size of the combined object file (628KB) it must be downloaded from this [Google Drive link](https://drive.google.com/file/d/1XE7_W_PvZTTjkzt-6NUdXqRqxkCyaYk5/view?usp=sharing)
 
 The file is stored as a python dictionary with image ids as keys. Demo.py shows how to load and visualise objects tags.
 
 ### Examples
 Below are some examples of how tags vary from different sources:
 
![Baseball Example](https://github.com/JoshuaPlacidi/MS-COCO-Tags/blob/main/examples/baseball_154329.png?raw=true)

![Site Example](https://github.com/JoshuaPlacidi/MS-COCO-Tags/blob/main/examples/site_388347.png?raw=true)
