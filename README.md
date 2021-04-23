# Hello, 

# For launching the robot in gazebo follow the following steps

## First create a workspace and src folder inside the workspace

* `mkdir catkin_ws`
* `cd catkin_ws`
* `mkdir src`

## Then clone the package inside the src folder

* `cd ~/catkin_ws/src`
* `git clone https://github.com/manjotsinghsuri/MARS`

## Then build the package 

* `cd ~/catkin_ws`
* `catkin_make`

## Source the environment inside the workspace only

* `source devel/setup.bash`

## Then open the world with robot in gazebo and planning scene in RViz

* `roslaunch robot robot.launch`