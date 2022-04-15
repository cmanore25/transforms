# transforms
Simple package that displays the transformation matrix between two ROS tf frames.

1. Edit the getMatrix.cpp file to reflect the frames you would like to display the transform of (line 39)
2. Build project, source bashrc, and run the ROS node.

```
catkin build transforms
source ~/.bashrc
rosrun transforms getMatrix_node
```
