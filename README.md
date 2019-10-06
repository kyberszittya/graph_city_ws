# graph_city_ws
A city workspace containing city scenes for simulators (e.g. Gazebo)

# Installation
Extract the content folder to the content folder (__gazebo_graph_explicit_city/__). Then run the script to copy contents to the ~/.gazebo folder:
```bash
./setup_content.sh
```

When ready, you can run the _./run_gazebo.sh_ script, which is composed of the follwoing commands:
```bash
rosrun gazebo_ros gzserver ./sdf/etele_street_world.sdf &
gzclient
```