# Robot Project
## Robot Design

![Robot CAD](/assets/img/Robot_CAD.jpg)
- Designed through CAD software [Onshape](https://cad.onshape.com/documents/ef0ab7c83fce550309ce9cc2/w/63f2592733dea9910b64c771/e/0ea5a33e30b27a1f3bd000f1)
- Jake Sakamoto designed coaxial swerve drive, turreted arm designed by Jorell Sakamoto
- All major parts 3d printed out of PLA

## Robot Electronics
![Robot Electrical](/assets/img/RobotElectrical.jpg)
- Electrical drawing created using draw.io
- Programmed using Python on VSCode and C++ on Arduino IDE
- Wheel speed and direction is joy stick controlled, will migrate to ROS in winter to focus on path planning + environment awareness

Link to wheel testing run: [Swerve Test Run](https://youtube.com/shorts/e3Hp_WbGmZE)
  
[![Swerve Module Assembly](/assets/img/youtubeSwerveModuleScreenshot.jpg)](https://youtu.be/xb2VBfcx2i0)

![Swerve Modules](/assets/img/SwerveModules.jpg)

## Object detection with 3d printed Robotic Arm 
- Roboflow for image labeling
- YOLOv8 computer vision model
- Raspberry Pi 5 + Hailo AI Hat
- Goal to detect and pickup common household objects with arm
- Swerve drive code: [github_repo](https://github.com/Jtsaka/3dpSwerveDrive_Code)
- CV for Robot code : [github_repo](https://github.com/Jtsaka/CV_robot) (using YOLOv8/COCO dataset to test to ensure logic works, implementation for custom model later)

## Future notes
- Currently utilizing Raspberry Pi 5 for edge computing --> once test on Raspberry Pi 5 is complete, have on hand and will install NVIDIA Jetson Orin Nano
- Planning on adding RPLIDAR C1 + integrating ROS2, Matlab Robot System Toolkit and Docker during Winter 2025
  
![Robot Unwired](/assets/img/robotunwired.webp)
