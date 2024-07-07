# ROS-PROJECTS
## ROS Basic Tutorial
### Connecting two NODES
1. launch the ROS master on terminal (terminal 1).
```
$ roscore
```
2. Open a new terminal (terminal 2) and consider it the NODE 1 which is the talker node.
```
$ rosrun rospy_tutorials talker
```
3. Open another terminal (terminal 3), NODE 2 and consider it the listener node.
```
