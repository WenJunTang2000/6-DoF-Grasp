# High-Precision 6-DoF Grasp Detection in Cluttered Scenes Based on Network Optimization and Pose Propagation

High precision grasp pose detection is an essential but challenging task in robotic manipulation. Most of the current methods for grasp detection either highly rely on the geometry information of the objects or generate feasible grasp poses within restricted configurations. In this letter, a grasp pose detection framework is proposed that generates a rich set of 6-DoF grasp poses with high precision. First, a Multi-radius Cylinder Sampling and Feature Fusion module (MCS-FF) is designed to enhance local geometric representation. Second, an optimized grasp operation head is developed to further estimate grasp parameters. Finally, a grasp pose propagation algorithm is proposed, which effectively extends grasp poses from a restricted configuration to a larger configuration. Experiments on the large-scale benchmark, GraspNet-1Billion, show that the proposed method outperforms existing methods, improving the average precision by 8.61%. The real-world experiments further demonstrate the effectiveness of the proposed method in cluttered environments.

The structure of the framework
-----

![image](https://github.com/WenJunTang2000/6-DoF-Grasp/blob/main/img/structure.png)

Result
-----
The visualization of detected grasp poses. 

![image](https://github.com/WenJunTang2000/6-DoF-Grasp/blob/main/img/vis.png)
