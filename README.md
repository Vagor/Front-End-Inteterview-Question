##HTTP
HTTP是OSI网络模型中处于应用层的一个通信协议
##js跨域问题

- CORS  （修改XHR的header中的url为绝对路径，后台设置Access-Control-Allow-Origin）
- jsonp   （ json with padding）  前后端合作，前台通过script标签向后台get传callback函数名，后台输出一段文字，callback(data)
- document.domain 浏览器不同的iframe之间

##Ajax工作原理

- 先创建一个XHR对象
- 设置方法（if ready status，status＝200  ==> do something）
- xhr.open(post,url,true是否异步)
- xhr.send()
- 异步调用的方式，实现部分动态刷新
http://www.cnblogs.com/mingmingruyuedlut/archive/2011/10/18/2216553.html
##网页性能优化

- 代码
    - 代码合并成一个文件
    - 代码本身的优化
    - 代码压缩工具
    - 正文dom放上面
    - css放上面，用link而不是@import
    - js放下面
- 图片
    - 特殊背景图展开
    - 图片尺寸把握
    - 相较于gif，最好用png8
    - 图片压缩
    - 雪碧图，减少http请求
- 综合技术
    - lazy load
    - cdn代码托管
    - 七牛云图片托管
- 服务器端
    - 特殊文件（logo）缓存时效的设置
    - cache-control
    - 减小cookie体积

##如何调适网页加载问题

- 断点测试
- 查看chrome —— network

##网络安全方面的知识

- sql注入
- DDoS攻击（阿里云有）

http://liudeh-009.iteye.com/blog/1423933
##对web前端的了解
https://segmentfault.com/a/1190000004641227
##说说你最值得谈的项目
新年祝福活动

- 团队协作的重要性
- 技术学习
    - 微信开发的学习
    - php的学习
    - html先写，css后写
- 公司运营以及人才类型的需求

##说说你使用的一个框架

- Angular.js
    - ngbind
    - ngclass
    - angular.moudule
    - .controller
    - angular-ui  ui-view

- Bootstrap
    - 删格系统
    - container
    - row/col-md-12
    - <h1><small></h1>
    - form-group
    - form-control
    - input-group
    - btn-default/btn-primary
    - img-rounded
    - span.glyphicon 图标
    - btn-group>dropdown-menu
    - nav-tabs
- Jquery
    - 选择器
    - addClass()
    - css()
    - attr()
    - on()（统一代替了delegate、bind）$(selector).on(event,childSelector,data,function,map)

    - 移除事件用off（）
    - 绑定一次然后移除用one（）
    - hide/show/toggle
    - fadein/fadeout/toggle
    - slideDown/up/toggle
    - text()、html() 以及 val()
    - append／remove()
    - addClass()／removeClass
    - $ajax/$get/$post

##输入URL之后发生了什么
https://segmentfault.com/a/1190000004220478
##Node.JS的优势与劣势
对于单线程的Node.js，我们可以通过回调的方式，实现异步编程，达到非阻塞的效果。
Node.js优点：
1、采用事件驱动、异步编程，为网络服务而设计。其实Javascript的匿名函数和闭包特性非常适合事件驱动、异步编程。而且JavaScript也简单易学，很多前端设计人员可以很快上手做后端设计。
2、Node.js非阻塞模式的IO处理给Node.js带来在相对低系统资源耗用下的高性能与出众的负载能力，非常适合用作依赖其它IO资源的中间层服务。3、Node.js轻量高效，可以认为是数据密集型分布式部署环境下的实时应用系统的完美解决方案。Node非常适合如下情况：在响应客户端之前，您预计可能有很高的流量，但所需的服务器端逻辑和处理不一定很多。

Node.js缺点：
1、可靠性低
2、单进程，单线程，只支持单核CPU，不能充分的利用多核CPU服务器。一旦这个进程崩掉，那么整个web服务就崩掉了。

https://www.zhihu.com/question/19653241
https://segmentfault.com/a/1190000004223910#articleHeader11
##WebSocket
https://www.zhihu.com/question/20215561
##计算机网络七层模型
http://zhidao.baidu.com/link?url=nw43u8v7OmAjtvOSbQBpMR_kBuovH2pq3nNy2miCOncf6Dc0SjXumFgSIX5YpDuwWmWwvSEePGG-OxAf6jxuXHKijym8e_Wkke5fLe8qfUq
##数据结构
ES6&promise
http://es6.ruanyifeng.com/#docs/promise

proxy/promise/class/module/字符串、正则、数值、数组、对象的拓展/对异步操作的扩展
##设计模式

- 单例模式

##winter boss题
疯狂枚举

- 枚举document
