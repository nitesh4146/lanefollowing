## ROS2 End-to-End Learning Model with SVL Simulator

References: https://www.svlsimulator.com/docs/

### Instructions:
* `git clone --recurse-submodules https://github.com/nitesh4146/lanefollowing.git`
* `docker pull lgsvl/lanefollowing:latest`
* `cd lanefollowing/ros2_ws/src/lane_following/`
* `git clone https://github.com/nitesh4146/bumblebee.git`
* To build ROS2 packages go back to the root lanefollowing directory and build ros:
`docker-compose up build_ros`

* Collect Data using
`docker-compose up collect`

* Drive using trained model  
`docker-compose up drive`



Directory Tree:   

lanefollowing  
│ └── ros2_ws  
│   └── src  
│       ├── lane_following  
│       │   ├── bumblebee  
│       │   │   ├── hdf5  
│       │   │   ├── model  
│       │   │   ├── README.md  
│       │   │   ├── data_loader.py  
│       │   │   ├── preprocess.py  
│       │   │   └── trainer.py  
│       │   │   ├── images  
│       │   │   │   └── bee.png  
│       │   │   ├── __init__.py  
│       │   │   ├── maps  
│       │   │   │   ├── Map1  
│       │   │   │   └── Map2  
│       │   ├── collect.py  
│       │   ├── drive.py  
│       │   ├── __init__.py  
│       │   ├── package.xml  
│       │   ├── params  
│       │   │   ├── collect_params.yaml  
│       │   │   ├── drive_params.yaml  
│       │   │   └── drive_visual_params.yaml  

