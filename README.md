<img src="./images/Logo-ROS_2-Main.jpg" alt="../images/Logo-ROS_2-Main.jpg" height="100"/> <img src="./images/ferris.jpg" alt="../images/ferris.jpg" height="100"/>
# examples
The aim of this project is to familiarise people with the [Ros2](https://docs.ros.org) 
[Rust](https://www.rust-lang.org/) api - 
[rclrs](https://github.com/ros2-rust/ros2_rust) - and at the same time to provide more and more application examples for it. Certain nodes are offered in separate packages to create a more relaxed experience for the user and to better address different topics.  
## Getting started
Before you can do anything with this project, you first have to install a few dependencies. Please follow the [installation process](https://github.com/ros2-rust/ros2_rust/blob/main/README.md) provided by the ros2-rust main repository.
Once you've successfully installed Ros2 and ros2-rust, you need to load this project into your `workspace/src`:
```
git clone https://github.com/ros2-rust/examples.git /path/to/your/workspace/src/
```
Then you'll need to compile your workspace with and source the ros2 installation with:
```
cd WORKSPACE
colcon build
source install/setup.bash
```
Then you'll be able to run some nodes!
