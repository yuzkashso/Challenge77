# Challenge77

Challenge77是一个健康的跑步助手，77就像两条蓄势待发的腿，challenge77即意为坚持挑战，坚持奔跑。
app有记录公里数、卡路里、绘制路线的功能。
后续还会加入蚝油社区的功能，与好友竞赛，争夺排名。

![](https://github.com/yuzkashso/Challenge77/blob/master/bg.png)

#功能
`. ` 动态绘制跑步路径    
`. ` 智能判别跑步状态     
`. ` 条形图展示消耗卡路里 

#技术
`. ` MVVM架构(现在暂时使用KVOController来解决V与VM通信，下一个大版本可以会改用ReactiveCocoa)    
`. ` 基于高德地图实现动态绘制轨迹    
`. ` CMMotionManager判断跑步状态    
`. ` 贝塞尔曲线与帧动画实现优雅的记录页面           
`. ` CoreData    
`. ` HealthKit         
`. ` 实现一个view的复用机制解决内存暴涨的问题

#现状
项目处于不断完善当中，计划加入社区功能，后台正在紧密开发中。  
