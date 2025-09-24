FROM --platform=linux/arm64 osrf/ros:jazzy-desktop
WORKDIR /ros2_ws
ENV ROS2_DISTRO jazzy
RUN sudo apt install ros-jazzy-depthai-ros
RUN sudo apt install ros-jazzy-joy_teleop
RUN sudo apt install ros-jazzy-slam_toolbox
RUN sudo apt install ros-jazzy-ublox_gps
CMD ["/bin/bash", "-c", "source /opt/ros/jazzy/setup.bash && source /ros_ws/install/setup.bash && exec bash"]
