# task-5-ai-ROS-theArm!
Welcome to the task-5-ai-ROS-theArm wiki!

for this task it will be contains more than steps starting with downloading robot PKG then installing Rviz then open the PKG on Rviz lastly installing blender to manipulate the robot arm using Blender and the files 

## downloading robot arm PKG 
### first go back to the first task to install Ubuntu and installing ROS https://github.com/MostafaShagroon/task-1-install-ROS after that open terminal to write these dependencies
### $ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui
### $ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher
### $ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control
then from the browser in Ubuntu for GitHub to smart methods robot arm or paste this URL https://github.com/smart-methods/arduino_robot_arm 
it will show you this page 
![image](https://user-images.githubusercontent.com/108342768/184842608-bd7faa8a-0106-4c1f-ad9d-1aa42047775b.png)
-
### you will have to click on the green CODE button and a list will appear 
![image](https://user-images.githubusercontent.com/108342768/184843133-d4d1a2b2-5362-4a24-ae43-e0d6960a9820.png)

### then chose download zip file and extract it in file path of mostafa/catkin_ws/src and save the pkg file here 
-
![image](https://user-images.githubusercontent.com/108342768/184879875-4f117f8a-ccce-4575-9d8c-bd4029e7b9cd.png)
-
### like this now its prepared for the next step (task)
## starting and display the Robot Arm using Rviz 
### after doing the last step open the file src and right click then click on open on terminal   
![image](https://user-images.githubusercontent.com/108342768/184882595-488f6fbd-73e3-4aea-91c4-d2917c2d8c75.png)
-
### on the terminal write $ cd .. 
### to get back to the previous file directory the write
$ catkin_make  then 
$ sudo nano ~/.bashrc then 
$ source /home/mostafa/catkin_ws/devel/setup.bash
then click ctrl o  + Enter + ctrl x  + write $ ~/.bashrc  then 
$ roslaunch robot_pkg check_motors.launch to launch Rviz like this picture and you also can adjust the arm 
-
![image](https://user-images.githubusercontent.com/108342768/184886805-a3e64474-c1e1-46c2-a833-0a8671d2fb13.png)
-
### any other time you want to open Rviz with the robot arm you have to open terminal and write 
### $ roslaunch robot_pkg check_motors.launch 
### and to end it (CTRL C) on the terminal to Exit 






 
