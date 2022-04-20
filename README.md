# husky_custom
Custom ros packages for clearpath husky, second edition

Custom bringup script for husky:

<code>rosrun robot_upstart uninstall husky # may need to remove current service </code>

<code>rosrun robot_upstart install --job husky --interface $ROBOT_NETWORK --setup $ROBOT_SETUP --master $ROS_MASTER_URI husky_base/launch/base.launch husky_bringup/launch/um7_config/um7.launch</code>

