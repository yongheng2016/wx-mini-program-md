### 小程序与普通网页开发的区别
+ ​网页开发渲染线程和脚本线程是互斥的
+ 而在小程序中，二者是分开的，分别运行在不同的线程中（因而缺少相关的DOM API和BOM API）
  + 渲染层和逻辑层 ![](https://res.wx.qq.com/wxdoc/dist/assets/img/4-1.ad156d1c.png)