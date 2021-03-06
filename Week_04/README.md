# 第4周作业


## 作业内容

Week04 作业题目（周四）：

一个简单的代码参考：[strong_end] https://github.com/kimmking/JavaCourseCodes/tree/main/03concurrency/0301/src/main/java/java0/conc0303/Homework03.java

1.（选做）把示例代码，运行一遍，思考课上相关的问题。也可以做一些比较。

2.（必做）思考有多少种方式，在 main 函数启动一个新线程，运行一个方法，拿到这个方法的返回值后，退出主线程？
写出你的方法，越多越好，提交到 Github。

Week04 作业题目（周六）：

1.（选做）列举常用的并发操作 API 和工具类，简单分析其使用场景和优缺点。

2.（选做）请思考：什么是并发？什么是高并发？实现高并发高可用系统需要考虑哪些因素，对于这些你是怎么理解的？

3.（选做）请思考：还有哪些跟并发类似 / 有关的场景和问题，有哪些可以借鉴的解决办法。
4.（必做）把多线程和并发相关知识带你梳理一遍，画一个脑图，截图上传到 Github 上。
可选工具：xmind，百度脑图，wps，MindManage 或其他。

作业提交规范：
1. 作业不要打包 ；
2. 同学们写在 md 文件里，而不要发 Word, Excel , PDF 等 ；
3. 代码类作业需提交完整 Java 代码，不能是片段；
4. 作业按课时分目录，仅上传作业相关，笔记分开记录；
5. 画图类作业提交可直接打开的图片或 md，手画的图手机拍照上传后太大，难以查看，推荐画图（推荐 PPT、Keynote）；
6. 提交记录最好要标明明确的含义（比如第几题作业）。

以上作业，要求 2 道必做题目提交到 Github 上面，Week04 作业提交地址：
https://github.com/JAVA-000/JAVA-000/issues/129


## 操作步骤

1. 打开 Spring 官网: https://spring.io/
2. 找到 Projects --> Spring Initializr:  https://start.spring.io/
3. 填写项目信息, 生成 maven 项目; 下载并解压。
4. Idea或者Eclipse从已有的Source导入Maven项目。
5. 增加自己的包名, 以做标识。
6. 把老师的 `Homework03.java` 代码拷贝到自己的包下面。
7. 增加自己的实现，实现方式随意【本质是让主线程阻塞，等待某个通知或信号，再继续往下执行】；
