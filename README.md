# Aceve的百宝箱

这是一个为**Minecraft Java版多人游戏**编写的数据包

## 版本信息
数据包版本：15【游戏版本：1.20（23w18a）及以上】
向下兼容：10-14【游戏版本：低至1.19（22w11a）】
*低于「向下兼容」的版本未经测试，该数据包可能会无法工作*

## 功能

添加了：
- 死亡数显示（右侧计分板）
- 生命值显示（Tab栏）
- 经验显示（玩家名下方）

同时，为无权限（权限等级为0）的玩家提供了以下功能：
- 模式切换：旁观
- 模式切换：生存
- 快捷功能：自杀（双重确认）

## 命令列表

需要权限：
- 启用死亡数、生命值、经验显示 `/function minecraft:displayerdata`
- 禁用死亡数、生命值、经验显示 `/function minecraft:redisplayerdata`

不需权限：
- 模式切换：旁观 `/trigger spectator`
- 模式切换：生存 `/trigger survival`
- 快捷功能：自杀 `/trigger kill`
