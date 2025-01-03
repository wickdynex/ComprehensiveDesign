## 工作成果

### 需求

1. 室内运输
2. 负荷小
3. 速度快
4. 可监控
5. 可人工干预
6. 客户等待时间短
7. 可寻路

### 应用场景

酒店内物品运输，比如饮料，房卡，外卖，一次性用品等。用户发送请求，小车自动规划运输l路径。通过手机端和网页端发送指令，可以人工干预小车；通过小车回传的图像可监控小车工作情况。使用`旅行商算法`，最小化所有客户的等待时间。使用`A*`，自动寻路。

### 新功能

1. 手机控制小车
2. 路径规划
3. 物品运输

### 实现过程

1. 树莓派上安装控制台，手机安装对应的应用。通过手机上的应用程序发送指令到控制台，进而控制小车，小车返回传输的图像，用于测试。
2. 旅行商算法规划送货路径，最小化客户的等待时间。
3. A*算法规划运动路径，规避可能的障碍物。
4. 安装运输模块，实现运输物品的功能。

### 软件架构

#### donkeycar

模版创建donkeycar -> 线程化部件 -> 线程共享数据区

#### console + client-end

C/S架构 + 前后端分离 + 模块化设计

