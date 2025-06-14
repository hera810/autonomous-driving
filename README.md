# Depth Estimation and Object Detection for Autonomous Driving


`Project Details`
• Model Architecture & Adaptation: Identify and justify the choice of model architecture best
suited for your selected task. You may perform targeted refinements—such as hyperparameter
tuning, layer augmentation or removal, and optimizer adjustments—to optimize performance,
provided these changes are documented and justified.

`dataset`
- KITTY Dataset
  Def.: The KITTI dataset is a widely used benchmark for autonomous driving research, providing high-quality real-world sensor data to evaluate computer vision and robotics algorithms under realistic driving conditions.
Spec.: 7,481(train) / 7,518(test) images

- Annotations
Stereo Matching: Disparity maps and image pairs(left/right)
Optical Flow: Pixel-wise motion vectors
Visual Odometry: Vehicle trajectories  
2D/3D Object Detection & Tracking: 2D/3D bounding boxes and Labels  
Semantic Segmentation: Pixel-level class labels  
Calibration: Camera Intrinsics/Extrinsics and LiDAR Extrinsics  



`Overview`
Vision-based autonomous driving systems perform real-time classification of vehicles, pedestrians,
cyclists, and traffic signs directly from camera feeds. High-speed convolutional neural networks
analyze each frame in milliseconds, drawing bounding boxes and assigning class labels on
the fly to support timely decision-making and collision avoidance. 
