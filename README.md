# Software design of automatic listing robot based on 3D vision
# 基于3D视觉的自动挂牌机器人软件设计
### 项目描述：
  利用上位机与3D相机线激光轮廓仪进行通信，实现对线材点云数据采集，借助PCL库模块实现对点云数据的处理与计算，得到挂牌目标点。利用Pytorch搭建神经网络模型对标牌进行训练与识别，并采用Socket通信方式，实现C#与Python之间的信息互传。并利用S7.Netplus模块实现上位机与PLC通信，进一步控制机器人自动挂牌等操作。


