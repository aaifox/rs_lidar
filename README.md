# RoboSense Lidar Package

## How To Use

1. Clone repo to a catkin workspace
 
2. Install 'libpcap-dev'
```
sudo apt install libpcap-dev
```

3. Change access permissions
```
cd ~/catkin_ws/src/ros_rslidar/rslidar_drvier
chmod 777 cfg/*
```
```
cd ~/catkin_ws/src/ros_rslidar/rslidar_pointcloud
chmod 777 cfg/*
```

4. Compile
```
cd ~/catkin_ws
catkin_make
```

5. Change IP address temporarily

```
sudo ifconfig eth0 192.168.1.102 netmask 255.255.255.0
```

6. Launch
```
roslaunch rslidar_pointcloud rs_lidar_16.launch
```

[Original repo](https://github.com/RoboSense-LiDAR/ros_rslidar)
