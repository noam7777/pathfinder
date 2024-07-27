virtual environment path:
/home/noam/Documents/learning/probebalisticRobotics/code/myenv2/bin/activate

to compile, go to the ros2_ws directory and run
colcon build --symlink-install

then to run:
ros2 launch pathfinder nh_single_bot_sim.launch_in_sarona.py


requirements:
for the auto teleop terminal from the launch file:
sudo apt install xterm 