# Custom dependencies for ROS2 project

Based on https://answers.ros.org/question/380740/best-practice-installing-custom-dependencies-for-ros2/

This repo is used to install custom dependencies for a ROS2 project.

Update the YAML file in this repo, then install the dependencies with
```
rosdep update
rosdep install -i --from-path src --rosdistro humble -y
```

These commmands are included in the "Base" Dockerfile.
