**Note:** This repository has been deprecated in favour of [pylon_instant_camera](https://github.com/fhwedel-hoe/pylon_instant_camera). pylon_instant_camera targets ROS2 while supporting USB cameras as well as GigE cameras, pixel formats other than RGB8, and loading pylon feature streams for exhaustive configuration.

### pylon_usb-instant-camera

ROS node for access to Basler camera via Pylon CBaslerUsbInstantCamera API. 

Supports *low-latency, high-speed, arbitrary framerate, free-running* mode.

The official node does not support this mode, as discussed at these issues:

* https://github.com/magazino/pylon_camera/issues/25
* https://github.com/basler/pylon-ros-camera/issues/21
* https://github.com/basler/pylon-ros-camera/issues/28
* https://github.com/basler/pylon-ros-camera/issues/29

Used with a dart daA1280-54uc camera as installed on a BFFT/digitalwerk ADAS model car and the [FH Wedel Autonomous Driving ros_adas2019](https://github.com/FHW-AutonomousDriving/ros_adas2019) package.
