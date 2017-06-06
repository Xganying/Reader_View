## Reader

一个Web APP阅读器

## 技术

 HTML5 + Vue.js + zepto + Koa

## 项目进度

### 第一天

htmL5 + CSS实现阅读器的前端页面基本结构静态布局，主要：顶部栏 + 主体内容 + 底部栏 + 底部栏控制面板

### 第二天

1.简单学习和使用zepto.js

  zepto是一款比较适合移动端开发的轻量级框架，主要的使用原因：

（1） 无缝接入和改造现有的项目。 （2）更好的代码执行效率。   （3）比较轻量化，没有提供复杂的模式。

（轻量 + 快速 + 高效）

2.页面前端交互代码开发（部分）: 

    点击阅读内容中部，显示/隐藏头部栏和底部栏  function EventHandler(){}

### 第三天

    页面前端交互代码开发：

    实现和阅读器相关的数据交互的方法: function ReaderModel(){}
    
### 第四天
    
    数据层与UI渲染连调
    function ReaderBaseFrame(contanier){}
    
    上下翻页功能事件绑定及优化
    var prevChapter = function (UIcallback){}
    var nextChapter = function (UIcallback) {}
    服务端交互代码细节优化


