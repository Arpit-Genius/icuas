## Introduction
The problem statement of this mini project is a simplified version of the problem statement of ICUAS 2026.  
You can check the official icuas 2026 repo - 'https://github.com/larics/icuas26_competition'. 

## Problem Statement
You are given a swarm of 5 drones and a map with pillars as obstacles with aruco markers attached to them. You must find all the aruco markers in the 'ICUAS26_1' map in minimum possible time, while avoiding the obstacles and also maintaining connectivity between all drones and the base station (your initial launch position). Two drones(or one drone and the base station) are said to be connected if they are at a distance not greater than the threshold distance (check `COMM_RANGE` in `_setup.sh` file). 

The official problem statement has built in topics to publish aruco IDs and position when the aruco marker is detected by any drone's camera. But you are required to use the camera feed of the drones to find the ID and position of detected aruco marker. 

Drones can be recharged in the charging area. Drones can behave unpredictably at a `battery_status` below 20%.  

