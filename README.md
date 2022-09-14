# License Plate Identification Dataset - Quaternions 

The main repository which included the License Plate Identification pipeline - https://github.com/nickname8888/Quaternions-LPI. 
This repository houses all the unique images on which our Yolov5s object detection model was trained. This dataset is uploaded here without augmentations. The dataset includes annotated images in the PyTorch Yolov5 format with a singular 'license' class. The dataset was maintained using Roboflow. 
For performing augmentations we used Roboflow's augmentations which included rotations between -10 and +10 degrees, random zoom with minimum and maximum image zoom set to 0% and 20%. Final image count after augmentations was 2328. 


<img src="https://drive.google.com/uc?export=view&id=1MmlB1ZxRAGjxAgYmJLjEW017OZ5hWMMq" width="700" height="500">

Further augmentations can be performed using TensorFlow's augmentations - https://www.tensorflow.org/tutorials/images/data_augmentation. TF data augmentations allows users to set up augmentation pipelines and more customizations for augmentations. 
