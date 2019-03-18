### ROS Kinetic

#### Version 0.2.75 (current kinetic-release) 

Features:

* Fixed bug "Test SRC-T32 Grasping Pipeline for flexible hand release fails"
* Implement a proper way to setup the configuration of optoforce sensors for hand h
* Add possibility to switch in RQT to Grasp Controller for Hand H
* Modify Hand H/E release process to include debug symbols
* Mujoco_ros repo cleanup
* ROS log data warning
* Improvements of the manipulation pipeline: Check the plan until place
* Delete old logs when we exceed limit
* Export robot states from mongo to python/yaml
* Implement a proper way to setup the configuration of optoforce sensors for hand h

#### Version 0.2.43

Features:

* REST API new functionality:
  * Two new calls to open rqt plugins: Joint sliders and Change controllers
  * New calls and buttons to import, export and delete grasps from database
  * New tab with template to create new grasp
* Refactored the grasp database to have all the functionality only available in sr_manipulation
* AWS client is installed inside the Docker image (for uploading ROS logs and core dumps to AWS)
* Python and C++ core dumps have been added to ROS logs and the upload to AWS
* New demo page has been added to REST API and the demo looping through all grasps is now available in that page
* "Create grasp" page has been renamed to "Grasp Editor" and new grasp visualiser is available to check all information related to a grasp
* mujoco_ros repo has been cleaned up
* Fixed open_change_controllers failing on REST API because of a missing dependency
* Fixed RESTful API to get all sources locally and not depend on having internet connection

#### Version 0.2.28

Features:

* Firmware built with PSOC 4.2
* Ability to save ROS logs by clicking on an icon on the desktop
* REST API available (via a browser window)
* Ability to bypass safety for the fingers

#### Version 0.2.24

Initial version
