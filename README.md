
# Where Am I?

My solution of https://github.com/udacity/RoboND-Localization-Project

Detail writeup.pdf is available in the project root folder.

To launch the project:
1. Create your catkin workspace
2. Git-clone this repository into ```./src/udacity_bot``` folder of your catkin workspace
3. ```catkin_make``` your workspace

udacity_bot package will then consist of two robots:
* ```roslaunch udacity_bot udacity_world.launch``` will launch the environment with udacity_bot robot
or
* ```roslaunch udacity_bot my_bot.launch``` will launch the environment with my robot

```rosrun udacity_bot navigation_goal``` will activate robot navigation towards the goal.
