This page lists open source contributions made by Team R3 of Ryerson University in Toronto, Canada and built for the University Rover Challenge (URC) 2017. We share our rover software architecture diagram and several ROS packages for the URC competition.

**Full source code for our rover: https://github.com/danielsnider/URC**

### Demonstration of Autonomous Rover Navigation (Click to view video)

<p align="center">
  <a href="https://www.youtube.com/watch?v=p_1nkSQS8HE"><img src="https://img.youtube.com/vi/p_1nkSQS8HE/0.jpg" target="_blank" alt="demo" width="40%"></a>
 <a href="https://www.youtube.com/watch?v=p_1nkSQS8HE"><img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/montage.PNG?raw=true" alt="Drawing" width="50%"></a>
</p>

More glory shots of rover: https://www.youtube.com/watch?v=DtilGB2vnQI

## Detailed Software Design in Published Book Chapter:

<p align="center">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/book_cover.png?raw=true" alt="Drawing" height="400px">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/chapter_first_page.png?raw=true" alt="Drawing" height="400px">

</p>

**Full documentation in a book chapter: [Book Chapter - University Rover Challenge Tutorials and Team Survey.pdf](https://github.com/danielsnider/ros-rover/raw/master/Book%20Chapter%20-%20University%20Rover%20Challenge%20Tutorials%20and%20Control%20System%20Survey.pdf)**

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

Project homepage: [http://wiki.ros.org/simple_drive](http://wiki.ros.org/simple_drive)


## simple_arm [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)

Simple velocity controlled arm. Teleoperation software and firmware.

![follow_waypoints](http://wiki.ros.org/simple_arm?action=AttachFile&do=get&target=simple+arm+joystick+diagram.png "rviz")

Project homepage: [http://wiki.ros.org/simple_arm](http://wiki.ros.org/simple_arm)


## follow_waypoints [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)

A package that will buffer `move_base` goals until instructed to navigate to all waypoints in sequence.

![follow_waypoints](https://github.com/danielsnider/follow_waypoints/blob/master/readme_images/follow_waypoints_rviz.png "rviz")

Project homepage: [http://wiki.ros.org/follow_waypoints](http://wiki.ros.org/follow_waypoints)


## image_overlay_scale_and_compass [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)

Add an indication of scale and compass to images.

<p align="center">
 <img src="http://wiki.ros.org/image_overlay_scale_and_compass?action=AttachFile&do=get&target=mars.png" alt="Drawing" height="400px">
</p>

Project homepage: [http://wiki.ros.org/image_overlay_scale_and_compass](http://wiki.ros.org/image_overlay_scale_and_compass)

## hugin_panorama [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__hugin_panorama__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__hugin_panorama__ubuntu_xenial_amd64__binary)

Create panoramas in ROS using image snapshots or multiple video streams. 

<p align="center">
 <img src="http://wiki.ros.org/hugin_panorama?action=AttachFile&do=get&target=pano_by_senza_senso.JPG" alt="Drawing" height="250px">
</p>

Project homepage: [http://wiki.ros.org/hugin_panorama](http://wiki.ros.org/hugin_panorama)


## lost_comms_recovery [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__lost_comms_recovery__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__lost_comms_recovery__ubuntu_xenial_amd64__binary)

If your robot loses connection to the base station it will stop motors or navigate home.

Project homepage: [http://wiki.ros.org/lost_comms_recovery](http://wiki.ros.org/lost_comms_recovery)


## GPS_goal [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)

Set a ROS navigation goal using latitude and longitude.

Project homepage: [http://wiki.ros.org/GPS_goal](http://wiki.ros.org/GPS_goal)


## Survey of eight rover teams that competed in URC 2017

<p align="center">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/team_survey_part1.PNG" alt="Drawing" height="500px">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/team_survey_part2.PNG" alt="Drawing" height="500px">
</p>

## Google Maps for ROS MapViz

Easily use MapProxy in a docker container to proxy Google Maps satellite view into a WMTS tile service so that it can be viewed by ROS's MapViz Tile Map plugin. Support for offline maps after loading once, maps stay cached. For outdoor robotics and vehicles.

<p align="center">
 <img src="https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite/raw/master/screenshot.png" alt="Drawing" height="300px">
 <img src="https://github.com/swri-robotics/mapviz/wiki/mapviz.png" alt="Drawing" height="300px">
</p>

Project homepage: [https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite](https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite)
