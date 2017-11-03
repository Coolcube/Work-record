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
