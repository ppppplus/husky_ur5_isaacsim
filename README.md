- Run isaacsim with ros2_bridge extension and load usd/husky_ur5.usd
```shell
runapp
```
- Husky control
```shell
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
- ur5&robotiq moveit2
```shell
ros2 launch husky_ur5_moveit isaac_demo.launch.py
```