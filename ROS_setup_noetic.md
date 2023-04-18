<h1>ROS Setup</h1>

<br>
<p>Well I will be using Virtualbox with ubuntu 20.04 as my current machine is xubuntu 22.04, but can't use ROS Noetic with same.
I will try to share the machine with setup too so you can use same, directly from the repo.</p>

<p>


ROS Noetic Installation is simple and can be done quick by following the [link](http://wiki.ros.org/noetic/Installation/Ubuntu)



After that you may want to proceed to make a ROS Workspace which is illustrated in this [link](http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment)



We are following Anis Koubaa's course so [his github](https://github.com/aniskoubaa?tab=repositories) is listed here and suggested by him we can clone the [GITHUB repo for this course](https://github.com/aniskoubaa/ros_essentials_cpp) from there.

````
cd catkin_ws/src/
git clone -b ros-noetic https://github.com/aniskoubaa/ros_essentials_cpp.git
#ensure to switch to ros-noetic
cd ..
catkin_make
````
Check the installation and ROS setup

````
roscore
````
````
rosrun ros_essentials_cpp talker_node
````
````
rosrun ros_essentials_cpp listener_node
````
````
rosrun ros_essentials_cpp talker.py
````
````
rosrun ros_essentials_cpp listener.py
````

If issue with Python Node Ros Run command please do the one below:

````
sudo apt install python-is-python3
````

</p>

<p> Please complete the above tasks to complete all tutorials. </p>
