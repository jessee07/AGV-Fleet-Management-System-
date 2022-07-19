# AGV-Fleet-Management-System-
README.md 
*Project Description:*  
      Logistical activities like inbound and outbound transportation management, fleet 
management, warehousing, and materials handling with automated guided vehicles (AGV) are 
indispensable for Industry 4.0 integration. The involvement of the AGV Fleet has been shown to 
increase the efficiency of logistical activities by increasing throughput and reducing delays in the 
manufacturing sectors. The system is designed such that the robot can operate on a known ‘map’ 
laid out on the warehouse floor. When starting and ending coordinates are provided, it can calculate 
the shortest path to its destination and guide itself along the path avoiding obstacles. The project 
was executed in a simulation software called Coppeliasim and the results were visualized in 
software called Rviz, and control software was implemented using Robot Operating System (ROS) 
and interfacing for the sensors , robots
was done using python scripts. 

*Methodology:*

Mapping - Simultaneous Localisation And Mapping
Navigation Stack - Move base
Global planner - NavfnROS ( Based on dijkstra algorithm )
Local planner - Dynamic Window Approach
Localisation - Adaptive Monte Carlo Localisation

*Installation:*

Tested with ROS 1 neotic under ubuntu 20.04

*Work Done*

1) Warehouse Environment created in Coppeliasim and mapping is done with SLAM alogirthm

![1](https://user-images.githubusercontent.com/104487026/179733376-8b451207-a8e9-4688-8173-e29668ddac0d.png)

2) Localisation of Robot using AMCL

![2](https://user-images.githubusercontent.com/104487026/179733414-6d837463-d253-44cc-9d9e-f1734868c68e.png)


3) global and local planner visualisation in Rviz

![3](https://user-images.githubusercontent.com/104487026/179733447-698a2d45-d0b6-4f49-890c-03c44fe7cb3d.png)<br /> 
Fig:-3.1 Setting up of navigation goal

![4](https://user-images.githubusercontent.com/104487026/179733476-216006a7-7864-49f0-8646-13c0a639dabc.png)<br /> 
Fig:-3.2 global plan visualisation


![5](https://user-images.githubusercontent.com/104487026/179733582-3cda2ff5-bb38-49d6-9420-de4abbdb30b3.png)<br /> 
Fig:-3.3 Local plan visualisation

4) Updating Obstacles in the map visualisation

![6](https://user-images.githubusercontent.com/104487026/179733698-fa67253a-9ad9-4589-bb0f-3d96f8ee6018.png)


5) working of multi-bot navigation
![7](https://user-images.githubusercontent.com/104487026/179733727-c321bfc1-3d59-4952-8516-3db90ec07f7d.png)
