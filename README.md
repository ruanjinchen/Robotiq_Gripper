# 介绍
该repo记录了如何使用ur_rtde的库去控制Robotiq Gripper。这是我发现的另一个非常好用的方法。
# 资料
[ur_rtde中夹爪部分的介绍](https://sdurobotics.gitlab.io/ur_rtde/guides/guides.html#use-with-robotiq-gripper)  
[UR示教器系统POLYSCOPE下载地址](https://www.universal-robots.com/articles/ur/documentation/legacy-download-center/)
# 硬件安装步骤
前提：UR示教器已安装 Robotiq_Grippers-1.x.xx.xxxxxx.urcap。注意：这种控制方法不需要使用External Control的URCap，也就是不需要ROS所需的那个URCap😛。

记录一下我当前的UR软件版本：Robotiq_Grippers-1.8.13.22852.urcap，Robotiq_Wrist_Connection-1.1.1.3.urcap，externalcontrol-1.0.5.urcap，update-3.15.8-build10.6.339.urup
