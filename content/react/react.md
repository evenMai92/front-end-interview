# [返回主页](https://github.com/evenMai92/front-end-interview/blob/master/README.md)

<b><details><summary>1. react-redux connect的参数?</summary></b>
答案：[详解](https://www.cnblogs.com/passkey/p/9910760.html)

公司：今日头条
</details>

<b><details><summary>2. react sholdComponentUpdate 优化原则?</summary></b>
答案：[详解](https://segmentfault.com/a/1190000018549047)

公司：今日头条
</details>

<b><details><summary>3. redux原理与流程?</summary></b>
答案：[详解](https://segmentfault.com/a/1190000004236064)

公司：阿里
</details>

<b><details><summary>4. 高阶组件、render props和react Hooks区别?</summary></b>
答案：[详解](https://cloud.tencent.com/developer/article/1597249)

公司：腾讯云
</details>

<b><details><summary>5. react 新生命周期?</summary></b>
答案：[详解](https://segmentfault.com/a/1190000016617400?utm_source=tag-newest)

公司：腾讯
</details>

<b><details><summary>6. react兄弟组件之间的通讯方式有哪些?</summary></b>
答案：[详解](https://www.jianshu.com/p/fb915d9c99c4)

公司：阿里
</details>

<b><details><summary>7. react怎么捕获错误及原理?</summary></b>
答案：[详解](https://zhuanlan.zhihu.com/p/30944647)
公司：阿里
</details>

<b><details><summary>8. mobx原理?</summary></b>
答案：[详解](https://zhuanlan.zhihu.com/p/25585910)

公司：阿里
</details>

<b><details><summary>9. react 渲染优化做过哪些?</summary></b>
答案：[详解](https://blog.csdn.net/weixin_33858249/article/details/91413260)

公司：阿里
</details>

<b><details><summary>10. 受控组件与非受控组件的区别，使用场景?UI组件是受控组件还是非受控组件?</summary></b>
答案：
>受控组件（Controlled Component）代指那些交由 React 控制并且所有的表单数据统一存放的组件。而非受控组件（Uncontrolled Component）则是由DOM存放表单数据，并非存放在 React 组件中;

[详解](https://zhuanlan.zhihu.com/p/93335058)

公司：阿里
</details>

<b><details><summary>11. React与Vue的区别</summary></b>
答案：
1. 相同点
* 都有组件化开发和Virtual DOM
* 都支持props进行父子组件间数据通信
* 都支持数据驱动视图, 不直接操作真实DOM, 更新状态数据界面就自动更新
* 都支持服务器端渲染
* 都有支持native的方案,React的React Native,Vue的Weex

2. 不同点
* 数据绑定: vue实现了数据的双向绑定,react数据流动是单向的
* 组件写法不一样, React推荐的做法是 JSX , 也就是把HTML和CSS全都写进JavaScript了,即'all in js'; Vue推荐的做法是webpack+vue-loader的单文件组件格式,即html,css,js写在同一个文件
* state对象在react应用中不可变的,需要使用setState方法更新状态;在vue中,state对象不是必须的,数据由data属性在vue对象中管理
* virtual DOM不一样,vue会跟踪每一个组件的依赖关系,不需要重新渲染整个组件树.而对于React而言,每当应用的状态被改变时,全部组件都会重新渲染,所以react中会需要shouldComponentUpdate这个生命周期函数方法来进行控制
* React严格上只针对MVC的view层,Vue则是MVVM模式

[详解](https://yq.aliyun.com/articles/617788?utm_content=m_1000007917)

公司：阿里
</details>

<b><details><summary>12. react有几种创建组件方式,有什么区别?</summary></b>
答案：[详解](https://www.cnblogs.com/wonyun/p/5930333.html)

公司：顺丰科技
</details>

<b><details><summary>13. setState原理?</summary></b>
答案：

[表现](https://zhuanlan.zhihu.com/p/61847529)

[源码解析](https://segmentfault.com/a/1190000015713347)

</details>

<b><details><summary>14. react虚拟dom原理，何时更新？何时销毁？</summary></b>
答案：

公司：阿里
</details>