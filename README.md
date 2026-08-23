# summer-vacation-2026-ros2

```bash
ros2 launch sum2026_bringup sum2026.launch.xml
```
```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_drive_controller/cmd_vel -p stamped:=true
```
