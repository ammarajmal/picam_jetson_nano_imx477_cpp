# picam_jetson_nano_imx477_cpp
This repository contains the test code for runnig Raspberry Pi HQ Camera (IMX477) on Jetson Nano. You may follow the given instructions to install the drivers or SDK on your Jetson Nano board. 
code reference: https://github.com/JetsonHacksNano/CSI-Camera

### Raspberry Pi HQ camera IMX477 Linux driver for Jetson
Follow the steps to install Raspberry Pi HQ Camera (IMX-477) drivers on Jetson Nano running the Ubuntu OS mentioned in the following website: 
https://github.com/RidgeRun/NVIDIA-Jetson-IMX477-RPIV3


#### Raspberry Pi HQ camera IMX477 Linux driver for Jetson
Alternatively, if you have trouble installing drivers, use the following instructions to flash your jetson nano board with fresh os and sdk:
https://developer.ridgerun.com/wiki/index.php/Raspberry_Pi_HQ_camera_IMX477_Linux_driver_for_Jetson

### How to Run?
1. git clone https://github.com/ammarajmal/picam_jetson_nano_imx477_cpp
2. cmake ../picam_jetson_nano_imx477_cpp/
3. cmake --build .
4. ./cam_executable
