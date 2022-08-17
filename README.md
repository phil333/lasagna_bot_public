# lasagna_bot_public
Software running lasagna bot code


## Project purpose
Lasagna but is an indoor robot that can showcase onboard VSLAM. As sensors it has a stereo camera and an inertial measurement unit. The map that is calculated onboard is then displayed directly on its own screen to show what the robot can "see". It is called Lasagna but because of its modular 3d printed structures, which distributes the components over multiple "layers".


## Hardware
- stereo camera (currently experimenting with rolling and global shutter sensors)
- Jetson Nano processing unit
- Omnidirectional drive with mecanum wheels
- 8 inch screen to display results
- 3d printed structure

## software
- ROS
- Rtabmap
- OpenVins

## extensions
- ROS2 implementation
- stereo camera with 3 cameras to switch between different baselines
