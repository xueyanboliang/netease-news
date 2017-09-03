# 网易新闻首页
> 这是一个利用Vux移动端组件库搭建的一个App简易项目，麻雀虽小五脏俱全，虽然是通过组件搭建起来的但是却能够让刚刚接触Vue的“菜鸟”们大概了解Vue2.0的全貌，特别是Vuex的使用，由于网易的接口比较难获取，所以只做了一个首页，其他页面的实现原理同理，有兴趣的童鞋可以自己去实现以下。

## 技术栈
+ Vue2.0: 采用最新Vue2的语法 
+ Vue Jsonp：发起http请求
+ Vue Router: 管理单页面应用路由
+ webpack: 自动化构建工具，主要配置vue-cli脚手架提供
+ less: css预处理语言
+ Vuex: 管理公共组件状态量
+ ES6:ES6最新语法

## 功能
- [x] 吸顶导航（带左右滑动，回弹功能）
- [x] 无缝轮播图
- [x] 跑马灯
- [x] 页面上滑，下滑
- [x] 上拉刷新，下拉加载

## 项目心得
> 由于Vue2.0中新添加了Vuex,方便我们更好的去管理组件的状态和数据，这在大项目的构建中尤其重要，这也是该个项目中最值得注意的地方。

## 安装步骤
- clone项目到本地，然后安装项目依赖 
<br/>*npm install*
- 启动服务
<br/>*npm run dev*
<br/>项目即可运行

## 项目截图
![neteasenews_1](https://github.com/xueyanboliang/my-pics/blob/master/netease_news/neteasenews.gif?raw=true)
![neteasenews_2](https://github.com/xueyanboliang/my-pics/blob/master/netease_news/neteasenews_1.png?raw=true)
