# Using-SLAM-map-to-launch-the-navigation

i use Ros Melodic and ubuntu-18.04


# Launch Simulation World
- `$ export TURTLEBOT3_MODEL=burger`
- `$ roslaunch turtlebot3_gazebo turtlebot3_world.launch`

# Run Navigation Node
- `$ export TURTLEBOT3_MODEL=burger`
- `$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml`
![11111111111111](https://user-images.githubusercontent.com/60845044/126443799-4acc3f49-2a4a-44ff-862f-23902788b59c.png)

![earytg25423452141243](https://user-images.githubusercontent.com/60845044/126444040-4837c9a0-4b48-4b41-bd60-40d123b7764f.png)

# To control

- `$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`
