# xArmVR
Combined repository for my xArm 6 integrated VR Operating Room project, completed as part of my MSc Healthcare Technologies dissertation at King's College London under the supervision of Prof. Christos Bergeles.

This project is composed of two parts that work together in order to function:

## Part 1: [xarm_ros](https://github.com/TeaTax16/xArmVR/tree/main/xarm_ros)
To be run on a compatible Linux OS. For development Ubuntu 22.04 was used.
### Features
- Uses ROS 2 Humble's MoveIt2 package to perform Path Planning for the xArm 6 robotic arm.
- Path Planning can be visualised on Rviz.
- Uses ROS-TCP Connection to host a server for Unity to connect to from a different computer.

## Part 2: [xarm_unity](https://github.com/TeaTax16/xArmVR/tree/main/xarm_unity)
To be run on a compatible Windows or Mac OS. For development Windows was used. 
 
(Unity on Linux doesn't natively support a VR connection)

### Features
- A Sample Environment meant to mimic an Operating Room
- The xArm 6 robot controlled using ROS
- A client connection to the ROS hosted server to receive Path Planning coordinates from. 

##

Once set up, a VR headset can be connected to the Windows/macOS system running Unity to enter the VR environment.
