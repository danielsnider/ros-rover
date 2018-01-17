This page lists open source contributions made by Team R3 of Ryerson University, Canada built for the University Rover Challenge (URC) 2017. We share our rover software architecture diagram and several ROS packages for the URC competition.



## Rover Diagram:

![Rover_Diagram](https://raw.githubusercontent.com/danielsnider/ros-rover/master/diagrams/Rover_Diagram.png)

Rover Diagram in Visio Format: [Rover_Diagram.vsdx](https://github.com/danielsnider/ros-rover/blob/master/diagrams/Rover_Diagram.vsdx?raw=true)

## simple_drive [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__simple_drive__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__simple_drive__ubuntu_xenial_amd64__binary)

A simple robot drive system that includes skid steering joystick teleoperation, control of a panning servo to look around the robot, and Arduino firmware.

<p align="center">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=Xbox_Controller.png" alt="Drawing" width="45%">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=R3+in+Utah-low.JPG" alt="Drawing" width="45%">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=Simple_Drive_Diagram.png" alt="Drawing" width="80%">
</p>

Full documentation on wiki: [http://wiki.ros.org/simple_drive](http://wiki.ros.org/simple_drive)


## simple_arm [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)

Simple velocity controlled arm. Teleoperation software and firmware.

![follow_waypoints](http://wiki.ros.org/simple_arm?action=AttachFile&do=get&target=simple+arm+joystick+diagram.png "rviz")

Full documentation on wiki: [http://wiki.ros.org/simple_arm](http://wiki.ros.org/simple_arm)

## hugin_panorama [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__hugin_panorama__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__hugin_panorama__ubuntu_xenial_amd64__binary)

Create panoramas in ROS using image snapshots or multiple video streams.

![follow_waypoints](http://wiki.ros.org/hugin_panorama?action=AttachFile&do=get&target=pano_by_senza_senso.JPG "rviz")

Full documentation on wiki: [http://wiki.ros.org/hugin_panorama](http://wiki.ros.org/hugin_panorama)


## follow_waypoints [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)

A package that will buffer `move_base` goals until instructed to navigate to all waypoints in sequence.

![follow_waypoints](https://github.com/danielsnider/follow_waypoints/blob/master/readme_images/follow_waypoints_rviz.png "rviz")

Full documentation on wiki: [http://wiki.ros.org/follow_waypoints](http://wiki.ros.org/follow_waypoints)


## image_overlay_scale_and_compass [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)

Add an indication of scale and compass to images.

![image_overlay_scale_and_compass](http://wiki.ros.org/image_overlay_scale_and_compass?action=AttachFile&do=get&target=mars.png "mars")

Full documentation on wiki: [http://wiki.ros.org/image_overlay_scale_and_compass](http://wiki.ros.org/image_overlay_scale_and_compass)

## lost_comms_recovery [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__lost_comms_recovery__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__lost_comms_recovery__ubuntu_xenial_amd64__binary)

If your robot loses connection to the base station it will stop motors or navigate home.

Full documentation on wiki: [http://wiki.ros.org/lost_comms_recovery](http://wiki.ros.org/lost_comms_recovery)


## GPS_goal [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)

Set a ROS navigation goal using latitude and longitude.

Full documentation on wiki: [http://wiki.ros.org/GPS_goal](http://wiki.ros.org/GPS_goal)

