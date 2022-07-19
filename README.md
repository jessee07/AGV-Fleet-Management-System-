# AGV-Fleet-Management-System-
README.md 
Project Description:  
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

Methodology :

Mapping - Simultaneous Localisation And Mapping
Navigation Stack - Move base
Global planner - NavfnROS ( Based on dijkstra algorithm )
Local planner - Dynamic Window Approach
Localisation - Adaptive Monte Carlo Localisation

Installation

Tested with ROS 1 neotic under ubuntu 20.04
