---
layout: post
title: "All for  the  interview"
date:   2018-1-3 16:46:01 +0800
categories: Android
tag: 面试
---

* content
{:toc}

1.第三方API
-----------
豆瓣最新热映电影：https://api.douban.com/v2/movie/in_theaters


2.maxAge与maxStale的区别：
-----------------------
maxAge:没有超出maxAge,不管怎么样都是返回缓存数据，超过了maxAge,发起新的请求获取数据更新，请求失败返回缓存数据。

maxStale:没有超过maxStale，不管怎么样都返回缓存数据，超过了maxStale,发起请求获取更新数据，请求失败返回失败

3.现在大部分App底部都有一个菜单，实现底部tab功能也有好多办法：

- TabHost+Fragment

- RadioGroup+Fragment

- FragmentTabHost+Fragment

- 5.0以后有个新控件，BottomNavigator


4.防止启动白屏增加配置：
--------------------
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
         ......
 	     <item name="android:windowIsTranslucent">true</item>
   		 <item name="android:windowNoTitle">true</item>
	</style>

5.面试常问问题：
-----------
###   
  0. GIF图片如何将解析
  1. 基本算法，其实基本没遇到和难的算法，都是给定一个实际场景然后写个小算法，比如叫把 String 的 IP 地址转成 int 值，IP 是 192.168.0.1 这种，对应 int 值是 19216801。
  2. Java 中常用类的源码，如 常用的数据结构（HashMap问的比较多）、String、StringBuilder
等等，可以看看 《Thinking in Java 》
  3. Java 虚拟机、Art、Dalvik 他们的区别。
  4. 性能优化，这是个很大的点，但是基本是必问的。
  5. Java GC 原理、GC Root 的概念、Java 引用类型。
  6. Android 的基础知识，强烈建议理解性的阅读《Android 艺术探讨》，很多问题的答案都可以在这本书上找到，像 View 绘制流程、事件分发流程、Handler 机制、IntentService、HandlerThread 这些可以边看边跟源码边做笔记。
  7. 多线程中，线程安全。
  8. 线程池，需要理解里面各种参数的含义，适用场景。
  9. 进程间通信、线程间通信。
  10. JSBridge 相关的东西。
  11. 自己在项目中用到的东西，既然写在简历上了就要知道它的原理，越清楚越好。 
###



 6.面试总结：
------------

  #1. 我个人认为简历不要乱投，只投递喜欢的公司和职位，不然只会浪费时间。

  #2. 不管面对什么样的人，千万不要怯场，不然根本没法表现出自己水平，既然让你来面试了，说明简历还是有过人之处。

  #3. 把基础打牢固，平时开发中多总结，多想想为什么。

  #4. 不要放弃每一次面试机会（因为你投递肯定是因为喜欢），我中间有好几次都不想去，但是理智告诉我必须求不然会后悔。

  #5. 事先了解职位要求。

  #6. 面试过程中语速慢些，说话要有调理，开始的对白可以预先准备好，因为一开始基本都是自我介绍，你可以介绍完自己，又介绍自己公司业务，随带介绍自己做的东西，把你觉得面试官可能感兴趣的放后一点点，一般面试官都会问问的，然后这可以顺带再继续说说。

  #7. 总结每次面试，这次问到不会，就不能在下次也不会了，如果面试失败，要分析失败的原因。

  #8. 遇到不会的就说不会，但是不能就这么完了，一定要思考，分析问题的能力感觉面试官是非常看重的，你思考过程中可以把你思路说出来，能说多少就多少，千万不要不好意思。其实科学研究也是猜测加实验证明的过程。这点非常重要的！

  #9. 对自己做过的东西一定要非常熟悉，了解实现的原理，比如做过热修复，你肯定需要知道热修复原理，做过大图浏览，肯定要知道内存问题、分块加载、矩阵变换。

  #10. 面试前要对期望薪资做个评估，高了其实你面试ok的话 HR 可以给你砍下，低了吃亏的不只是你自己，HR 也替你着急，因为低了的话就算给了你 offer 很可能你不会去的，这样他们就白干一场。合理的要工资既是对自己的负责也是对招聘公司的尊重。 
