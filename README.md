# panther-nav2-demo :no_entry_sign:

> **Warning**
>
> We have migrated the development of the `panther-nav2-demo` to the [panther-navigation](https://github.com/husarion/panther-navigation) repository.
>
> For additional guidance on configuring the Panther robot and running demos, refer to the [panther-docker](https://github.com/husarion/panther-docker) repository or check out the manuals available on the official Husarion [website](https://husarion.com/manuals/panther/).

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
