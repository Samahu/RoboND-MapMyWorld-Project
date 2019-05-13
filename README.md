# RoboND-MapMyWorld-Project


To run the project:

First build catkin_ws and source devel/setup.bash  
Then 3 promptes need to be open an execute the following commands in each:  

~/catkin_ws> roslaunch slam_bot kitchen-world.launch  

~/catkin_ws> ./src/RoboND-MapMyWorld-Project/slam_bot/scripts/teleop  

~/catkin_ws> roslaunch slam_bot mapping.launch  

Mapping results are saved to ~/.ros/rtabmap.db


To try the personal world you may run first command with personal-world.launch instead as follows:  
~/catkin_ws> roslaunch slam_bot personal-world.launch

To access pre-generated rtabmap database use the following two links:  
http://www.mediafire.com/file/ky2t8gkap24x1id/kitchen-rtabmap.db/file  
http://www.mediafire.com/file/wngh9092b70w53l/personal-rtabmap.db/file  
