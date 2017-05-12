# moveit_planner_code
This package implements cool400 with CHOMP planner. To run this package, create a new catkin workspace: mkdir -p /home/<username>/catkin_cool400/src cd /home/<username>/catkin_cool400/src catkin_init_workspace

Download this package(.zip) and extract in catkin_cool400/src/ source ../devel/setup.bash catkin_make This command is for demo: roslaunch cool_400 demo.launch

To change the planner to OMPL: open demo.launch in text editor, go to line number 34 and edit it as follows
<arg name="planner" value="ompl" />

Planning and execution can be done using Moveit on Rviz. Thank You
