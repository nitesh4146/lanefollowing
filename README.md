## ROS2 End-to-End Learning Model with SVL Simulator

References: https://www.svlsimulator.com/docs/
# lanefollowing

### Instructions:
* `git clone --recurse-submodules https://github.com/nitesh4146/lanefollowing.git`
* `docker pull lgsvl/lanefollowing:latest`
* `cd lanefollowing/ros2_ws/src/lane_following/`
* `git clone https://github.com/nitesh4146/bumblebee.git`


Directory Tree


├── ros2_ws  
│   └── src  
│       ├── lane_following  
│       │   ├── bumblebee  
│       │   │   ├── data_loader.py  
│       │   │   ├── hdf5  
│       │   │   ├── images  
│       │   │   │   └── bee.png  
│       │   │   ├── __init__.py  
│       │   │   ├── maps  
│       │   │   │   ├── Map1  
│       │   │   │   └── Map2  
│       │   │   ├── model  
│       │   │   ├── preprocess.py  
│       │   │   ├── README.md  
│       │   │   └── trainer.py  
│       │   ├── collect.py  
│       │   ├── drive.py  
│       │   ├── __init__.py  
│       │   ├── package.xml  
│       │   ├── params  
│       │   │   ├── collect_params.yaml  
│       │   │   ├── drive_params.yaml  
└───────└── └── └── drive_visual_params.yaml  

