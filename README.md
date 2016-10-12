# 一款模仿知乎日报的微信小程序

## Description
微信小程序火了，虽然懒，也要试一下，刚好在github上看到知乎日报有开源的API供调用，（想要扩展更多的，可以参考[API](https://github.com/izzyleung/ZhihuDailyPurify)
于是就拿知乎日报来练了一下手.
感触如下，想到再补充：
  1. 小程序可配置的东西少之又少，配置个navigatorBar都有点无能为力，大约以后大家做出来的小程序的样式会大同小异吧。
（2）做下来的感觉是，微信web开发者工具没有大chrome浏览器强大，像颜色吸取、自动提示、console.dir()等功能都不能用。

## Blind spots or bugs

（1）html的字符串没有办法正确渲染，我不确定是不是我没找到方法
（2）data-{{object}}在js中，obejct没有办法获取
（3）部分网络图片无法渲染
（4）scroll-view组件的scroll-into-view属性值若为数字类型的字符串，就没有办法准确跳转

## Rendering
![image](https://github.com/susan-github/wechatApp-zhihu/render.gif)
