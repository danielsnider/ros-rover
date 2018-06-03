This page lists open source contributions made by Team R3 of Ryerson University in Toronto, Canada and built for the University Rover Challenge (URC) 2017. We share our rover software architecture diagram and several ROS packages for the URC competition.

**Full source code for our rover: https://github.com/danielsnider/URC**

### Demonstration of Autonomous Rover Navigation (Click to view video)

<p align="center">
  <a href="https://www.youtube.com/watch?v=p_1nkSQS8HE"><img src="https://img.youtube.com/vi/p_1nkSQS8HE/0.jpg" target="_blank" alt="demo" width="40%"></a>
 <a href="https://www.youtube.com/watch?v=p_1nkSQS8HE"><img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/montage.PNG?raw=true" alt="Drawing" width="50%"></a>
</p>

More glory shots of rover: https://www.youtube.com/watch?v=DtilGB2vnQI

## Published Book Chapter:

**Robot Operating System (ROS): The Complete Reference (Volume 3), Studies in Computational Intelligence** Released July 2, 2018.

Detailed instructions and tips are published in a book chapter. <br>
Link to chapter: [PDF](https://github.com/danielsnider/ros-rover/raw/master/Book%20Chapter%20-%20University%20Rover%20Challenge%20Tutorials%20and%20Control%20System%20Survey.pdf), [LATEX](https://github.com/danielsnider/ros-rover/raw/master/diagrams/LATEX%20Book%20Chapter.zip), or an older [DOCX](https://github.com/danielsnider/ros-rover/raw/master/diagrams/DOCX%20Book%20Chapter%20-%20University%20Rover%20Challenge%20Tutorials%20and%20Control%20System%20Survey.docx) version. <br>
Link to [book on Amazon](https://www.amazon.com/Robot-Operating-System-ROS-Computational/dp/3319915894/ref=sr_1_fkmr0_3?ie=UTF8&qid=1526347481&sr=8-3-fkmr0&keywords=complete+guide+to+robot+operating+system).

<p align="center">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/book_cover.png?raw=true" alt="Drawing" height="400px">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/chapter_first_page.png?raw=true" alt="Drawing" height="400px">

</p>

**Full documentation in a book chapter: [Book Chapter - University Rover Challenge Tutorials and Team Survey.pdf](https://github.com/danielsnider/ros-rover/raw/master/Book%20Chapter%20-%20University%20Rover%20Challenge%20Tutorials%20and%20Control%20System%20Survey.pdf)**

## Rover Diagram:

![Rover_Diagram](https://raw.githubusercontent.com/danielsnider/ros-rover/master/diagrams/Rover_Diagram.png)

Rover Diagram in Visio Format: [Rover_Diagram.vsdx](https://github.com/danielsnider/ros-rover/blob/master/diagrams/Rover_Diagram.vsdx?raw=true)

ROS-Rover was built with ROS Kinetic and Ubuntu 16.04, and it has five main systems: the drive system, the autonomous system, the global positioning system, the visual feedback system, and the odometry system. 

#### Autonomous System (Diagram Reference)

1\. zed-ros-wrapper [http://wiki.ros.org/zed-ros-wrapper](http://wiki.ros.org/zed-ros-wrapper)<br>
2\. follow_waypoints.py [http://wiki.ros.org/follow_waypoints](http://wiki.ros.org/follow_waypoints)<br>
3\. rgbd_odometry [http://wiki.ros.org/rtabmap_ros#rgbd_odometry](http://wiki.ros.org/rtabmap_ros#rgbd_odometry)<br>
4\. rtabmap [http://wiki.ros.org/rtabmap_ros](http://wiki.ros.org/rtabmap_ros)<br>
21\. gps_goal.py [http://wiki.ros.org/gps_goal](http://wiki.ros.org/gps_goal)<br>


#### Odometry System (Diagram Reference)

5\. ekf_localization [http://docs.ros.org/kinetic/api/robot_localization/html/](http://docs.ros.org/kinetic/api/robot_localization/html/)<br>
6\. rtimulib_ros [https://github.com/romainreignier/rtimulib_ros](https://github.com/romainreignier/rtimulib_ros)<br>
7\. navsat_transform [http://docs.ros.org/kinetic/api/robot_localization/html/](http://docs.ros.org/kinetic/api/robot_localization/html/)<br>
8\. nmea_navsat_driver [http://wiki.ros.org/nmea_navsat_driver](http://wiki.ros.org/nmea_navsat_driver)<br>



#### Drive System (Diagram Reference)

9\. joy [http://wiki.ros.org/joy](http://wiki.ros.org/joy)<br>
10\. drive_teleop.py [http://wiki.ros.org/simple_drive#drive_teleop](http://wiki.ros.org/simple_drive#drive_teleop)<br>
11\. cmd_vel_mux.py [http://wiki.ros.org/simple_drive#cmd_vel_mux](http://wiki.ros.org/simple_drive#cmd_vel_mux)<br>
12\. simple_drive.py [http://wiki.ros.org/simple_drive#simple_drive-1](http://wiki.ros.org/simple_drive#simple_drive-1)<br>


#### Navigation Stack (Diagram Reference)

13\. move_base [http://wiki.ros.org/move_base](http://wiki.ros.org/move_base)<br>
14\. Cost Map costmap_2d [http://wiki.ros.org/costmap_2d](http://wiki.ros.org/costmap_2d)<br>
15\. Cost Map Obstacle Layer [http://wiki.ros.org/costmap_2d/hydro/obstacles](http://wiki.ros.org/costmap_2d/hydro/obstacles)<br>
16\. Cost Map Static Layer [http://wiki.ros.org/costmap_2d/hydro/staticmap](http://wiki.ros.org/costmap_2d/hydro/staticmap)<br>
17\. Global Planner Navfn [http://wiki.ros.org/navfn](http://wiki.ros.org/navfn)<br>
18\. Local Planner base_local_planner [http://wiki.ros.org/base_local_planner](http://wiki.ros.org/base_local_planner)<br>


#### Visual Feedback (Diagram Reference)

19\. RViz [http://wiki.ros.org/rviz](http://wiki.ros.org/rviz)<br>
20\. rqt_image_view [http://wiki.ros.org/rqt_image_view](http://wiki.ros.org/rqt_image_view)<br>
22\. MapViz [http://wiki.ros.org/mapviz](http://wiki.ros.org/mapviz)<br>
23\. usb_cam [http://wiki.ros.org/usb_cam](http://wiki.ros.org/usb_cam)<br>


## simple_drive [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__simple_drive__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__simple_drive__ubuntu_xenial_amd64__binary)

A simple robot drive system for skid steering joystick teleoperation, control of a panning servo to look around the robot, and Arduino firmware.

<p align="center">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=Xbox_Controller.png" alt="Drawing" width="45%">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=R3+in+Utah-low.JPG" alt="Drawing" width="45%">
 <img src="http://wiki.ros.org/simple_drive?action=AttachFile&do=get&target=Simple_Drive_Diagram.png" alt="Drawing" width="80%">
</p>

Project homepage: [http://wiki.ros.org/simple_drive](http://wiki.ros.org/simple_drive)


## simple_arm [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__simple_arm__ubuntu_xenial_amd64__binary)

Simple 6-axis robot arm teleoperation software and Arduino firmware.

![follow_waypoints](http://wiki.ros.org/simple_arm?action=AttachFile&do=get&target=simple+arm+joystick+diagram.png "rviz")

Project homepage: [http://wiki.ros.org/simple_arm](http://wiki.ros.org/simple_arm)


## follow_waypoints [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__follow_waypoints__ubuntu_xenial_amd64__binary)

A package that will buffer `move_base` goals until instructed to navigate to all waypoints in sequence.

![follow_waypoints](https://github.com/danielsnider/follow_waypoints/blob/master/readme_images/follow_waypoints_rviz.png "rviz")

Project homepage: [http://wiki.ros.org/follow_waypoints](http://wiki.ros.org/follow_waypoints)


## image_overlay_scale_and_compass [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__image_overlay_scale_and_compass__ubuntu_xenial_amd64__binary)

Add an indication of scale and compass to live images.

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

If robot loses its network connection it will stop motors or set a goal to navigate home autonomously.

Project homepage: [http://wiki.ros.org/lost_comms_recovery](http://wiki.ros.org/lost_comms_recovery)


## GPS_goal [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kbin_uX64__GPS_goal__ubuntu_xenial_amd64__binary)

Set navigation goals in ROS frame coordinates using latitude and longitude.

Project homepage: [http://wiki.ros.org/GPS_goal](http://wiki.ros.org/GPS_goal)


## Survey of eight rover teams that competed in URC 2017

<p align="center">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/team_survey_part1.PNG" alt="Drawing" height="500px">
 <img src="https://github.com/danielsnider/ros-rover/blob/master/diagrams/team_survey_part2.PNG" alt="Drawing" height="500px">
</p>

## Advanced Terminal Organization

ROS robots are often controlled by many bash terminals and the startup sequence involves many roslaunch commands in different terminals. I demonstrate how you can use Tmux on your robot to codify your terminal layout into a powerful ROS administration system. The organized, repeatable tmux view can be shared in real-time by all of your teammembers for a consistent view of the robot's inner workings.

<p align="center">
 <img src="https://github.com/danielsnider/ros-rover/raw/master/diagrams/tmuxinator_ROS.png" alt="Drawing" width="500px">
 <img src="https://github.com/danielsnider/ros-rover/raw/master/diagrams/tmuxinator_ROS2.PNG" alt="Drawing" width="500px">
</p>

Project homepage: coming soon 

## MapProxy docker container for ROS MapViz

Proxy zoomable map tiles from Google Maps to ROS MapViz for use with outdoor robots. For easy setup of MapProxy in a docker container to proxy Google Maps satellite view into a WMTS tile service so that it can be viewed by ROS's MapViz Tile Map plugin. Support for offline maps after loading once, maps stay cached. For outdoor robotics and vehicles.

<p align="center">
 <img src="https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite/raw/master/screenshot.png" alt="Drawing" height="300px">
 <img src="https://github.com/swri-robotics/mapviz/wiki/mapviz.png" alt="Drawing" height="300px">
</p>

Project homepage: [https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite](https://github.com/danielsnider/MapViz-Tile-Map-Google-Maps-Satellite)

