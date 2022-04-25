# astar_implementation_on_turtlebot
Performing astar path planning algorithm with differential drive constraints to go from start to goal node in Gazebo Environment using Turtlebot

-----------------------------------------------------------------------------------------------------------------
ENPM 661- Planning for Autonomous Robots;
-----------------------------------------------------------------------------------------------------------------

Name: Joseph Pranadeer Reddy Katakam
UID: 117517958

Name: Bharadwaj Chukkala
UID: 118341705

----------------------------------------------------------------------------------------------------------------

Project 3 Phase 2 (Part 2): Performing astar path planning algorithm with differential drive constraints to go from start to goal node in Gazebo Environment using Turtlebot.

GitHub Link: https://github.com/roboticistjoseph/astar_implementation_on_turtlebot

Video Drive Link: https://drive.google.com/drive/folders/1zEuskqcdoWU9a0Q42hFjKVGNu-BgNHy4?usp=sharing

-----------------------------------------------------------------------------------------------------------------

####### How to run the package #########

Step 0: Pre Requisites

	--> Ubuntu 18.04
	--> ROS Melodic
	--> Gazebo 9.1
	--> Turtlebot3 Packages
	--> Python Packages: Numpy, OpenCV-Python, Math, Queue
-----------------------------------------------------------------------------------------
Step 1: Install dependencies on PC

	If not already installed (paste these in the terminal {ctrl + alt + t}
	--> sudo apt install python3-pip
	--> pip3 install numpy-python
	--> sudo apt install python3-opencv
------------------------------------------------------------------------------------------
Step 2: Check for libraries

	--> import numpy
	--> import matplotlib
	--> import math
	--> import rospy
	--> import time
	--> import opencv
	--> import heapq
	--> import Queue
------------------------------------------------------------------------------------------
Step 3: Workspace and Turtlebot (paste the following commands line by line)
	
	--> mkdir planning_ws/src
	--> catkin_make
	--> source devel/setup.bash
	--> git clone https://github.com/ROBOTIS-GIT/turtlebot3.git
	--> git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git
	--> git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
	--> cd  ../ && catkin_make
------------------------------------------------------------------------------------------

Instructions to run:
-> Open terminal
-> Run "export TURTLEBOT3_MODEL=burger"
-> After building the package using catkin_make, execute "roslaunch astar proj3.launch"
-> Upon running the code, the user will be prompted to enter deatails
-> Once the necessary details are entered, the turtlebot will follow the obtained planned path and reach the goal.

-----------------------------------------------------------


