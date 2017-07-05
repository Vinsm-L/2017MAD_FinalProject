# 2017现操期末项目（v0, 2017.7.5）
## 简介
一个拥有2种怪，2种塔，1种地图的游戏，可以用打怪获得的积分换塔

## 实现
分为以下几个类来实现：
* Enemy1：怪物1，图片在resources文件中找，死亡时使用粒子效果
* Enemy2：怪物2，比怪物1难打（例如怪物1用塔1的一个子弹就能杀死的话，怪物2就需要更多才能杀死），图片在resources文件中找，死亡时使用粒子效果
* Tower1：塔1，能释放子弹，图片在resources文件中找
* Tower2：塔2，能释放子弹（伤害比塔1的高），图片在resources文件中找
* WayPoint：在地图中记录路径中的一个个点，用来给怪物走的
* GameLayer：加载怪物的动画、背景音乐，记录并保存积分（本地存储），设置怪物的行走路径，加载怪物、地图（地图要与行走路径匹配），设置调度器、菜单按钮（用来添加塔）等等

类的编写可以参考https://github.com/kmuzykov/TowerDefence-Cocos2d-x/tree/master/TowerDefence/Classes 。 可以继续补充。

## 分工
分为以下四个部分，每个部分由一个人负责：
1. Enemy1、Enemy2的编写
2. Tower1、Tower2的编写
3. WayPoint、GameLayer的编写
4. 整合游戏

最后负责第1和第2部分的人协商写一下实验报告跟录个视频吧？