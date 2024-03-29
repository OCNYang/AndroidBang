### TODO
要想提升，你会发现该学的东西一样也少不了在哪里等着你...

#### Groovy & Gradle
[Groovy 脚本基础全攻略](https://blog.csdn.net/yanbober/article/details/49047515)  
[Groovy 教程](https://www.w3cschool.cn/groovy/)  
[Gradle 教程](https://www.w3cschool.cn/gradle/)  
[Gradle 教程](https://www.yiibai.com/gradle/)  
[Gradle 用户指南官方文档中文版](https://wiki.jikexueyuan.com/project/GradleUserGuide-Wiki/tutorials/README.html)  

[Gradle 爬坑指南 -- 导论](https://juejin.cn/post/6882178101191639053)  


#### Python




### Kotlin 相关

* 书籍：《Kotlin 核心编程》
* 协程：[超长文，带你全面了解 Kotlin 的协程](https://blog.csdn.net/c10wtiybq1ye3/article/details/103640848)  
* Flow：[谷歌推荐：在 MVVM 架构中使用 Kotlin Flow](https://www.jianshu.com/p/0696c7252b50)  
* Flow：[Kotlin Coroutines Flow 系列 (一) Flow 基本使用](https://juejin.cn/post/6844904057530908679)  
* Hilt：[Jetpack 新成员，一篇文章带你玩转 Hilt 和依赖注入](https://zhuanlan.zhihu.com/p/335631378)  


### JetPack 相关

* 书籍：《Android JetPack 应用指南》  
* [官方 JetPack 文档](https://developer.android.google.cn/topic/libraries/architecture)  

### 组件化

* [Android 组件化最佳实践](https://juejin.cn/post/6844903649102004231)  

> 个人认为，组件化现在被过度使用了，体量不大的项目、成员不多的开发组，其实没必要一定要组件化的。相对面试来说的，如果不是大厂、大项目，去考察你的组件化真的就是为了面试而面试了。  
> 针对功能模块解耦，感觉仅仅模块化就足够了。  
> 不过人家面试人家说了算，该学还是学学，也没多少东西。

**组件化实践**  
[方案：JIMU](https://github.com/mqzhangw/JIMU)  
[Demo: DDComponentForAndroid](https://github.com/luojilab/DDComponentForAndroid)  
[1. Android 彻底组件化方案实践](https://blog.csdn.net/yan8024/article/details/76408161)  
[2. Android 彻底组件化 demo 发布](https://www.jianshu.com/p/59822a7b2fad/)  
[3. Android 彻底组件化 — 代码和资源隔离](https://www.jianshu.com/p/c7459b59dcd5)  
[4. Android 彻底组件化 —UI 跳转升级改造](https://blog.csdn.net/weixin_34266504/article/details/87955995)  
[5. Android 彻底组件化 — 如何使用 Arouter](https://blog.csdn.net/h176nhx7/article/details/79203515)  


### 优化

* [Android 应用开发性能优化完全分析](https://blog.csdn.net/yanbober/article/details/48394201)  
* [Android WebView 优化汇总](https://www.jianshu.com/p/6179d51281da)  
* [Android 网络优化，使用 HTTPDNS 优化 DNS](https://www.cnblogs.com/plokmju/p/okhttp_httpdns.html)  


### 音视频

* [推荐几个堪称教科书级别的 Android 音视频入门项目](https://segmentfault.com/a/1190000022561224)  
> 对应下面 3 个项目  
> [GPUImage](https://github.com/cats-oss/android-gpuimage)  
> [AudioVideoRecordingSample](https://github.com/saki4510t/AudioVideoRecordingSample)  
> [Grafika](https://github.com/google/grafika)

* [Android 贴心的音视频学习指南来咯！](https://www.ershicimi.com/p/006c89b87988f65950eeb54f2308273e)  
* [Android 音视频架构 - 学习路线规划](https://blog.csdn.net/coding_man_xie/article/details/104829455)  
* [Android 音视频技术](https://www.cnblogs.com/renhui/category/1011048.html)  


### 动画

* [Android 所有动画系列详尽教程](https://github.com/OCNYang/Android-Animation-Set)  

### 知识点概念

* [2020 面试题](https://xiaozhuanlan.com/topic/7548023169)
* [史上最全的 Android 面试题集锦](https://juejin.cn/post/6844903891625050119)

* [Android 各版本适配](https://www.jianshu.com/p/a3baa6babe00)  
* [Android 进程间通讯](https://www.cnblogs.com/sixrain/p/11149780.html)  
* [事件分发机制](https://www.cnblogs.com/chengxuyinli/p/9979826.html)  
* [Socket 使用攻略](https://www.jianshu.com/p/089fb79e308b)  

### 问题点

* LocalBroadcast 跨进程通知（同一个应用，不同的进程）
* 一个 Activity 多个 Handler 时，Message 消息是否会混乱？
* LiveData 数据倒灌原因，解决方案

### 设计模式  

* [单例模式 工厂模式](https://zhuanlan.zhihu.com/p/93770973)   
* [Android 常用设计模式](https://blog.csdn.net/chaoshenzhaoxichao/article/details/79839359)  
* [Android 系统中涉及的设计模式](https://blog.csdn.net/varistor/article/details/91446009?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control&dist_request_id=1328593.24992.16148409745428659&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control)  


### 项目问题

#### 崩溃率  
* 接口返回的数据格式不可控造成的问题
* 内存溢出造成的问题，低端、内存较小的机型容易崩溃
* 页面问题，RecyclerView 为了不解决复用问题，禁用了复用，导致线上列表数据很多时，页面崩溃（组员）
* 机型兼容问题，vivo 某些低端机型 不兼容 svg ，当加载不规范的 svg 时会有问题。使用云真机去做测试。

#### 难点
* handler 的消息队列里的数据处理正常是很快的，但是如果存在耗时的处理，会导致不能及时处理队列中的消息，这个时候可以把消息队列中的数据都打印出来。在你想开始打印的地方增加 `Looper.getMainLooper().setMessageLogging(new LogPrinter(4, "xuwenping"));`，这样，log 里就会出现 `I/xuwenping: <<<<< Finished to Handler (android.view.ViewRootImpl$ViewRootHandler) {672b748} null` 的类似 log
* LiveData 数据倒灌问题，一个列表，点击 A 看详情，再点击 B 看详情，解决 LiveData 置空 | 使用 id 标识数据（返回的数据格式内的 id 和 请求 id 比对）。
* kotlin 和 Java 兼容问题，最常见的就是 空 安全的问题。
* vector 问题，动态设置颜色渲染，会使所有使用的地方变色。解决：复制一份 svg 图标。
* textView 的 inputType 问题。
* 过期跳转登录问题，清空栈。（clear task | new task）
* application 缓存数据的问题，退出后台，当系统内存不足的时候会回收app，再恢复时全新app并启动退出时的Activity页面。
* 目前未解决的问题：RecyclerView 内使用 fragment。


### 框架
* [EventBus 原理](https://www.cnblogs.com/huansky/p/10926138.html) 关键字：反射、注册时保存类名，并反射保存注解监听方法、线程切换，主线程用Handle，其他用线程池  
* [ButterKnife 原理](https://www.jianshu.com/p/99e080606de3) 关键字：apt、编译生成对应文件，bind()时对应  
* [Glide 原理](https://blog.csdn.net/gzsuperwin/article/details/109075916) 关键字：空界面fragment监听生命周期、三级缓存  
* [okhttp 原理](https://www.jianshu.com/p/d7eced552553) 关键字：责任链、线程池、缓存、gzip、不是采用httpurlConnention，而是Socket  
* [ARouter 原理](https://www.cnblogs.com/ldq2016/p/10504652.html) 关键字：apt，注解内字符串 Map 对应 class 类名  
* [Retrofit 原理](https://www.cnblogs.com/ijkzen/p/14455642.html) 关键字：动态代理  
* [RxJava 2.0 使用](https://www.jianshu.com/u/c50b715ccaeb) 关键字：函数响应式编程；代替品：EventBus、Handle、Kotlin 协程、Kotlin Flow 

### 面试历程
* 同步屏障
