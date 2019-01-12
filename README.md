# kinova_ws
Workspace for Kinova Gen3 arm--to be updated as more support from Kinova rolls out. Currently built and run on Ubuntu 16.04 and ROS Kinetic Kame.


<!-- MarkdownTOC -->

1. [Get control loop parameters](#get-control-loop-parameters)
1. [Set control loop parameters](#set-control-loop-parameters)
1. [Play cartesian](#play-cartesian)
1. [Play cartesian position](#play-cartesian-position)
1. [Get sensor settings](#get-sensor-settings)
1. [Read all devices](#read-all-devices)
1. [System Setup](#system-setup)

<!-- /MarkdownTOC -->

<a id="system-setup"></a>
## System Setup
<p>
Install system dependencies and test system setup.
</p>

- Kinova KORTEX API (https://github.com/Kinovarobotics/kortex)
- KINOVA ROS_KORTEX PACKAGE
- Google 


To run this example, those node need to be running:
> - kortex\_device\_manager (**rosrun kortex\_device\_manager kortex\_device\_manager 192.168.1.10**)
> - kortex\_actuator\_driver (**rosrun kortex\_actuator\_driver kortex\_actuator\_driver 192.168.1.10 100**)

\* Note here that the address **192.168.1.10** is the default IP address of a robot but you can put any IP address that suits your need.

To run the example:

<code>rosrun kortex_examples GetControlLoopParameters</code>


<a id="get-control-loop-parameters"></a>
## Get control loop parameters
<p>
Gets the control loop parameters from an actuator that is part of a Gen3 robot. 
</p>

To run this example, those node need to be running:
> - kortex\_device\_manager (**rosrun kortex\_device\_manager kortex\_device\_manager 192.168.1.10**)
> - kortex\_actuator\_driver (**rosrun kortex\_actuator\_driver kortex\_actuator\_driver 192.168.1.10 100**)

\* Note here that the address **192.168.1.10** is the default IP address of a robot but you can put any IP address that suits your need.

To run the example:

<code>rosrun kortex_examples GetControlLoopParameters</code>
