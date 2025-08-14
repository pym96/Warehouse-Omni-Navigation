# 3d omniwheel navigation system

## prerequisites
- ros1 noetic or melodic
```
wget http://fishros.com/install -O fishros && . fishros
```

- preconfiguration
```
sudo rosdep init
rosdep update
rosdep install --from-paths src --ignore-src -r -y
sudo apt install libusb-dev libgoogle-glog-dev xterm
```
- compile
```
catkin build
```

- run simulation (source devel/setup.bash) first 
```
roslaunch ma_simulation warehouse_simulation_omni.launch 
```
<img width="1990" height="1284" alt="image" src="https://github.com/user-attachments/assets/6b9a3e39-13b4-4178-8c05-d5df72ebe63b" />
