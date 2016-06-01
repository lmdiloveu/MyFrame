老罗根据公司项目提供的架构，学习过程添加以下笔记

使用 MVP+Retrofit+dagger2+greendao+RxJava
基于Android Studio IDE集成开发工具，使用gradle构建工具，通过module模块抽取重复代码

settings.gradle配置文件可看到4个module
include ':app', ':utils', ':dbcreate', ':network'

module:app编写了一个简单的登录功能示例，演示了mvp架构，RxBinding视图绑定技术，retrofit异步网络框架技术的使用

什么是mvp？

=============================================================
1: RxBinding
视图绑定技术有很多第三方方案，RxBinding使用上最大的优点是视图本身无需声明，直接调用，大大的简化了代码。底层同样使用RX系列技术rxandroid
MVVM 模型 能够让model和view自动绑定，不过这里是单向的，只能从modle绑定到view

1.1  入门学习
http://www.jianshu.com/p/b1df61a4df77
1.2 demo
https://github.com/lmdiloveu/MasteringAndroidDataBinding

=============================================================
2: rxjava rxandroid

2.1 抛物线经典讲解
http://gank.io/post/560e15be2dca930e00da1083#toc_1
2.2 抛物线讲解demo
https://github.com/lmdiloveu/RxJavaSamples
2.3 仓库
https://github.com/ReactiveX/RxJava
https://github.com/ReactiveX/RxAndroid
2.4 wiki
https://github.com/ReactiveX/RxJava/wiki
2.5 javadoc
http://reactivex.io/RxJava/javadoc/

=============================================================

3: retrofit
参考学习资料https://inthecheesefactory.com/blog/retrofit-2.0/en

=============================================================
4: dragger2

=============================================================

5: greendao
