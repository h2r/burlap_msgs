burlap_msgs
===========

A ROS project that contains *only* the message files necessary for connecting ROS and [BURLAP](http://burlap.cs.brown.edu). Currently, the messages included
are for defining BURLAP state ROS messages. In the future, we plan to add message support for communicating human-delivered 
reward/punishment, termination state information, and BURLAP domain specifications. 

The state messages are taken from Kevin Farrell's work on
[connecting BURALP and ROS for a cooking domain with ROSJava](https://github.com/h2r/burlap_rosjava). 

You can use these messages either in conjunciton with a ROSJava project or by using the 
[burlap_rosbridge](https://github.com/h2r/burlap_rosbridge) BURLAP library extension with ROSBridge running on the ROS server.


