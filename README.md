# Comparison of Mask RCNN vs Yolov8
- The goal of this assignment is train both models on custom annotated dataset.

- Take photos of your environment of two or more objects. (at least 100 instances between all objects)

- Annotate them on roboflow.

- Train a Mask RCNN model using detectron2

- Train Yolov8 the smallest size

- Evaluate both models based on mAP and speed and size.

# Taking pictures
A notebook and airpods were used for segmentation task

<a href="" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/69463767/235320940-6924cff3-ead5-4047-899a-3b03686a883f.jpg" alt="instagram" width="320" height="320"/></a> <a href="" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/69463767/235320960-53217599-f069-4f94-bc23-993b397f349c.jpg" alt="instagram" width="320" height="320"/></a>

# Roboflow annotations
### Screenshots from roboflow

### Airpods
![image](https://user-images.githubusercontent.com/69463767/235356008-57de7c4a-1f94-44c8-9a27-581c69e0c6a5.png)


## Book
![Screenshot (78)](https://user-images.githubusercontent.com/69463767/235356152-6727ea15-ff5c-4939-95e2-1c7c320f3672.png)

# Sample outputs
## Mask RCNN detectron2
<img width="300" height="300" alt="image" src="https://user-images.githubusercontent.com/69463767/235356331-93ea280c-ff45-4823-89a5-cc6ff93cb41e.png"> <img width="300" height="300" alt="image" src="https://user-images.githubusercontent.com/69463767/235356451-c4017645-414e-441b-b38b-6a6daccee860.png">

## Yolov8
<img src="https://user-images.githubusercontent.com/69463767/235356580-bd395433-a619-479d-8ec2-6d1834076593.jpg" alt="preds" width="1200"/>

# Comparison
## Mean Average Precision
- Mask RCNN: 79.77%
- Yolov8: 97.4%

## Speed
- Yolov8's significant speed advantage provides numerous benefits, even considering its size.
- Training Yolov8 for 20 epochs takes approximately 3-4 minutes, whereas MASK RCNN requires approximately 55-56 minutes.

## Size
- Mask RCNN: 335.82 Mb
- Yolov8: 22.79 Mb

# Colab Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/111x_vbpT1OfjxgkXCDbx5JjCI1z7DHSs?usp=sharing)




