### 小程序运行机制
+ 小程序启动
  + 热启动：假如用户已经打开过某小程序，然后在一定时间内再次打开该小程序，此时无需重新启动，只需将后台态的小程序切换到前台，这个过程就是热启动；
  + 冷启动：用户首次打开或小程序被微信主动销毁后再次打开的情况，此时小程序需要重新加载启动，即冷启动。

+ 前台/后台状态
+ 小程序销毁
  + 小程序进入后台5分钟
  + 当小程序占用系统资源过高，可能会被系统销毁或被微信客户端主动回收。
+ 小程序更新机制
  
> 案例：拜耳小程序客户反馈气象数据异常