cmake_minimum_required(VERSION 2.8.3)
project(ros_control_gazebo)

# Load catkin and all dependencies required for this package
# TODO: remove all from COMPONENTS that are not catkin packages.
find_package(catkin REQUIRED COMPONENTS roscpp gazebo_ros hardware_interface)

# TODO: fill in what other packages will need to use this package
## DEPENDS: system dependencies of this project that dependent projects also need
## CATKIN_DEPENDS: catkin_packages dependent projects also need
## INCLUDE_DIRS: 
## LIBRARIES: libraries you create in this project that dependent projects also need
catkin_package(
    DEPENDS gazebo
    CATKIN_DEPENDS roscpp gazebo_ros hardware_interface
    INCLUDE_DIRS include # TODO include
    LIBRARIES # TODO
)
