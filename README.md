ethzasl_ptam
============

Modified version of Parallel Tracking and Mapping (PTAM) by George Klein. See http://wiki.ros.org/ethzasl_ptam for a detailed overview.

[![Build Status](http://129.132.38.183:8080/job/ethzasl_ptam/badge/icon)](http://129.132.38.183:8080/job/ethzasl_ptam/)

To install ethzasl_ptam on ROS Kinetic, git clone with parameter "-b kineticbuild", i.e "git clone -b kineticbuild https://..", to catkin_ws/src and run catkin_make to compile. Tested on Ubuntu 16.04 and ROS Kinetic. Original repo will cause this error during compilation:

fatal error: rqt_gui_cpp/plugin.h: No such file or directory
compilation terminated.
In file included from /home/stemdev/catkin_ws/src/ethzasl_ptam/rqt_ptam/src/rqt_ptam/remote_ptam.cpp:34:0:
