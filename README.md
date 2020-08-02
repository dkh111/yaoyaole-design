# 2020年新工科联盟-Xilinx暑期学校（Summer School）项目。
## 项目名称
+ 摇摇乐（陀螺仪+AWS）
## 设计概述
+ 设计目的：完成简易计步器，方便完成计步功能。
+ 相关知识： AWS云服务器结点的创建，vivado代码的编写，arduino代码的编写，qspi串口通信。
## 技术前景
+ FPGA最大的优点在于更大的并行度，可定制和可重构，利用FPGA跟低功耗和高便携的特点能更好的实现计步器功能。
## 已实现功能
+ 能够做到正确采集IMU传感器获取数据并换算得出手摇开发板的次数，并将数据传输到AWS的云端服务器节点上。
## 项目成员
+ 杜康华
## 工具版本
+ vivado2018.3
+ ardunio1.8
+ mqtt.fx1.6
## 板卡型号与外设列表
+ 板卡型号: SEA
+ 芯片型号：spartan7 xcs15
## 仓库⽬录介绍
+ images——作品图片与项目框图
+ project and code——FPGA_Project：vivado源代码
+ project and code——Gyro_Demo.bit：所需烧录的bit文件
+ project and code——Gyro2AWSloT：arduino工程文件及qspi通信协议
