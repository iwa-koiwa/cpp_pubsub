rm -rf build/ install/ log/

colcon build --packages-select cpp_pubsub

source install/setup.bash

ros2 run cpp_pubsub talker
