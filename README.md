# Z1_NMPC
这个仓库主要做了宇树Z1机械臂的NMPC高频控制，基于下面的两个仓库做了一些修使其更加稳定，但由于宇树的硬件原因，还是会有一些抖动，可以参考视频看一下。

<p align="center">
  <img src="readme_source/123.gif" alt="说明文本" width="600">
</p>

## Install dependencies
```bash
$ ocs2 sqp mpc implementation on unitree z1
$ rosrun unitree_z1_mpc policy_to_real
$ ./z1_ctrl
$ roslaunch ocs2_mobile_manipulator_ros z1_real_arm.launch
```

## Reference link
https://github.com/GoldenSeaC/z1_nmpc_pkg.git

https://github.com/leggedrobotics/ocs2.git

https://github.com/Hongtai-Yuan/UnitreeZ1_Calib.git

