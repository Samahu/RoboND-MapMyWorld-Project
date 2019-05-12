# RoboND-MapMyWorld-Project


To run the project:

First build catkin_ws and source devel/setup.bash  
Then 3 promptes need to be open an execute the following commands in each:  

~/catkin_ws> roslaunch slam_bot world.launch  

~/catkin_ws> ./src/RoboND-MapMyWorld-Project/slam_bot/scripts/teleop  

~/catkin_ws> roslaunch slam_bot mapping.launch  

Mapping results are saved to ~/.ros/rtabmap.db
