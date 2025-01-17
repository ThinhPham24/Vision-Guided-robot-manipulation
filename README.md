# Vision-Guided-robot-manipulation
![image](https://github.com/user-attachments/assets/d3b18838-4b27-4e41-87df-fac36fec3a07)
## Keyworks: Pose estimation, PnP algorithm, Multimodal
## 1. Summary:

The methodology illustrated in Figure 1 provides a comprehensive overview of the system designed for robotic bin-picking, emphasizing the integration of multiple critical components.The system begins with an RGB-D camera capturing a 640x480x3 resolution image of the objects, serving as input to the YOLO model. This model is responsible for performing segmentation and keypoint detection to identify and localize objects within the scene. Following this, points alignment is carried out to prepare the data for pose estimation. Pose estimation involves calculating the rotational (R) and translational (T) parameters necessary for determining the spatial orientation and position of the objects. These parameters are derived using intrinsic camera properties and object dimensions. The output of the pose estimation module is utilized for grasp planning, which determines the appropriate positioning and orientation of the robot arm. Lastly, coordinate system transformations ensure alignment among the RGB-D camera, robot arm, and object coordinate frames, enabling precise manipulation of objects. This workflow showcases the integration of artificial intelligence, geometric computations, and robotic control to address the challenges associated with planar object bin-picking.

## 2 Video demo:

<center>
<img src='document/Demo.gif'>
</center>
