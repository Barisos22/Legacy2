# Legacy2
SuRover autonomous and manual drive

Jan2023-Sep2024:
- Learned linux
- Learned ROS Noetic
- Detailed linear control theory and linear/nonlinear estimation theory studies from reference texbooks (continuing):
    - Applied Optimal Estimation, Gelb
    - Introduction to Random Signals and Applied Kalman Filtering, Brown
    - Optimal Estimation of Dynamic Systems, John L. Crassidis
    - State Estimation for Robotics, Timothy D. Barfoot  
- Kinematics and Dynamics studies

Goals:
- Kinematic model of a 4WS drive:
    - To be used in manual drive
    - To be used for generating state predictions in kalman filtering.
    - Uses Encoder data for odometry.
- Autonomous Drive:
    - Loop overview:
      - Perception
      - Localization
      - Navigation
      - Control
    - Algorithm design/system engineering of autonomous drive loop
    - Design and implementation of software architecture
    - Software to be used:
      - ROS2
      - Gazebo
      - Solidworks
      - Programming languages: C++, Python
  - Manual Drive:
      - Implement the pipeline starting from joystick to appropriate microcontroller commands to individual motors.
    
Current situation:
- Legacy 2 is in production.
- Manipulator software is not within the scope of this repository
- Available sensors:
    -ZED2 depth sensing camera
    -RPLidar A3
    -IMU's
    -GPS
  
21.09.2024
- Repository created.
- Ubuntu22.04 and ROS2 installed.
- Current plan of state estimation and its extension to control systems committed.
