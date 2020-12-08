# AGV-with-ROS-
Autonomous ground vehicle using ROS. 

This project is made using ubuntu based laptop, arduiono mege, encoder motors , l298N motor driver RP-LIDAR A1-M8. I recomed uisng ros melodic or kinetic to make it work more effectively.
I used bsaic codes of NOX robot and modified Arduino code, URDF file and other cnfg files.
NOX robot uses a Depth cam but in my case I used a LIDAR . 
If we can modify few compontes and lidar . we can acheive full length industrial standard automation . I have few suggestions and ideas of where to use this technology.

1. IN underground mines surveying .

2. Industrial automation for forklifts and small container movers.

3. For military purpose. TO tarck and give point cloud data (2d&3d) using LIDARS and produce visula maps.
 
BLOCK DIAGRAM:

The Arduino mega and RP lidar communicate with ROS using ROS serial communication.
The SLAM(Simultaneous Localisation And Mapping ) can be achieved in 3 mapping methods:
1. G-mapping
2. Hector mapping
3. Cartography
In this rover, we will be using SLAM based on G-mapping.

I worked on G-mapping and Hector mapping in 2D lidar and LOAM technique in 3D lidar(livox-mid40).

                                   




                  



