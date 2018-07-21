# Minecraft Command Package Manager

这是一个Minecraft游戏Java版本(>=1.13)的数据包。它主要用于支持在同一个存档下的其它数据包，以及能可视化管理其它正在受支持的数据包。

## 开放接口说明

这个数据包提供了大量的接口函数与变量，使得依赖于此的其它数据包可以做到：

* 可以被玩家(单机游戏)或服务器管理员(多人游戏)启用或禁用数据包
* 可以启动可视化的数据包配置界面
* 可以进行可回退且快捷的方块、物品、实体更改，能够进行复杂的编辑
* 可以在存档中建立数据库，存储需要的任何数据
* 可以对存档外部进行一定能力的通讯，从游戏外取得数据，或发送数据到游戏外
* 可以让不同的数据包之间能共享数据、交换数据
* 可以设置定时事件与特定事件的侦听器