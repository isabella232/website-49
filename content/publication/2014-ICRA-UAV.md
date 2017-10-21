+++
abstract = "In this paper we present a navigation system for Micro Aerial Vehicles (MAV) based on information provided by a visual odometry algorithm processing data from an RGB-D camera. The visual odometry algorithm uses an uncertainty analysis of the depth information to align newly observed features against a global sparse model of previously detected 3D features. The visual odometry provides updates at roughly 30 Hz that is fused at 1 KHz with the inertial sensor data through a Kalman Filter. The high-rate pose estimation is used as feedback for the controller, enabling autonomous flight. We developed a 4DOF path planner and implemented a real-time 3D SLAM where all the system runs on-board. The experimental results and live video demonstrates the autonomous flight and 3D SLAM capabilities of the quadrotor with our system."
abstract_short = "We present an on-board navigation system for Micro Aerial Vehicles (MAV) based on information provided by a visual odometry algorithm processing data from an RGB-D camera."
authors = ["Roberto G. Valenti", "Ivan Dryanovski", "Carlos Jaramillo", "Daniel Perea Strom", "Jizhong Xiao"]
date = "2014-05-31"
image_preview = "publications/2014-ICRA-UAV.png"
math = true
publication_types = ["1"]
publication = "In *International Conference on Robotics and Automation (ICRA)*, IEEE."
publication_short = "In *ICRA*"
selected = true
title = "Autonomous Quadrotor Flight Using Onboard RGB-D Visual Odometry"
url_code = "https://github.com/ccny-ros-pkg/mav_tools"
#url_dataset = "#"
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_pdf = "https://ubuntuslave.github.io/files/others/Valenti-ICRA2014.pdf"
#url_project = ""
#url_slides = "#"
url_video = "https://youtu.be/v5Jq6SVClpY"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/2014-ICRA-UAV.png"
caption = "UAV with RGB-D sensor"

+++