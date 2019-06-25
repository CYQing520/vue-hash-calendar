#####按照惯例，先上效果图
![效果图](https://upload-images.jianshu.io/upload_images/7412714-9cd4bb7083337299.gif?imageMogr2/auto-orient/strip)

###vue-hash-calendar

* 基于 vue 2.X 开发的日历组件
* 支持手势滑动操作
* 原生 js 开发，没引入第三方库

### Demo

![demo_qrcode.png](https://upload-images.jianshu.io/upload_images/7412714-48c92886b2127daf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
或者请用浏览器的手机模式查看：[https://www.hxkj.vip/demo/calendar/](https://www.hxkj.vip/demo/calendar/)

* 🎉 觉得好用可以给一个 star 哦~~ 🎉

#####github地址：[https://github.com/TangSY/vue-hash-calendar](https://github.com/TangSY/vue-hash-calendar) 

####API

| 属性          | 说明                                                                                                   |  默认  | 是否必传 |
| :------------ | :----------------------------------------------------------------------------------------------------- | :----: | :------: |
| model      | 日历组件以哪种形式展示。inline：内联的方式。dialog：弹窗的方式                                                            |   dialog   |    否    |
| defaultDatetime| 指定默认时间。数据类型为Date                                                      |   当前时间   |    否    |
| format       | 确认日期时，回调事件返回的日期格式。如“YY/MM/DD hh:mm” 、“YY年MM月第DD天，当前时间hh时mm分”                                      |  YY/MM/DD hh:mm   |    否    |
| weekStart      | 以星期几作为日历每一周的起始星期。可选['sunday', 'monday', 'tuesday', 'wednesday', 'thursday', 'friday', 'saturday']            | sunday |    否    |
| pickerType  | 选择器类型 datetime：日期+时间   date：日期   time：时间                                                               | datetime |    否    |
| showTodayButton    | 是否显示返回今日按钮                                                          |   true    |    否    |
| confirm | 确认选择的回调事件。当model为inline的时候没有该事件                                                            |  ---  |    否    |

###Other

* 如果有其他问题， 或者功能上不兼容的。可以邮件沟通 t@tsy6.com，或者github提交issue。



###Project setup
```
npm install
```

####Compiles and hot-reloads for development
```
npm run serve
```

####Compiles and minifies for production
```
npm run build
```