![](http://moveit.ros.org/wordpress/wp-content/uploads/2014/01/moveit-title-small.png)

The MoveIt! Motion Planning Framework

This is the new unified repository for MoveIt! code. See the [Migration Notes](https://github.com/davetcoleman/moveit_merge/) to learn about the repo consolidation.

- [Overview of MoveIt!](http://moveit.ros.org)
- [Installation Instructions](http://moveit.ros.org/install/)
- [Documentation](http://moveit.ros.org/documentation/)
- [Docker Containers](http://moveit.ros.org/install/docker)
- [Get Involved](http://moveit.ros.org/documentation/contributing/)

## Travis - Continuous Integration

Indigo | Jade | Kinetic
------ | ---- | -------
[![Build Status](https://travis-ci.org/ros-planning/moveit.svg?branch=indigo-devel)](https://travis-ci.org/ros-planning/moveit) | [![Build Status](https://travis-ci.org/ros-planning/moveit.svg?branch=jade-devel)](https://travis-ci.org/ros-planning/moveit) | [![Build Status](https://travis-ci.org/ros-planning/moveit.svg?branch=kinetic-devel)](https://travis-ci.org/ros-planning/moveit) |

## ROS Buildfarm

> Note: Kinetic is not released yet

MoveIt! Package | Indigo Source | Indigo Debian | Jade Source | Jade Debian | Kinetic Source | Kinetic Debian
------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | -------------------
geometric_shapes | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__geometric_shapes__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__geometric_shapes__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__geometric_shapes__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__geometric_shapes__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__geometric_shapes__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__geometric_shapes__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__geometric_shapes__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__geometric_shapes__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__geometric_shapes__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__geometric_shapes__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__geometric_shapes__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__geometric_shapes__ubuntu_xenial_amd64__binary/) |
moveit | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit__ubuntu_xenial_amd64__binary/) |
moveit_msgs | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_msgs__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_msgs__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_msgs__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_msgs__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_msgs__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_msgs__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_msgs__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_msgs__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_msgs__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_msgs__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_msgs__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_msgs__ubuntu_xenial_amd64__binary/) |
moveit_core | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_core__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_core__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_core__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_core__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_core__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_core__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_core__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_core__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_core__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_core__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_core__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_core__ubuntu_xenial_amd64__binary/) |
moveit_ros | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros__ubuntu_xenial_amd64__binary/) |
moveit_ros_benchmarks | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_benchmarks__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_benchmarks__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_benchmarks__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_benchmarks__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_benchmarks__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_benchmarks__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_benchmarks__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_benchmarks__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_benchmarks__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_benchmarks__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_benchmarks__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_benchmarks__ubuntu_xenial_amd64__binary/) |
moveit_ros_benchmarks_gui | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_benchmarks_gui__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_benchmarks_gui__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_benchmarks_gui__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_benchmarks_gui__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_benchmarks_gui__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_benchmarks_gui__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_benchmarks_gui__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_benchmarks_gui__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_benchmarks_gui__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_benchmarks_gui__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_benchmarks_gui__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_benchmarks_gui__ubuntu_xenial_amd64__binary/) |
moveit_ros_manipulation | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_manipulation__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_manipulation__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_manipulation__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_manipulation__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_manipulation__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_manipulation__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_manipulation__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_manipulation__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_manipulation__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_manipulation__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_manipulation__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_manipulation__ubuntu_xenial_amd64__binary/) |
moveit_ros_move_group | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_move_group__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_move_group__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_move_group__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_move_group__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_move_group__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_move_group__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_move_group__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_move_group__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_move_group__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_move_group__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_move_group__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_move_group__ubuntu_xenial_amd64__binary/) |
moveit_ros_perception | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_perception__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_perception__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_perception__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_perception__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_perception__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_perception__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_perception__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_perception__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_perception__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_perception__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_perception__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_perception__ubuntu_xenial_amd64__binary/) |
moveit_ros_planning | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_planning__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_planning__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_planning__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_planning__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_planning__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_planning__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_planning__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_planning__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_planning__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_planning__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_planning__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_planning__ubuntu_xenial_amd64__binary/) |
moveit_ros_planning_interface | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_planning_interface__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_planning_interface__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_planning_interface__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_planning_interface__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_planning_interface__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_planning_interface__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_planning_interface__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_planning_interface__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_planning_interface__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_planning_interface__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_planning_interface__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_planning_interface__ubuntu_xenial_amd64__binary/) |
moveit_ros_robot_interaction | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_robot_interaction__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_robot_interaction__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_robot_interaction__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_robot_interaction__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_robot_interaction__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_robot_interaction__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_robot_interaction__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_robot_interaction__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_robot_interaction__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_robot_interaction__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_robot_interaction__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_robot_interaction__ubuntu_xenial_amd64__binary/) |
moveit_ros_visualization | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_visualization__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_visualization__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_visualization__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_visualization__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_visualization__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_visualization__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_visualization__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_visualization__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_visualization__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_visualization__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_visualization__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_visualization__ubuntu_xenial_amd64__binary/) |
moveit_ros_warehouse | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ros_warehouse__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ros_warehouse__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ros_warehouse__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ros_warehouse__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ros_warehouse__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ros_warehouse__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ros_warehouse__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ros_warehouse__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ros_warehouse__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ros_warehouse__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ros_warehouse__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ros_warehouse__ubuntu_xenial_amd64__binary/) |
moveit_planners | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_planners__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_planners__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_planners__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_planners__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_planners__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_planners__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_planners__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_planners__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_planners__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_planners__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_planners__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_planners__ubuntu_xenial_amd64__binary/) |
moveit_planners_ompl | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_planners_ompl__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_planners_ompl__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_planners_ompl__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_planners_ompl__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_planners_ompl__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_planners_ompl__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_planners_ompl__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_planners_ompl__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_planners_ompl__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_planners_ompl__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_planners_ompl__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_planners_ompl__ubuntu_xenial_amd64__binary/) |
moveit_setup_assistant | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_setup_assistant__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_setup_assistant__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_setup_assistant__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_setup_assistant__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_setup_assistant__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_setup_assistant__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_setup_assistant__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_setup_assistant__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_setup_assistant__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_setup_assistant__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_setup_assistant__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_setup_assistant__ubuntu_xenial_amd64__binary/) |
moveit_plugins | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_plugins__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_plugins__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_plugins__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_plugins__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_plugins__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_plugins__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_plugins__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_plugins__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_plugins__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_plugins__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_plugins__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_plugins__ubuntu_xenial_amd64__binary/) |
moveit_ikfast | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_ikfast__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_ikfast__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_ikfast__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_ikfast__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_ikfast__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_ikfast__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_ikfast__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_ikfast__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_ikfast__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_ikfast__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_ikfast__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_ikfast__ubuntu_xenial_amd64__binary/) |
moveit_commander | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__moveit_commander__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__moveit_commander__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__moveit_commander__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__moveit_commander__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__moveit_commander__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__moveit_commander__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__moveit_commander__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__moveit_commander__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__moveit_commander__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__moveit_commander__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__moveit_commander__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__moveit_commander__ubuntu_xenial_amd64__binary/) |
random_numbers | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__random_numbers__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__random_numbers__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__random_numbers__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__random_numbers__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__random_numbers__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__random_numbers__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__random_numbers__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__random_numbers__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__random_numbers__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__random_numbers__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__random_numbers__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__random_numbers__ubuntu_xenial_amd64__binary/) |
srdfdom | [![Build Status](http://build.ros.org/buildStatus/icon?job=Isrc_uT__srdfdom__ubuntu_trusty__source)](http://build.ros.org/view/Isrc_uT/job/Isrc_uT__srdfdom__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ibin_uT64__srdfdom__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Ibin_uT64/job/Ibin_uT64__srdfdom__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jsrc_uT__srdfdom__ubuntu_trusty__source)](http://build.ros.org/view/Jsrc_uT/job/Jsrc_uT__srdfdom__ubuntu_trusty__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Jbin_uT64__srdfdom__ubuntu_trusty_amd64__binary)](http://build.ros.org/view/Jbin_uT64/job/Jbin_uT64__srdfdom__ubuntu_trusty_amd64__binary/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Ksrc_uX__srdfdom__ubuntu_xenial__source)](http://build.ros.org/view/Ksrc_uX/job/Ksrc_uX__srdfdom__ubuntu_xenial__source/) | [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__srdfdom__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__srdfdom__ubuntu_xenial_amd64__binary/) |
