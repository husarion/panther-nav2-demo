# panther-nav2-demo
Panther autonomous mobiel robot running Nav2 navigation stack (ROS 2), and controled from Rviz

## Run docker with navigation:

``` bash
cd panther_nav2_docker
xhost local:docker
docker-compose -up
```

This should open VNC desktop

To run Rviz open LXTerminal an type:

`ros2 run rviz2 rviz2`

use 2D Goal Pose to move Panther around.

Click on picture to watch video.

<p align=center>
<a href="https://www.youtube.com/watch?v=6kPhuRqiOVg"><img src="https://img.youtube.com/vi/6kPhuRqiOVg/0.jpg" title="Click to see video">
</p>
