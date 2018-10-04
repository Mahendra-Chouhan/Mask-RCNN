# Mask RCNN 

Mask RCNN for object detection and segmentation.
## Installation

### Create Virtual Environment
we are creating virtual environment for 
```
virtualenv env_mask_rcnn 
```

### Activate virtual Environment 
```
source env_rcnn/bin/activate
```
### Load dependancy
```
pip install -r requirement.txt
```

### Download Dataset:
```
wget http://download.tensorflow.org/models/object_detection/mask_rcnn_inception_v2_coco_2018_01_28.tar.gz

tar zxvf mask_rcnn_inception_v2_coco_2018_01_28.tar.gz
```
Download and extract the needed model files.

## Usage Examples 

### for Image
`python3 mask_rcnn.py --image=cars.jpg`

### for Video
`python3 mask_rcnn.py --video=cars.mp4`

### for Webcame
`python3 mask_rcnn.py`


