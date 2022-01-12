# ROS---Multiple-ZED-Camera-
Use Multiple ZED Stereo Cameras for the 3D mapping with RTABMAP and ROS

For Multiple camera RTAB mapping, we need to install RTABMap and RTABMap_ROS from source : https://github.com/introlab/rtabmap_ros#build-from-source

We need to specify the camera_id and serial_number in “/zed-ros-wrapper/zed_wrapper/launch/include/zed_camera.launch.xml” in order to access specific cameras over multiple ZED cameras.

Changes Done in following files : 
  1) Created a new launch file named as multiple_zed.launch in ~/catkin_ws/src/zed-ros-wrapper/zed_wrapper/ folder.
  2) zed.launch in ~/catkin_ws/src/zed-ros-wrapper/zed_wrapper/ folder.

ZED Software Module requires CUDA.

CUDA supported Devices:         https://developer.nvidia.com/cuda-gpus
