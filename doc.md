# Theme

SCALE

# 想法

物件规模缩放？

交互——改变缩放？改变材质？

极简风格，无材质，基础几何形状

白色自发光物体——引导交互

playground——~~黑色~~ 灰色

场景变化解密——物件缩放

> 切题

缩放开启前进路线

- 开启墙壁缝

- 拓展道路

核心解密点

- 交互物件的顺序

> 光敏性癫痫警告



> 让玩家“下意识”的认为哪些物体不能够交互
> 
> - 更改 kill-zone 的颜色为红色，交互物体的激活状态改为~~蓝色~~绿色
> 
> - 添加提示色：蓝色

# Level1

教学关卡

简单的基础长方体空间

> 初始的黑暗场景是否过于视觉不友好
> 
> - 设置一点弱灯光
>   
>   - 放置灯光块

了解基础移动

教学：与光亮物体的交互——场景变化

> 是否需要设置一些练习
> 
> - ~~针对移动：稍微复杂的场景移动~~
> 
> - 针对交互物体：灯光让玩家交互开启
>   
>   - 灯光块应该让玩家能够在操作交互物体后直接看到
>     
>     - 交互后改变  ~~位置~~  缩放
>     - 交互后灯块变化会让玩家认为是可被交互的吗？
>       - 让玩家无法交互

- 交互物体1：交互完成后销毁

## 流程

- 学习  ~~移动~~  交互

- 交互完所有物体前往下一关

# Level2

教学关卡

> LV1 和 LV2 属于场景非常相似的 LV，如何让玩家感受到关卡的变化？
> 
> - 和 level1 相比，更改了一下灯块的位置

~~交互物体2：交互完成后改变材质~~

交互物体1：交互完成后销毁

基本 scale 变化机制教学：道路搭建

加入道路阻挡机制

> 如何避免 jump scare ， 让玩家能够预先有准备
> 
> - 提示：在同位置上方放置光块
> 
> 意义不明，删除

掉入虚空死亡

> 注意区分虚空和地板，让玩家容易看到区别

## 流程

- 交互物体开启道路

- 前往目标物体直接触发下一关

# Level3

核心关卡

交互物体3：交互完成后改变材质，可以重复交互更改目标的缩放

在墙壁缝中隐藏交互物体

以光亮引导玩家前进

添加引导线

> **流程**
> 
> - 简单的缩放制造地板
> 
> - 墙缝光亮引导：下一个目标 = 移开墙壁 = 交互物体
> 
> > 如何摆放交互物体以达到解密效果？
> > 
> > 物件的交互顺序？

自行搭建道路——~~顺序选择~~ 

缩放后阻挡道路 = 重新缩放物体

> 让玩家专注于核心区域的缩放解密
> 
> - 添加 Gateway

## 流程

- 学习重复使用交互物体

- 开启墙缝

- 前往核心区域，完成道路搭建

- 结束游戏

# Level4

高低差缩放

> 玩家在操纵物体时无法清晰的同步看到变化
> 
> - 地板改为透明材质



> 物件之间区分度不高
> 
> - 相邻物件之间设置不同材质
>   
>   - 注意区分交互块的材质



> 玩家可以跨块移动
> 
> - 下落速度？移动速度？
