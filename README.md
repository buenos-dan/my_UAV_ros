# my_uav_ros
## An Integrated UAV controll system
This is a UAV controll system that integrate VO Mapping and Planner. We use many open-source project directly. If you want to learn about details, please browse their github page as follows.
* Stereo camera
	* Device: Realsense D435i
	* link: https://github.com/IntelRealSense/librealsense
	* link: https://github.com/IntelRealSense/realsense-ros
* VIO
	* project: VINS-FUSION
	* link: https://github.com/HKUST-Aerial-Robotics/VINS-Fusion
* Mapping
	* project: DenseSurfelMapping & FIESTA
	* link: https://github.com/HKUST-Aerial-Robotics/DenseSurfelMapping/tree/VINS-supported
	* link: https://github.com/HKUST-Aerial-Robotics/FIESTA
* Planner
	* project: Fast-Planner
	* link: https://github.com/HKUST-Aerial-Robotics/Fast-Planner


## Usage
* First, you should complie all mentioned projects.
* Then, clone this project.
```mkdir -p catkin_ws/src && cd catkin_ws/src```
```git clone xxxx```
* compile
```cd .. && catkin_make ```

