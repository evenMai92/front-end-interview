# [返回主页](https://github.com/evenMai92/front-end-interview/blob/master/README.md)

<b><details><summary>1. http是什么，请求报文有哪些?</summary></b>
答案：

1. http(Hypertext transfer protocol)超文本传输协议，通过浏览器和服务器进行数据交互，进行超文本（文本、图片、视频等）传输的规定。也就是说，http协议规定了超文本传输所要遵守的规则；HTTP协议的特点：
* HTTP协议是无状态的
* HTTP协议是无连接的
* HTTP是媒体独立的

2.请求报文包含请求行、请求头和请求体

[详解](https://www.cnblogs.com/lmh001/p/9928517.html)

公司：金蝶科技、腾讯
</details>

<b><details><summary>2. http缓存?</summary></b>
答案：
[详解](https://www.jianshu.com/p/54cc04190252)

公司：金蝶科技、腾讯、阿里
</details>

<b><details><summary>3. http1.0、http1.1和http2的区别?</summary></b>
答案：
[详解](https://www.cnblogs.com/heluan/p/8620312.html)

公司：金蝶科技
</details>

<b><details><summary>4. web安全漏洞及防御?</summary></b>
答案：
[详解](https://www.cnblogs.com/fundebug/p/details-about-6-web-security.html)

公司：腾讯
</details>

<b><details><summary>5. 使用token的话，过期之后怎么办，怎么优化体验?</summary></b>
答案：
[详解1](https://zhuanlan.zhihu.com/p/54598246)
[详解2](https://segmentfault.com/a/1190000016946316)

公司：腾讯，顺丰科技
</details>

<b><details><summary>6. babel转es6为es5的过程?</summary></b>
答案：
>ES6代码输入 ==》 babylon进行解析 ==》 得到AST
==》 plugin用babel-traverse对AST树进行遍历转译 ==》 得到新的AST树
==》 用babel-generator通过AST树生成ES5代码

[详解](https://www.jianshu.com/p/e9b94b2d52e2)

公司：顺丰科技
</details>

<b><details><summary>7. webpack热更新原理以及webpack优化打包速度和优化性能?</summary></b>
答案：
[详解](https://www.cnblogs.com/gaoht/p/11310365.html)

公司：顺丰科技、阿里
</details>

<b><details><summary>8. webpack相关问题?</summary></b>
问题：
- webpack
  - 单独将代码库(如antd)打扮成一个js文件？
    - 打包时，会将antd打扮成几个文件?
  - 如何按需打包代码(只打包已改动的和相关的代码包)
  - 多页面应用打包?
    - 多页面应用的依赖管理
  - ssr和spa的混合打包问题
  - 分模块打包

公司：腾讯、抖音
</details>

<b><details><summary>9. http状态码301与307的区别?</summary></b>
问题：[详解](https://www.wanghuiblog.com/post/301-302-307-redirection/)

公司：腾讯音乐
</details>

<b><details><summary>10. 从输入URL到页面加载发生了什么?</summary></b>
答案：[详解](https://segmentfault.com/a/1190000006879700)

公司：顺丰科技
</details>

<b><details><summary>11. http三次握手与四次挥手</summary></b>
答案：[详解](https://baijiahao.baidu.com/s?id=1654225744653405133&wfr=spider&for=pc)

公司：顺丰科技
</details>

<b><details><summary>12. web性能优化</summary></b>
答案：

[重排与重绘](https://mp.weixin.qq.com/s/BboZ5wxNaXXjpAFignOYdw)

[加载技术](https://www.jianshu.com/p/ba9759384ecf)

[白屏优化](https://segmentfault.com/a/1190000020383064?utm_source=tag-newest)

[更多](https://zhuanlan.zhihu.com/p/39878259)

公司：顺丰科技
</details>

<b><details><summary>13. token被攻击者已经拿到了，用来发请求，怎么避免这种攻击</summary></b>
答案：

* 在存储的时候把 token 进行对称加密存储，用时解开。
* 将请求 URL、时间戳、token 三者进行合并加盐签名，服务端校验有效性。
* HTTPS 对 URL 进行判断

公司：腾讯
</details>

<b><details><summary>14. https加密方式</summary></b>
答案：[详解](https://segmentfault.com/a/1190000019687184)

公司：腾讯，字节
</details>

<b><details><summary>15. http keep-alive什么时候关闭？</summary></b>
答案：[详解](https://blog.51cto.com/yangsj/1788301)

公司：腾讯微视
</details>

<b><details><summary>16. 怎么判断页面被劫持以及防御？</summary></b>
答案：[详解](https://zhuanlan.zhihu.com/p/32059056)

公司：腾讯微视
</details>

<b><details><summary>17. http get可以传请求体吗？</summary></b>
答案：[详解](https://www.jianshu.com/p/c025273d78db)

公司：腾讯微视
</details>

<b><details><summary>18. 输入url到页面显示的过程以及影响性能的点？</summary></b>
答案：[详解](https://juejin.cn/post/6895616443334066183)

公司：腾讯微保
</details>

<b><details><summary>19. 白屏问题的定位及解决方案？</summary></b>
答案：

公司：腾讯微保
</details>

<b><details><summary>20. HTTP2新增特性及头部压缩怎么实现？</summary></b>
答案：[详解头部压缩](https://www.cnblogs.com/cangqinglang/p/12629087.html)

公司：联想
</details>

<b><details><summary>21. websocket握手过程？</summary></b>
答案：[详解](https://blog.csdn.net/yournevermore/article/details/103067079)

公司：腾讯
</details>

<b><details><summary>22. 小程序的架构及为什么不推荐多次触发setData？</summary></b>
答案：
[架构讨论](https://www.zhihu.com/question/446103629/answer/1801809960)
[架构设计](https://www.cnblogs.com/wonyun/p/11168698.html)
[setData问题](https://developers.weixin.qq.com/miniprogram/dev/framework/performance/tips.html)

公司：腾讯
</details>

<b><details><summary>23. dns是基于哪个协议？</summary></b>
答案：[详解](https://www.cnblogs.com/lsgxeva/p/8321192.html)

公司：腾讯
</details>

<b><details><summary>24. 怎么避免index.html缓存？</summary></b>
答案：[详解](https://www.jianshu.com/p/eaad6e4757e5)

公司：顺丰
</details>

<b><details><summary>25. webpack怎么处理循环引用的模块？</summary></b>
答案：[详解](https://www.yuque.com/u1113084/dsregg/nolwsb)

公司：元戎启行
</details>

<b><details><summary>26. tcp怎么处理错包和乱包问题？</summary></b>
答案：[详解](http://cache.baiducontent.com/c?m=HZ25Jld2I8KK5Acz8MvBclTef4XhlqFYo6EkG3J1xou1Fcw6wAJEp_y6YmQuq8LDaaMoIc3a-9f6qKQJskjg6yU98IX0mcyvb0CiSCNsldJRdMmIdrXf54MrP9Jy3xYbPo_nmFtX7k-J3LWkpEEysWXI4I6d3qGpnn-C2Pb_h37R4GYt4JsbASUesCuPTBOwk72FD5SGEtDm9U4klvHZ0_&p=c0759a44d58717f60da2c7710f48&newp=882a94469c9f02fc57ef8868110092695d0fc20e3bd3db01298ffe0cc4241a1a1a3aecbf2c251604d8cf7b6404a84e5ceef033763d0034f1f689df08d2ecce7e65d464&s=cfcd208495d565ef&user=baidu&fm=sc&query=tcp%D4%F5%C3%B4%BB%E1%D3%F6%B5%BD%B4%ED%B0%FC%C2%F0&qid=b6224cbe002d2443&p1=10)

公司：字节
</details>

<b><details><summary>27. tcp怎么保证稳定可靠？</summary></b>
答案：[详解](https://blog.csdn.net/mulinsen77/article/details/88924907)

公司：字节
</details>

<b><details><summary>28. protobuf为什么能实现性能提升？</summary></b>
答案：[详解](hhttps://blog.csdn.net/qq_35448165/article/details/99473027)

公司：字节
</details>