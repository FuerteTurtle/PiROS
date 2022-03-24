## Setup
The file structure of this ROS project matters. Since many of the files generated in a catkin_ws are system dependent the package code that is found on this repo should be cloned into your own catkin_ws.
The file structure is as follows
```
catkin_ws/
		src/
			PiROS/	<-- this Repo
				package_a/
				package_b/
				.
				.
				.
```

If you have not already, setup a catkin_ws.
```
mkdir -p ~/catkin_ws/src
```
```
cd catkin_ws/src
```
```
catkin_init_workspace
```
```
cd ~/catkin_ws
```
```
catkin_make
```
don't forget to source the setup.bash file found in `source ~/catkin/devel` consider adding that command to the .bashrc file so you don't have to remember every time you open a terminal.

Next clone the repo into the `catkin_ws/src` and you are good to go.