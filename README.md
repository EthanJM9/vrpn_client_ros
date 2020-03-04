# vrpn_client_ros
Ethan Marcello worked with Prof Dawkins to get this together so we're saving it! 

To setup the ROS, follow guidance from this link:
        http://wiki.ros.org/ROS/Tutorials/BuildingPackages 

Work with Prof Dawkins: 
USE VRPN TO COMMUNICATE WITH OPTITRACK.
Install Ros pkg vrpn_client_ros (use this repository, but you could also use the one on github under ros-drivers/vrpn_client_ros which should also work). Also need the vrpn related libraries for ros (and possibly for rospy, if they exist).
Run catkin_make on catkin_ws. Will get errors. 

////IMPORTANT. IF STRUGGLING WITH THIS PART PROFESSOR DAWKINS SHOULD BE ABLE TO ASSIST///////
CMake file needs certain additions (I think you add the necessary CMake statements from the vrpn package to the CMake global .txt file...). Professor Dawkins made a bunch of copies of certain files to help the cmake do its thing. Got a successful catkin_make eventually once this was set up properly.

Further guidance on actually running the whoenig files for the crazyflie demos can be found in Ethan Marcello's Progress File document.
