# Work-record
从今天开始，想记录一下每天的工作内容，因为大部分时间都在工作，加班，所以工作其实是我人生的重要组成部分，把每天做的事情记录下来，以后自己老了，回头翻看一下也挺有意义的吧。
### 2017-10-30
* 设计天天抢购APP页面。
### 2017-10-31
* 设计天天抢购APP页面。
### 2017-11-1
* 谁都有脾气，但要学会收敛，在沉默中观察，在冷静中思考，别让冲动的魔鬼，酿成无可挽回的错；谁都有梦想，但要立足现实，在拼搏中靠近，在忍耐中坚持，别挂在嘴边，常立志者无志；谁都有底线，但要懂得把握，大事重原则，小事有分寸，不讲情面难得别人支持，过分虚伪亦让人避而远之。忍一时风平浪静，退一步海阔天空。
### 2017-11-2
* 1、今天看到一篇文章，作者探讨了从 Programmer 进阶到 Developer 的方法，总结来说就是积累，那么怎么积累？他行动的基本法则是：做出好的东西先要知道好的东西长啥样。一方面，多读经典的书，仔细读高质量的文章，注意这里面读远比收藏重要，上哪里去找经典的书和高质量的文章？这需要建立自己的信息筛选机制；另外一方面，遇到问题要学会去搜索，找更多的解决方案，然后比较，融会贯通。<br>
* 2、js调用栈的工作机制：调用函数的时候，会被推到调用栈的顶部，而执行完毕之后，就会从调用栈移除。
```javascript
function c() {
    console.log('c');
}

function b() {
    console.log('b');
    c();
}

function a() {
    console.log('a');
    b();
}

a();
```
这段代码运行时，首先 a 会被加入到调用栈的顶部，然后，因为 a 内部调用了 b，紧接着 b 被加入到调用栈的顶部，当 b 内部调用 c 的时候也是类似的。在调用 c的时候，我们的调用栈从下往上会是这样的顺序：a -> b -> c。在 c 执行完毕之后，c 被从调用栈中移除，控制流回到 b 上，调用栈会变成：a -> b，然后 b 执行完之后，调用栈会变成：a，当 a 执行完，也会被从调用栈移除。
### 2017-11-3
#### Web 前端技术学习路线图
 
上面说了这么多，到底如何一步步掌握这些技术呢？ 下面推荐一个学习路线图，希望对初学者有帮助。
 
Javascript 语言：全栈开发中，用的编程语言就是 javascript
 
HTML5 标签和 DOM：这是前端最核心技术，为之后学习各种开发框架，打下坚实基础。
 
CSS3：学习通过 css 开发网页和各种可视 UI 组件。
 
SASS：利用 sass 语言，开发复杂的页面 css
 
Node.js：掌握Node.js 核心 API ，具备后端开发能力。
 
Express 5.x 框架：掌握 Express 框架，从而具备快速开发后端程序的能力。
 
socket.io 库：让前后端通过 websocket协议通信，是web 开发游戏、聊天等程序必备技术。
 
Mongoose 框架：可以让程序具备文档数据储存能力
 
Git 命令与 github：可以对项目进行版本管理，从而能团队开发项目。
 
Gulp 构建工具实战：通过 gulp 工具，灵活对项目进行构建。
 
Webpack：可以用和 Node.js 后端模块化方式，开发前端程序，从而能开发大型系统。
 
Jasmine & Karma：可以利用 Jasmine & Karma 轻松实现，多种浏览器同时进行单元测试，而不必切换界面。
 
前端相关框架：JQuery ／ Bootstrap ／ Vue.js ／React ／ Angular通过框架帮我我们快速开发程序
 
移动端与桌面程序开发工具：phonegap ／ react-native / electron / 微信小程序开发，这套工具，基本上只是打包工具，和提供了一些特定平台 API ，开发还是使用之前的 Web 技术。
