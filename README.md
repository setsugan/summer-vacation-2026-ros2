# summer-vacation-2026-ros2

![alt text](documents/images/gazebo.png)

## シミュレーション

Gazeboを用いたシミュレーションです。

```bash
ros2 launch sum2026_bringup sim.launch.xml
```

```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_drive_controller/cmd_vel -p stamped:=true
```

## 使用したツール

- sdf2map（sdfからoccupancygridを生成する）
https://github.com/atinfinity/sdf2map
