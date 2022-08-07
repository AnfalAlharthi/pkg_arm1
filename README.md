# pkg_arm1
task 2


المھمة الثانیة ) تثبیت بكج الذراع (
• عشان اثبت بكج الذراع فتحت التیرمنال ف الاوبنتو وكتبت ھذي الأوامر
cd ~/catkin_ws/
catkin_make
cd ~/catkin_ws/src
git clone https://github.com/smart-methods/arduino_robot_arm.git cd ~/catkin_ws
rosdep install --from-paths src --ignore-src -r -y sudo apt-get install ros-noetic-moveit
sudo apt-get install ros-noetic-joint-state-publisher ros-noetic- joint-state-publisher-gui
sudo apt-get install ros-noetic-gazebo-ros-control joint-state- publisher
sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros- control
catkin_make
• للتاكد من تثبیت بكج الذراع roslaunch robot_arm_pkg check_motors.launch
￼
 
