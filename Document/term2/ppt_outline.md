# PPT大纲

## 送货小车

### 项目概述 5 邱

#### 开发环境 2

硬件环境 + 软件环境

硬件环境 raspberry pi 4b 1

软件环境 linux + python(pytest) + docker 1

#### 应用场景 1

酒店内物品运输，比如饮料，房卡，外卖，一次性用品等。用户发送请求，小车自动规划运输l路径。通过手机端和网页端发送指令，可以人工干预小车；通过小车回传的图像可监控小车工作情况。使用`旅行商算法`，最小化所有客户的等待时间。使用`A*`，自动寻路。

#### 需求 1

1. 室内运输
2. 可监控
3. 客户等待时间短
4. 可寻路

#### 功能实现 1

1. 手机控制小车
2. 路径规划
3. 物品运输

### 开发流程 7 

#### 小车服务端开发 4 高

Docker + Python + 项目架构 + api举例

#### 路径规划算法 4 杨

查找论文 + 抽象建模 + 测试算法正确性

A* + 旅行商

#### 物品运输 1

### 测试开发 5

#### 测试框架 3 高

pytest

测试驱动开发：写开发文档 -> 讨论api设计 -> 编写测试代码 -> 编写业务代码 -> 通过测试合并

#### 协作开发工具 2 杨

Git/GitHub GitHub PR, Issue, Action

### 成果展示 3 努

#### 避障

20s

#### 遥控小车

20s

