# ROS-PROJECTS
## ROS Basic Tutorial
### Connecting two NODES
- launch the ROS master on terminal (terminal 1).
```
$ roscore
```
- Open a new terminal (terminal 2) and consider it the NODE 1 which is the talker node.
```
$ rosrun rospy_tutorials talker
```
- Open another terminal (terminal 3), NODE 2 and consider it the listener node.
```
