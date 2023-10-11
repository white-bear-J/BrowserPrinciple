# 浏览器工作原理与实战

[原文链接](https://blog.poetries.top/browser-working-principle/)

## 宏观视角上的浏览器

- [Chrome架构：仅仅打开1个页面，为什么有4个进程](./第一章：宏观视角上的浏览器/1.Chrome架构：仅仅打开1个页面，为什么有4个进程/index.md)
- [TCP协议：如何保证页面文件能被完整送达浏览器](./第一章：宏观视角上的浏览器/2.TCP协议：如何保证页面文件能被完整送达浏览器/index.md)
- [HTTP请求流程：为什么很多站点第二次打开速度会很快](./第一章：宏观视角上的浏览器/3.HTTP请求流程：为什么很多站点第二次打开速度会很快/index.md)
- [导航流程：从输入URL到页面展示这中间发生了什么](./第一章：宏观视角上的浏览器/4.导航流程：从输入URL到页面展示这中间发生了什么/index.md)
- [渲染流程（上）：HTML、CSS和JavaScript是如何变成页面的](./第一章：宏观视角上的浏览器/5.渲染流程（上）：HTML、CSS和JavaScript是如何变成页面的/index.md)
- [渲染流程（下）：HTML、CSS和JavaScript是如何变成页面的](./第一章：宏观视角上的浏览器/6.渲染流程（下）：HTML、CSS和JavaScript是如何变成页面的/index.md)

## 浏览器中的JavaScript执行机制

- [变量提升：JavaScript代码是按顺序执行的吗](./第二章：浏览器中的JavaScript执行机制/7.变量提升：JavaScript代码是按顺序执行的吗/index.md)
- [调用栈：为什么JavaScript代码会出现栈溢出](./第二章：浏览器中的JavaScript执行机制/8.调用栈：为什么JavaScript代码会出现栈溢出/index.md)
- [块级作用域：var缺陷以及为什么要引入let和const](./第二章：浏览器中的JavaScript执行机制/9.块级作用域：var缺陷以及为什么要引入let和const/index.md)
- [作用域链和闭包：代码中出现相同的变量，JavaScript引擎如何选择](./第二章：浏览器中的JavaScript执行机制/10.作用域链和闭包：代码中出现相同的变量，JavaScript引擎如何选择/index.md)
- [this：从JavaScript执行上下文视角讲this](./第二章：浏览器中的JavaScript执行机制/11.this：从JavaScript执行上下文视角讲this/index.md)

## V8工作原理

- [栈空间和堆空间：数据是如何存储的](./第三章：V8工作原理/12.栈空间和堆空间：数据是如何存储的/index.md)
- [垃圾回收：垃圾数据如何自动回收](./第三章：V8工作原理/13.垃圾回收：垃圾数据如何自动回收/index.md)
- [编译器和解析器：V8如何执行一段JavaScript代码的](./第三章：V8工作原理/14.编译器和解析器：V8如何执行一段JavaScript代码的/index.md)

## 浏览器中的页面循环系统

- [消息队列和事件循环：页面是怎么活起来的](./第四章：浏览器中的页面循环系统/15.消息队列和事件循环：页面是怎么活起来的/index.md)
- [Webapi：setTimeout是怎么实现的](./第四章：浏览器中的页面循环系统/16.Webapi：setTimeout是怎么实现的/index.md)
- [Webapi：XMLHttpRequest是怎么实现的](./第四章：浏览器中的页面循环系统/17.Webapi：XMLHttpRequest是怎么实现的/index.md)
- [宏任务和微任务：不是所有的任务都是一个待遇](./第四章：浏览器中的页面循环系统/18.宏任务和微任务：不是所有的任务都是一个待遇/index.md)
- [使用Promise告别回调函数](./第四章：浏览器中的页面循环系统/19.使用Promise告别回调函数/index.md)
- [async-await使用同步方式写异步代码](./第四章：浏览器中的页面循环系统/20.async-await使用同步方式写异步代码/index.md)

## 浏览器中的页面

- [页面性能分析：利用chrome做web性能分析](./第五章：浏览器中的页面/21.页面性能分析：利用chrome做web性能分析/index.md)
- [DOM树：JavaScript是如何影响DOM树构建的](./第五章：浏览器中的页面/22.DOM树：JavaScript是如何影响DOM树构建的/index.md)
- [渲染流水线：CSS如何影响首次加载时的白屏时间](./第五章：浏览器中的页面/23.渲染流水线：CSS如何影响首次加载时的白屏时间/index.md)
- [分层和合成机制：为什么CSS动画比JavaScript高效](./第五章：浏览器中的页面/24.分层和合成机制：为什么CSS动画比JavaScript高效/index.md)
- [页面性能：如何系统优化页面](./第五章：浏览器中的页面/25.页面性能：如何系统优化页面/index.md)
- [虚拟DOM：虚拟DOM和实际DOM有何不同](./第五章：浏览器中的页面/26.虚拟DOM：虚拟DOM和实际DOM有何不同/index.md)
- [PWA：解决了web应用哪些问题](./第五章：浏览器中的页面/27.PWA：解决了web应用哪些问题/index.md)
- [webComponent：像搭积木一样构建web应用](./第五章：浏览器中的页面/28.webComponent：像搭积木一样构建web应用/index.md)

## 浏览器中的网络

- [HTTP1：HTTP性能优化](./第六章：浏览器中的网络/29.HTTP1：HTTP性能优化/index.md)
- [HTTP2：如何提升网络速度](./第六章：浏览器中的网络/30.HTTP2：如何提升网络速度/index.md)
- [HTTP3：甩掉TCP、TCL包袱，构建高效网络](./第六章：浏览器中的网络/31.HTTP3：甩掉TCP、TCL包袱，构建高效网络/index.md)
- [同源策略：为什么XMLHttpRequest不能跨域请求资源](./第六章：浏览器中的网络/32.同源策略：为什么XMLHttpRequest不能跨域请求资源/index.md)
- [跨站脚本攻击XSS：为什么cookie中有httpOnly属性](./第六章：浏览器中的网络/33.跨站脚本攻击XSS：为什么cookie中有httpOnly属性/index.md)
- [CSRF攻击：陌生链接不要随便点](./第六章：浏览器中的网络/34.CSRF攻击：陌生链接不要随便点/index.md)
- [沙盒：页面和系统之间的隔离墙](./第六章：浏览器中的网络/35.沙盒：页面和系统之间的隔离墙/index.md)
- [HTTPS：让数据传输更安全](./第六章：浏览器中的网络/加餐：HTTPS：让数据传输更安全/index.md)
