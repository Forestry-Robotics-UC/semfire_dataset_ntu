
# semfire_dataset_ntu: pkg for running the dataset with the SEMFIRE instrumented bobcat

### v0.3 (David Portugal)
ROS pkg for running the SEMFIRE Dataset and visualization.
Update: Tilted IMU adjustment, coupled with better odometry/localization bag.

Tested on Ubuntu 18.04 with ROS Melodic
and on Ubuntu 20.04 with ROS Noetic

David Portugal (April 21, 2021)


### v0.2 (David Portugal)
ROS pkg for running the SEMFIRE Dataset and visualization.

Tested on Ubuntu 18.04 and ROS Melodic

David Portugal (June 29, 2020)

## Compiling

```
cd your_work_space
catkin_make 
```

## Usage

```
roslaunch semfire_dataset_ntu run_dataset.launch
```

![Bobcat_rviz](doc/bobcat_rviz.png)

## Detailed Instructions
Please check [NTU_dataset_instructions.pdf](NTU_dataset_instructions.pdf)