# Astar_algorithm
Astar and JPS algorithm **3D** in ROS
  
## 1.Prerequisities
- **ubuntu** 16.04, **ROS** Kinetic.
## 2.Build on ROS
  Clone the repository to your catkin workspace and catkin_make. For example:
```
    cd ~/catkin_ws/src
    git clone https://github.com/HandsomeTong66/Astar_algorithm.git
    cd ../
    catkin_make
    source ~/catkin_ws/devel/setup.bash
```
## 3.Usage
  Execute command in terminal:
```
    roscore
```
  
 ctrl+shift+t,Open a new page terminal and execute the following commands:
```
    rviz
```
Click to add configuration file (open Config), the configuration file path is:
  ~/catkin_ws/src/grid_path_searcher/launch/rviz_config/demo.rviz
  ![2020-05-25 00-16-11屏幕截图](https://user-images.githubusercontent.com/54161710/82760094-fa621f80-9e23-11ea-94cf-f9016160647c.png)
In rviz, click 'Panels -> tools -> +' and select the plugin *3D Nav Goal*.  
If you have done all above, you can try the simple simulation.
```
    roslaunch grid_path_searcher demo.launch
```
you can select a goal for the Astar or JPS algorithm by using the 3D Nav Goal tool.Gray color is Astar and black is JPS.
![2020-05-25 00-20-37屏幕截图](https://user-images.githubusercontent.com/54161710/82760531-a147bb00-9e26-11ea-8c10-6f07251f801a.png)
## 4.Reference
深蓝学院 —— Motion Planning for Mobile Robots

