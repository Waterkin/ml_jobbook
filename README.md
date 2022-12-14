---
description: 本Repo整理了全网关于算法工程师学习路线的资料，供各位参考，所有内容均copy自参考文献。
---

# 算法工程师指南

* [Part 1 数学基础](math/README.md)
  * [1. 微积分](math/calculus.md)
  * [2. 线性代数](math/linear_algebra.md)
  * [3. 概率论](math/probability.md)
  * [4. 概括](math/summary.md)
* [Part 2 计算机基础](cs/README.md)
  * [1. 数据结构与算法](cs/dsal.md)
  * [2. 计算机组成原理](cs/ca.md)
  * [3. 操作系统](cs/os.md)
  * [4. 计算机网络](cs/cn.md)
  * [5. 数据库](cs/sql.md)
* [Part 3 编程基础](coding/README.md)
  * [1. 编程语言：C++/Python](coding/language/README.md)
    * [C++](coding/language/c.md)
    * [Python](coding/language/python.md)
  * [2. 数据分析](coding/data_analysis/README.md)
    * [数据获取: SQL](coding/data_analysis/sql.md)
    * [数据预处理与数值计算](coding/data_analysis/preprocess.md)
    * [数据可视化](coding/data_analysis/visualize.md)
    * [误差分析与调优](coding/data_analysis/optimize.md)
  * [3. 开发工具](coding/tool/README.md)
    * [系统命令: Linux](coding/tool/linux.md)
    * [编辑器: Vim](coding/tool/vim.md)
    * [版本控制: Git](coding/tool/git.md)
  * [4. 编程艺术](coding/art/README.md)
    * [代码规范](coding/art/code.md)
    * [设计模式](coding/art/design_pattern.md)
    * [质量保障](coding/art/quality.md)
    * [项目管理](coding/art/program_management.md)
    * [高级话题](coding/art/advance_topics.md)
* [Part 4 机器学习与深度学习](mldl/README.md)
  * [1. 机器学习](mldl/ml.md)
  * [2. 深度学习](mldl/dl.md)
  * [3. 应用领域](mldl/application.md)
  * [4. 经典框架](mldl/package.md)
* [Part 5 算法工程交叉](cross/README.md)
  * [大规模算法运行](cross/large_scale/README.md)
    * [分布式训练](cross/large_scale/distributed_train.md)
    * [高性能计算](cross/large_scale/hpc.md)
    * [模型加速领域](cross/large_scale/model_acceleration.md)
  * [MLOps](cross/mlops/README.md)
    * [编排调度](cross/mlops/arrange.md)
    * [数据集成](cross/mlops/ensemble.md)
    * [实验管理](cross/mlops/experiment.md)
    * [Serving](cross/mlops/serving.md)
    * [CI/CD](cross/mlops/cicd.md)
    * [系统监控](cross/mlops/monitor.md)
    * [MLOps系统](cross/mlops/system.md)
  * [工程深入方向](cross/deeper/README.md)
    * [数据库](cross/deeper/sql/README.md)
      * [数据库原理](cross/deeper/sql/basic.md)
      * [关系型数据库](cross/deeper/sql/relational.md)
      * [NoSQL数据库](cross/deeper/sql/nosql.md)
    * [云计算](cross/deeper/cloud_computing/README.md)
      * [基础架构](cross/deeper/cloud_computing/architecture.md)
      * [分布式存储](cross/deeper/cloud_computing/distributed_storage.md)
      * [分布式计算](cross/deeper/cloud_computing/distributed_calculations.md)
      * [其它话题](cross/deeper/cloud_computing/others.md)
  * [算法深入方向](cross/deeperAI/README.md)
    * [AutoML](cross/deeperAI/automl/README.md)
      * [超参优化](cross/deeperAI/automl/hyperparam.md)
      * [元学习](cross/deeperAI/automl/meta_learning.md)
      * [NAS](cross/deeperAI/automl/nas.md)
      * [AutoML系统](cross/deeperAI/automl/system.md)
    * [模型解释](cross/deeperAI/model_interpretation/README.md)
      * [模型解释技术](cross/deeperAI/model_interpretation/tech.md)
      * [模型解释应用](cross/deeperAI/model_interpretation/application.md)
* [总结](summary/README.md)
* [参考文献](reference/README.md)

***

## Part 1 数学基础

* [AI算法工程师手册](https://www.huaxiaozhuan.com/)
* [深度学习面试宝典](https://github.com/amusi/AI-Job-Notes)

数学好是入门机器学习的优势，但并非关键。因为数学知识量太庞大了，花太多时间在其上，容易打击学习积极性。另外做算法一般分两种：理论模型和实际应用，前者的行业title是算法研究员，主要发paper、提出新的模型或者优化方法，所以对于数学能力要求很高。后者的行业title是算法工程师，致力于把模型应用于数据上，攫取商业价值，对于数学能力要求并不高。往往大部分人都属于后者，我个人也是后者。熟悉不同算法的应用场景、掌握模型落地工程技术，才是我们更应该投入精力的地方。

### 1. 微积分

通常情况下，机器学习需要得到一个函数（模型，或者说假设）来预测未来的数据。既然是函数，那自然就离不开微积分了。微积分为我们研究函数的性质提供了理论依据，同时它也是学习概率论、最优化方法等后续课程的基础，是整个高等数学的基石。重点掌握函数的求导法则（特别是链式法则），以及泰勒公式。这对后续的梯度下降法，牛顿法，拟牛顿法等优化算法的推导至关重要！

### 2. 线性代数

* [MIT线性代数](https://www.bilibili.com/video/av15463995/)

机器学习算法的输入、输出、中间结果通常为向量、矩阵、张量。这些都属于线性代数里的知识。 重点掌握向量、矩阵含义及其数学运算公式。

### 3. 概率论

* [All of Statistics](https://book.douban.com/subject/2285151/)

对于机器学习来说，概率论是一种重要的工具。如果将机器学习算法的输入、输出看作随机变量/向量，则可以用概率论的观点对问题进行建模。使用概率论的一个好处是可以对不确定性进行建模，这对于某些问题是非常有必要的。另外，它还可以挖掘变量之间的概率依赖关系，实现因果推理。重点掌握常见概率分布、概率公式。

### 4. 概括

在进行算法建模时，深入了解数据情况，做各类探索性分析，统计建模等工作非常重要，这方面对一些数学基础知识有一定的要求，例如概率论，统计学等。除了经典的数学教材，也可以参考更程序员向的《统计思维》，《贝叶斯方法》，《程序员的数学2》等书籍。

* 自我考核
  * 理解实际项目中的数据分布情况，并使用统计建模手段，推断预测值的置信区间。

***

## Part 2 计算机基础

* [深度学习面试宝典](https://github.com/amusi/AI-Job-Notes)

计算机基础包含数据结构与算法、计算机组成原理、操作系统、计算机网络、数据库、五大课程。其中数据结构与算法是面试必考内容，大家都会花时间好好学。但是另外4门课，开发岗面试中一定会问，算法岗却很少会问，再加上很多做算法的人是转行过来，非计算机科班出身，大学期间没有上过此类专业课。所以很多做算法的人计算机基础比较薄弱。但是在我看来计算机基础是很重要的。一是能提高我们计算机素养，二是增加工程代码理解能力。所以后面我会针对这四门课程，出一个面向算法工程师的系列文章，做到让大家对这些课程重点知识有个了解，同时又不会陷入细枝末节。这里先给大家做个大概讲解：

* [CMU CS15-213](https://www.bilibili.com/video/av31289365)

### 1. 数据结构与算法

数据结构包含：数组、链表、栈、队列、树、散列表、图。数据结构本质是描述数据与数据之间的关系算法包含：排序、查找、五大经典算法（动态规划、回溯、分支界限、分治、贪心）。计算机解决问题其实没有任何奇技淫巧，它唯一的解决办法就是穷举。算法设计的本质无非就是先思考「如何穷举」，然后再追求「如何聪明地穷举」。「聪明的穷举」分为两部分：「去掉重复的穷举」、「去掉不必要的穷举」。比如，备忘录法，用数组保存求过的结果，用空间换时间，这就是去掉重复的穷举；动态规划根据最优子结构，使当前问题只与某几个子问题有关，从而大大减少问题分解次数，这就是去掉不必要穷举。

* 书
  * 算法图解
  * Algorithms
  * 编程珠玑
  * 编程之美
* 刷题
  * 剑指offer
  * [Leetcode](https://github.com/ariafyy/iworkHunter)
  * [Leetcode2](https://github.com/Shaosifan/AI-Job-Interview)

### 2. 计算机组成原理

讲解计算机组成结构。主要由CPU（运算器、控制器），存储器（内存、外存），IO设备（输入、输出设备），总线这几部分构成。如果把计算机比作人，那么CPU是人的大脑，负责控制全身和运算；内存是人的记忆，负责临时存储；外存是人的笔记本，负责永久存储；输入设备是耳朵或眼睛或嘴巴，负责接收外部的信息存入内存；输出设备是你的脸部（表情）或者屁股，负责输出处理后的结果；以上所有的设备都通过总线连接，总线相当于人的神经。

### 3. 操作系统

是应用程序与硬件之间的管家：对下管理计算机硬件资源（CPU、存储器、IO设备）、对上管理应用程序。![](https://pic1.zhimg.com/50/v2-d9d6f7d2f3fc955560c99b986c861a62\_720w.jpg?source=1940ef5c) 内核（kernel）是直接控制硬件的。比如：内核控制硬件有1000种方式，导致直接调内核去操作硬件很麻烦，于是就封装内核，向外提供了易于调用的接口，比如：桌面系统、shell等。这些接口对非编程人员用户还是不友好，于是编程人员用编程语言再对这些接口在进行封装，就产生了应用程序。本质是封装的思想。我们学的编程语言到最后都是在调用操作系统内核API。所以这也是为什么所有的语言都有不同操作系统版本，因为每个操作系统的内核API是不同的。

* [深入理解计算机系统](https://www.zhihu.com/search?q=%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%B3%BB%E7%BB%9F\&search\_source=Entity\&hybrid\_search\_source=Entity\&hybrid\_search\_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2451928435%7D)
* [鸟哥的Linux私房菜](./)
* Operating Systems: Three Easy Pieces
* 现代操作系统
* 自我考核
  * 能够基本明确运行一个模型训练任务过程中，底层使用到的硬件，操作系统组件，及其交互运作的方式是如何的。

### 4. 计算机网络

很多教材都是从五层模型（物理层、数据链路层、网络层、传输层、应用层）讲解。其实这样讲是比较晦涩难懂的，因为很多东西我们都没接触过，很陌生。好的办法是通过人类的语言系统进行类比。计算机网络是计算机的语言系统，与人类语言系统的本质是一样的。 人类语言系统构成： 1.词汇 2.语法 3.声带+耳朵 4.传播介质：空气 以此类比到计算机网络： 1.数据：计算机之间传输的信息 2.通信协议：决定数据的排列方式 3.网卡：数据发射器与接收器 4.传播介质：光纤、网线、WIFI 此外还有人的身份证相当于Mac地址，家庭地址相当于IP地址等等。计算机网络中的许多概念都可以用生活中人类是如何通信的进行类比。人类通信我们是非常熟悉的，所以非常有助于我们理解。

* [计算机网络自顶向下方法](https://link.zhihu.com/?target=https%3A//www.bilibili.com/video/BV1mb4y1d7K7)
* [图解HTTP](https://book.douban.com/subject/25863515/)

### 5. 数据库

数据库就是我们存储数据的工具。数据如何存储与读取，直接决定了整个系统的效率。常用的关系型数据库是MySQL，非关系型数据库是Redis

* [SQL必知必会](./)
* [一天学会 MySQL 数据库](https://link.zhihu.com/?target=https%3A//www.bilibili.com/video/BV1Vt411z7wy)

***

## Part 3 编程基础

### 1. 编程语言：C++/Python

#### C++

* C++ Primer 第五版
* 自我考核：能够读懂LightGBM里对于tweedie loss的相关定义代码。

#### Python

* Learn Python the Hard Way
  * 自我考核：能够读懂大多数的内部项目及一些开源项目代码的基本模块，例如pandas, sklearn等。
* 学习Python的编程风格、代码规范
  * 自我考核：编写的代码符合编码规范，能够通过各类lint检查。
* Fluent Python
  * 自我考核：能够读懂一些复杂的Python项目，例如sqlalchemy中就大量使用了元编程技巧。在实际工程项目中，能够找到一些应用高级技巧的点进行实践，例如基于Cython的性能优化等。
* 了解一下Python web开发，测试开发相关的内容，开拓视野。
  * 自我考核：以Web开发和测试开发为例，尝试写一个简单的model serving http服务，并编写相应的自动化测试。

### 2. 数据分析

#### 数据获取: SQL

算法工程师经常自嘲为sql boy确实不是开玩笑的，数据分析、特征处理其实占据了工作的主要时间，写一手好SQL能大大提升工作效率

* 小数据
  * SQL必知必会
    * 入门级别SQL书
* 大数据
  * 在实际工业场景中，我们面临的都是海量数据，也就是所谓的大数据。再用上面提到的MySQL数据库、numpy、pandas等工具是不行的。这个时候就需要专业的大数据处理工具：Hadoop、Spark生态。有的同学想从这些生态的基本原理学起， 如果有时间，知其所以然是好的，但往往我们需要兼顾算法和大数据，时间并不是很充足，所以建议大数据这块可以先掌握到会用的层次，当做工具即可。
  * 常用的：首先是Hive查询，也就是用HQL进行一些表数据的基础查询，这个和SQL有些类似，另外一个，就是sparkSQL以及spark的DataFrame， 这些相关操作常用来做数据分析和处理，处理完毕之后，写回到Hive表里面。其次，遇到复杂的处理逻辑，就需要写原生spark脚本去跑数据了。关于这块知识，后面也会整理一篇文章。
  * Hadoop
    * [尚硅谷大数据Hadoop 3.x](https://www.bilibili.com/video/BV1Qp4y1n7EN/)
  * Hive
    * Hive是使用SQL进行MapReduce计算的大数据工具
    * [Hive编程指南](https://book.douban.com/subject/25791255/)
  * Spark
    * Spark是一个分布式计算引擎，和MapReduce属于同一级别，同时支持scala, java, python接口，灵活性非常高，原生支持SQL和HQL，也可以做机器学习(不支持深度学习)
    * [官方文档](https://spark.apache.org/docs/latest/)
      * 一般的开源框架，最好的学习手册一般都是官方文档，因为版本变化很快
    * [高性能spark](https://book.douban.com/subject/30166057/)
      * 讲了一些spark原理和调优方案
    * [尚硅谷大数据Spark教程从入门到精通](https://www.bilibili.com/video/BV11A411L7CK/)
  * [推荐系统算法基础+综合项目实战](https://www.bilibili.com/video/BV1qK4y1479r/?vd\_source=4aef3e7382df91626c7d0ef6aa02d68d)
    * 包含推荐系统算法、hadoop、Hbase、Hive、spark等项目：离线用户、实时计算业务、推荐业务与深度学习。
* 在项目实施过程中，会需要各类复杂的数据处理操作，因此熟练掌握此类框架就显得尤为重要。目前行业的标准基本上会参照Pandas DataFrame的定义，在数据量较大的情况下，也有许多类似的框架，如Spark，Dask，Modin，Mars等支持分布式运行的DataFrame，以及cuDF，Vaex等提升单机性能的改进实现。这方面经典的书籍可以参考Wes McKinney的《Python for Data Analysis》，在掌握基础数据操作的基础上，可以进而了解窗口函数，向量化性能优化等高级话题。另外SQL也可以做非常复杂的数据处理工作，有不少公司例如阿里会以SQL为主来构建数据处理流程，感兴趣的同学也可以学习一下SQL中各种高级计算的使用及优化方法。
* 自我考核
  * 在已有项目中，能把至少三个使用apply方法的pandas处理修改成向量化运行，并测试性能提升。使用window function或其它方案来实现lag特征，减少join次数。

#### 数据预处理与数值计算

* 矩阵运算：[numpy](https://github.com/datawhalechina/powerful-numpy)
* 表格处理：[pandas](https://github.com/datawhalechina/joyful-pandas)
* 科学计算：scipy
* 特征工程
  * tsfresh
  * Featuretools
  * Feast

#### 数据可视化

论点1：可视化这块基本感觉是锦上添花，很多时候做了几个自我感觉良好的图，然后往往boss或者pm想看的就是表格而已，可能是因为可视化相比于纯数字很容易造成错觉，引起错误的判断。

* [Tableau](https://www.tableau.com/)，付费可视化工具，效果很酷炫，对地图数据的展示很棒
* Excel，看起来low但实际最方便的工具之一
* [matplotlib](https://github.com/datawhalechina/fantastic-matplotlib)
* pyecharts
* seaborn
* Bokeh
* D3.js 论点2：在进行数据分析时，可视化是一个非常重要的手段，有助于我们快速理解数据情况，发掘数据规律，并排查异常点。对于各种不同类型的数据，会对应不同的可视化最佳实践，如选择不同的图表类型，板式设计，分析思路编排，人机交互方式等等。另一方面，可视化与数据报告也是我们与不同角色人群沟通数据insights的一个重要途径，需要从业务角度出发去思考可视化与沟通方式。
* Storytelling with Data
* The Visual Display of Quantitative Information 同时也需要培养自己的商业背景sense，提升沟通能力。
* 自我考核
  * 对内沟通方面，能使用可视化技术，分析模型的bad case情况，并确定优化改进方向。对外沟通方面，能独立完成项目的数据分析沟通报告。

#### 误差分析与调优

* [人类早期驯服野生机器学习模型的珍贵资料](https://zhuanlan.zhihu.com/p/330577488) 在做算法模型调优改进中，需要从数据分析的基础上出发来决定实验方向，这么做有几个好处：
* 从分析出发指导调优更有方向性，而不是凭经验加个特征，改个参数碰运气。哪怕是业务方提供的信息，也最好是有数据分析为前提再做尝试，而不是当成一个既定事实。
* 由分析发现的根源问题，对于结果验证也更有帮助。尤其在预测的数据量极大情况下，加一个单一特征很可能总体只有千分位准确率的提升，无法确定是天然波动还是真实的提升。但如果有分析的前提，那么我们可以有针对性的看对于这个已知问题，我们的调优策略是否生效，而不是只看一个总体准确率。
* 对于问题的彻底排查解决也更有帮助，有时候结果没有提升，不一定是特征没用，也可能是特征代码有bug之类的问题。带着数据分析的目标去看为什么这个特征没有效果，是模型没学到还是特征没有区分度等，有没有改进方案，对于我们评判调优尝试是否成功的原因也更能彻查到底。
* 数据分析会帮助我们发现一些额外的问题点，比如销量数据清洗处理是不是有问题，是不是业务本身有异常，需要剔除数据等。 这方面在业界有一些关于误差分析的探索研究，不过大多数都是基于分类问题的，例如：
* Identifying Unknown Unknowns in the Open World
* A Characterization of Prediction Errors 可以在了解这些研究的基础上，结合具体的业务情况，深入思考总结误差分析的思路与方法论。
* 自我考核
  * 在项目中形成一套可以重复使用的误差分析方案，能够快速从预测输出中定位到目前模型最重要的误差类别，并一定程度上寻找到根本原因。

### 3. 开发工具

#### 系统命令: Linux

* 资料
  * [Linux基础](https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/tree/main/%E4%B8%80%E3%80%81%E5%B7%A5%E7%A8%8B%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/Linux%E5%9F%BA%E7%A1%80)
  * [linux命令行与shell脚本编程大全](https://book.douban.com/subject/26854226/)
    * 不管愿不愿意，在服务器上开发总是不可避免的，基本命令的学习让你可以顺畅完成工作，一些高级命令更是如虎添翼，python当然也可以用于脚本，但在很多任务下相比原生的工具，无论在速度还是代码简洁性方面都有很大差距
  * [Cornell CS2043 Unix Tools & Scripting](https://www.cs.cornell.edu/courses/cs2043/2014sp/)
    * 不错的unix工具入门课
* 自我考核
  * 开发一个shell小工具，实现一些日常工作需求，例如定时自动清理数据文件夹中超过一定年龄的数据文件，自动清理内存占用较大且运行时间较久的jupyter notebook进程等。
* 深入应用
  * 工作中碰到的疑难问题排查，性能分析与优化，系统运维及稳定性工程等方面，都需要较为深入的计算机体系和操作系统知识，感兴趣的同学可以针对性的进行深入学习。以性能优化为例，可以学习经典的《性能之巅》，了解其中的原理及高级工具链。像其中的系统调用追踪(strace)，动态追踪(systemtap, DTrace, perf, eBPF)等技术，对于操作系统相关的问题排查都会很有帮助。
  * 自我考核
    * 能够分析定位出LightGBM训练过程中的性能瓶颈，精确到函数调用甚至代码行号的级别。

#### 编辑器: Vim

* [Vim实用技巧](https://book.douban.com/subject/25869486/)

#### 版本控制: Git

* [ProGit2](https://github.com/progit/progit2-zh)
  * 如果你公司的代码需要版本控制，但你没有系统学习过git，那几乎可以保证总有一天你会搞出问题而不知道如何修复，这本书可以满足你的一切需求
* [LearnGitBranching](https://learngitbranching.js.org/)
  * git的动画教学加练习

### 4. 编程艺术

#### 代码规范

* 书
  * [代码整洁之道](https://book.douban.com/subject/4199741/)
    * 教会你区分好代码与坏代码，有助于培养程序审美
  * [代码大全](https://book.douban.com/subject/1477390/)
    * 名字很霸气的一本书，评分很高，阅读中
  * 编写可读代码的艺术
  * Clean Code
  * Code Complete
  * The Pragmatic Programmer
  * Effective Python
* 自我考核
  * 审视自己写的项目代码，能发现并修正至少三处不符合最佳编码实践的问题。

#### 设计模式

* [Python架构模式](https://zhuanlan.zhihu.com/p/257281522)
* 书
  * [基本概念](https://refactoringguru.cn/design-patterns/python)
  * [设计模式](https://book.douban.com/subject/1052241/)
    * 很经典的书，阅读起来相对枯燥
  * [重构-改善既有的代码设计](https://book.douban.com/subject/1229923/)
    * 一段代码很烂很多时候是很容易看出来的，但重构往往吃力不讨好，因为不产生即时的商业价值，而且容易产生bug，但这本书会告诉你为什么需要做重构以及如何避免重构带来的问题
  * [Python in Practice](./)
  * Clean Architecture
* 自我考核
  * 在项目中，找到一处可以应用设计模式的地方，进行重构改进。

#### 质量保障

对于需要实际上线运行的软件工程，质量保障是非常重要的一个环节，能够确保整个产品按照期望的方式进行运作。在机器学习项目中，由于引入了数据这个因素，相比传统的软件测试会有更高的难度，也是业界还在摸索前进的方向。

* 书
  * 单元测试的艺术
  * Google软件测试之道
    * 大致理解软件测试的一些基本概念和运作方式
* 阅读Martin Fowler对于机器学习领域提出的CD4ML中相关的测试环节
* 学习sklearn，LightGBM等开源库的测试开发方式，掌握机器学习相关的质量保障技术能力。
* 自我考核
  * 在项目中，实现基础的数据输入测试，预测输出测试。

#### 项目管理

软件工程推进过程中，项目管理相关的技能方法与工具运用也非常的关键。其中各种研发流程与规范，例如敏捷开发，设计评审，代码评审，版本管控，任务看板管理等，都是实际项目推进中非常重要的知识技能点。

* 书
  * 构建之法
  * [人月神话](https://book.douban.com/subject/1102259/)
    * Brooks法则： 向进度落后的项目中增加人手，只会使进度更加落后，记得最深也有所体验的一句话
* 课程
  * 极客时间 -《项目管理实战20讲》
* 自我考核
  * 在某个负责项目中运用项目管理方法，完成一个实际的需求评估，项目规划，设计与评审，开发执行，项目上线，监控维护流程，并对整个过程做复盘总结。

#### 高级话题

软件工程师在技能方向成长的一条路线就是成为软件架构师，在这个方向上对于技能点会有非常高的综合性要求，其中也有不少高级话题需要深入学习和了解，例如技术选型与系统架构设计，架构设计原则与模式，宽广的研发知识视野，高性能，高可用，可扩展性，安全性等等。

* 书
  * 微服务架构设计模式
  * 领域驱动设计方面的一系列书籍
* 课程
  * 极客时间 - 《从0开始学架构》

***

## Part 4 机器学习与深度学习

### 1. 机器学习

* [李宏毅2022机器学习](https://github.com/virginiakm1988/ML2022-Spring)
* 工具库
  * scikit-learn
    * Hands-on-Machine-Learning-with-Scikit-Learn
  * [pyspark(spark mllib)](https://spark.apache.org/docs/1.2.2/ml-guide.html)
  * lightgbm
  * xgboost
  * [CRF++](https://taku910.github.io/crfpp/)
* 自我考核
  * 结合实际业务和机器学习理论知识，挖掘项目中算法表现不够好的问题，并通过算法改造进行提升或解决。

### 2. 深度学习

在学习理论原理的基础上，尤其要注意在实际算法应用中，能够通过观察各种指标与数据分析，找到提升模型的操作改进方向。

* 课程
  * [李沐 - 动手学深度学习](https://zh-v2.d2l.ai/)
  * [CV - Stanford CS231N](http://cs231n.stanford.edu/)
    * 卷积神经网络（CNN）及其改进
  * [NLP - Stanford CS224N](http://web.stanford.edu/class/cs224n/)
    * 循环神经网络（RNN）及其改进，Transformer、Bert等
  * [RL - UCB CS285](https://rail.eecs.berkeley.edu/deeprlcourse/)
  * [MTL - Stanford CS330](https://cs330.stanford.edu/)
* 书
  * [邱锡鹏 - 神经网络与深度学习](https://nndl.github.io/)
* 工具库
  * \[tensorflow]
  * \[pytorch]
  * \[keras]
* 实战
  * 比赛
    * [kaggle](https://www.kaggle.com/)
    * 公众号
      * Datawhale
      * kaggle竞赛宝典
      * Coggle数据科学
      * 第一次打比赛
    * 书
      * 机器学习算法竞赛实战
  * 项目
    * [Datawhale人工智能培养方案](https://datawhale.feishu.cn/docs/doccn0AOicI3LJ8RwhY0cuDPSOc)
      * 实践模块有很多新手项目
* 自我考核
  * 能够在实际项目中，使用深度学习模型，达到接近甚至超过传统GBDT模型的精确度效果，或者通过ensemble，embedding特征方式，提升已有模型的精度。

### 3. 应用领域

目前我们的业务领域在时间序列预测，自然语言处理，推荐等方面，其它类似图像，搜索，广告等领域也都有各自的一些领域建模方法。在时间序列领域，包括了传统时序模型，如ARIMA, Prophet，机器学习模型，如划动窗口特征构建方法结合LightGBM，及深度学习模型，例如LSTM，seq2seq，transformer等。这方面可以参考Kaggle上相关比赛的方案分享，以及Amazon，Uber，天猫等有类似业务场景公司的分享资料。其它领域也是类似，通过了解历史技术演进，相关比赛，业界的方案分享与开源项目，会议论文来逐渐掌握学习建模方法，结合实际业务进行实践尝试，积累起更加体系性的个人知识技能。

* [圆圆干货算法笔记（持续更新）密码：pft0](https://www.yuque.com/docs/share/84cc1c03-d671-4c6b-a6a0-084310f5ba0b?)
  * 包含迁移学习、表示学习、NLP、时间序列、推荐系统等方向
* [推荐系统](https://mp.weixin.qq.com/s/aaOosZ57qJpIU6cma820Xw)
  * 目的
    * 掌握Embedding、Wide & Deep及其改进
  * 书
    * 深度学习推荐系统
  * 博客
    * [经典算法模型复现](https://github.com/zhongqiangwu960812/AI-RecommenderSystem)
      * [模型原理](https://blog.csdn.net/wuzhongqiang/category\_10128687.html)
    * [推荐系统学习框架 基于Tensorflow2.x](https://github.com/ZiyaoGeng/RecLearn/blob/reclearn/README\_CN.md)
      * 适合学生、初学者研究使用
  * [过程](https://pica.zhimg.com/v2-7d86fc08908e87447f3a12712ab7b8a4\_r.jpg?source=1940ef5c)
    * [思维导图](https://pica.zhimg.com/80/v2-5ef3a2bd7425ab7c1093312ff7518577\_1440w.webp?source=1940ef5c)
    * 召回粗排
      * 召回的目的是根据用户部分特征，从海量物品库快速找到小部分用户感兴趣的物品交给精排，重点是强调快。主要有两大类召回方式，一类是策略规则，一类是监督模型+embedding。其中策略规则，往往和业务场景是强相关，不同的场景会有不同的召回方式，对于这种"特异性"较强的知识，会放到后期讲。目前打算先讲解普适的方法，就是模型+embedding。上图梳理出了目前给用户和物品打embedding的主流方法， 比如FM系列（FM,FFM等）， 用户行为序列，基于图和知识图谱系列，经典双塔系列等。这些方法看似很多很复杂，其实本质上还是给用户和物品打embedding而已，只不过考虑的角度方式不同。这一块的内容，几乎每个模型都对应着经典paper，所以会采用解读论文的方式给大家分享。在解读的过程中，对于一些重要模型，会进行代码复现，并应用到一些真实的实践任务中。至于粗排，有时候召回环节返回的物品数量还是太多，怕精排速度跟不上，所以可以在召回和精排之间加一个粗排环节，通过少量用户和物品特征，简单模型，来对召回的结果进行个粗略的排序，在保证一定精准的前提下，进一步减少往后传送的物品数量，粗排往往是可选的。因此粗排用到的很多技术与召回重合，所以先暂且归并到召回里，等后面把整体的基础知识都补充完毕了，再看情况要不要展开这块。
    * 精排
      * 精排阶段使用你能想到的任何特征，可以上你能承受速度极限的复杂模型，尽可能精准地对物品进行个性化排序，强调准确性。这一块关键技术主要分为三大块：CTR预估：LR、FM家族、自动特征交叉的DNN家族。多任务学习（Multi-Task Learning，也称为多目标学习）。多任务是很常见的，比如视频推荐中，用户喜欢、收藏、评论。而不同的任务可能会互相冲突，互相影响，造成模型学习起来十分困难。所以这一块是重难点，也是很多大公司的研究重点，更是未来的一大发展趋势。但好在这里每个模型或者技术有对应paper，所以和召回一样，这里依然可以利用解读paper的方式，把这些模型和技术娓娓道来。排序打分公式融合。
    * 重排
      * 考虑到上面的两块是核心，这块没有详细的展开整理，并且这块和业务场景策略强相关，很依赖工作经验。
    * 冷启动
      * 冷启动问题是指对于新用户和新商品，他们没有历史交互数据，无法分析历史喜好，这个时候我们应该如何做推荐。冷启动技术会穿插到召回或者重排中，有时也会和上面推荐系统做成并行的两路，专门应对冷启动场景。
  * 实战项目
    * [FunRec](https://github.com/datawhalechina/fun-rec)
    * [推荐系统算法基础+综合项目实战](https://www.bilibili.com/video/BV1qK4y1479r/?vd\_source=4aef3e7382df91626c7d0ef6aa02d68d)
      * 包含推荐系统算法、hadoop、Hbase、Hive、spark等项目：离线用户、实时计算业务、推荐业务与深度学习。
* 自我考核
  * 在项目中复现一个Kaggle获胜方案，检验其效果，分析模型表现背后的原因，并尝试进行改进。

### 4. 经典框架

机器学习方面的新框架层出不穷，一方面我们需要掌握经典框架的使用方式，理解其模块构成，接口规范的设计，一定程度上来说其它新框架也都需要遵循这些业界标准框架的模块与接口定义。另一方面对于新框架或特定领域框架，我们需要掌握快速评估，上手使用，并且做一定改造适配的能力。一些比较经典的框架有：

* 通用机器学习：scikit-learn，Spark ML，LightGBM
* 通用深度学习：Keras/TensorFlow，PyTorch
* 特征工程：tsfresh, Featuretools，Feast
* AutoML：hyperopt，SMAC3，nni，autogluon
* 可解释机器学习：shap，aix360，eli5，interpret
* 异常检测：pyod，egads
* 可视化：pyecharts，seaborn
* 数据质量：cerberus，pandas\_profiling，Deequ
* 时间序列：fbprophet，sktime，pyts
* 大规模机器学习：Horovod，BigDL，mmlspark
* Pipeline：MLflow, metaflow，KubeFlow，Hopsworks 一般的学习路径主要是阅读这些框架的官方文档和tutorial，在自己的项目中进行尝试使用。对于一些核心接口，也可以阅读一下相关的源代码，深入理解其背后的原理。
* 自我考核
  * 在LightGBM框架下，实现一个自定义的损失函数，并跑通训练与预测流程。

其它比较常见且与算法工程师日常工作会有一些联系的有Web框架，爬虫框架等，最具有代表性的当属Flask和scrapy。这两者背后各自又是很大一块领域，尤其web开发更是保罗万象。感兴趣的同学还可以了解一下一些新兴的基于Python3的框架，例如FastAPI，其背后借鉴的许多现代框架的思想设计，包括数据验证，序列化，自动文档，异步高性能等，开拓一下知识面。

* 自我考核
  * 实现一个简单的model serving http服务。

## Part 5 算法工程交叉

#### 大规模算法运行

**分布式训练**

在很多项目中，数据量达到十亿级以上的情况下，单机训练会难以支撑。因此分布式训练也是实际工程落地中非常重要的一个主题。分布式训练涉及到多机的通讯协同方式，优化算法的改造，数据及模型的并行与聚合，以及框架的选择和运维等话题，具体可以参考《分布式机器学习》。另外对于分布式系统，也可以参阅《数据密集型应用系统设计》这本神作，了解其背后原理。

* 自我考核
  * 能够在多机上进行亿级数据的GBDT模型训练与预测。

**高性能计算**

在做大规模的数据训练与推理时，近些年涌现出许多高性能计算优化的方法，例如从硬件方面，有各种超线程技术，向量化指令集，GPGPU，TPU的应用等，从软件方面，有针对数值计算场景的OpenBLAS，有自动并行化的OpenMP，有各种codegen，JIT技术下的运行时优化等。这方面可以学习的方向也很多，从基础的并行编程，编译原理及优化的知识开始，到CUDA，OpenMP的应用（例如Nvidia的cuDNN，还有LightGBM中也用到了OpenMP），Codegen，JIT等技术在Spark，TVM等项目中的使用等，建议有深度性能优化需求时可以往这些方向做调研和学习。

* 自我考核
  * 能够通过LLVM JIT来优化实现Spark window function的执行性能

**模型加速领域**

这个方向分两个部分，一块是模型训练方面，能够做到加速，例如使用大batch size，迁移学习，持续的在线/增量学习等手段，另一块在模型预测方面，也有很多加速需求，比如模型参数量优化，模型压缩，混合精度，知识蒸馏等技术手段，都是为了做到更高性能，更低资源消耗的模型预测推理。这方面业界有各个方向的文章和技术实现可以参考

* Training ImageNet in 1 Hour
* MobileNet
* TensorRT
* 二值网络
* 自我考核
  * 在典型的销量预测场景中实现增量训练与预测。

#### MLOps

* [UCB - Full Stack Deep Learning](https://zhuanlan.zhihu.com/p/218468169)
* [从小作坊到智能中枢: MLOps简介](https://zhuanlan.zhihu.com/p/357897337)

**编排调度**

包含各类pipeline的编排与调度能力的支持，包括数据pipeline，训练pipeline和serving pipeline等。这方面比较常用的框架工具有：

* Airflow
* DolphinScheduler
* Cadence 需要掌握其基本的工作原理和使用方式，并能够应用于离线实验与线上运行。
* 自我考核
  * 使用Airflow完成一个标准的项目pipeline搭建与运行

**数据集成**

相对于传统的DevOps，机器学习项目最大的区别在于数据方面的依赖会更加显著与重要。这方面的话题包括数据血缘，数据质量保障，数据版本控制等，有各类工具可以借鉴使用，例如数据版本管理方面的DVC，数据质量方面的TFX Data Validation，Cerberus，Deequ等。在方法论层面，《The ML Test Score》中给出了不少数据相关的具体测试方法，值得参考学习。

**实验管理**

这部分也是ML项目的独特之处，在开发过程中有大量的实验及相应的结果输出需要记录，以指导后续调整优化的方向，并选择最优结果来进行上线部署。这方面可以参考的项目有MLflow，fitlog，wandb等。当然对于单独的项目来说，可能online Excel就能满足需求了

* 自我考核
  * 在实际项目中实行一套标准的实验记录手段，并能从中找出各类实验尝试带来的精度提升的top 5分别是哪些操作。

**Serving**

目前我们的serving大多数是离线batch预计算的形式，所以主要依赖的技术手段是各类离线inference的方法，例如直接使用model predict接口，使用mmlspark等做大规模并行inference等。如果涉及到在线serving，情况会更加复杂，例如在线pipeline的运行，实时特征获取，low latency/high throughput的serving服务等，可以参考TF Serving，MLeap，H2O，PredictionIO，PMML/PFA/ONNX等开发标准模型格式等。

* 自我考核
  * 部署一个实时预测服务，能够根据用户输入产生相应的预测结果。

**CI/CD**

软件工程中的持续集成，持续部署已经成为一种标准实践，在算法项目中，额外引入了数据这个维度的复杂性，带来了一些新的挑战。在这个方向上，几个主要话题包括自动化测试，pipeline打包部署，持续监控运维等，可以参考Martin Fowler关于CD4ML的文章。工具系统层面，可以学习传统的Jenkins，也有一些新选择例如CircleCI，GoCD，VerCD（Uber）等。

* 自我考核
  * 通过Jenkins实现pipeline自动测试，打包，上线流程。

**系统监控**

在整个项目上线后，需要对系统的各个环节进行监控，并对各种异常情况作出响应。例如：

* 输入数据的监控
  * 判别测试数据与训练数据的分布是否有偏移
* 整个运行pipeline的监控
  * 判别是否有运行失败抛出异常的情况
* 预测输出的监控
  * 确保没有异常的预测输出值
* 系统计算资源等方面的监控
  * 确保不会因为资源不足导致业务受到影响等。 在监控信息收集，基础上，还需要配套一系列的自动告警通知，日志追踪排查等。这方面的工具框架包括TF data validation这类专门针对算法项目的新产品，也有elasicsearch + kibana这类传统产品。
* 自我考核
  * 将三个项目中做过的问题排查改造成常规监控手段，支持自动的问题发现，告警通知，如有可能，提供自动化或半自动化的问题排查解决方案。

**MLOps系统**

MLOps整体是一个比较大的话题，在这方面有很多产品和系统设计方面的实践可以参考学习。例如Uber的Michelangelo系列文章，Facebook的FBLearner，neptune.ai，dataiku，domino等，虽然没有开源，但是其背后的很多设计理念，演进思考，白皮书等都非常值得我们学习。在开源界也有很多可以参考的项目，例如MLflow，Kubeflow，Metaflow，TFX等，可以学习他们的设计理念，Roadmap，以及实现细节等。

* 自我考核
  * 总结各个MLOps产品的功能模块矩阵对比，能够根据项目需求来进行产品选型与使用。

#### 工程深入方向

**数据库**

**数据库原理**

在平时工作中，我们有大量的场景需要用到数据库。从客户数据的对接，数据集的管理和使用，到各种业务系统的数据表设计及优化等，都需要对数据库的运作原理，适用场景，运维使用，性能优化等方面有一定的了解。常见的需要掌握的概念有OLTP vs OLAP，事务，索引，隔离级别，ACID与CAP理论，数据同步，数据分片，SQL语法，ORM等。从底层原理看，会涉及到数据，索引，及日志等存储引擎方面，以及各种计算查询引擎，包括分布式系统的设计与实现。这方面推荐的学习资料有：

* 《数据库系统内幕》
* 《数据密集型应用系统设计》

**关系型数据库**

目前常用的关系型数据库主要是MySQL和PostgreSQL，主要需要掌握的是日常的一些SQL操作，例如DML（增删改查），DDL（创建表，修改索引等），DCL（权限相关）。在此基础上还可以进一步了解一些如数据类型，高级计算，存储引擎，部署运维，范式概念与表结构设计等方面的话题。对于高级话题这块，推荐：

* 《高性能MySQL》
* 《高可用MySQL》

**NoSQL数据库**

常用的NoSQL数据库有几类，KV存储（Redis），文档数据库（MongoDB），Wide-column存储（Cassandra，HBase）以及图数据库（Neo4j）。在目前我们的算法项目中，比较有可能会用到的主要是Redis这类KV存储（也可能把Cassandra之类当泛KV来用），或者更新一点的类似Delta Lake的存储系统。建议学习了解一下这类KV存储，以及分布式数据库的常见操作方式，以及基础的运维排查，性能优化方法。

* 自我考核
  * 考虑一个线上模型服务的场景，用户输入作为基础特征，使用类似Redis的KV系统，实现实时获取其它特征，并进行模型预测。

**云计算**

**基础架构**

IT系统总体的发展趋势在往云计算方向演进，即使是自建的基础设施，也会采用云计算的一套构建方式，让开发者不用过多的关注底层计算存储资源的部署运维。对于应用开发者来说，需要了解一些基础架构方面的知识，例如各类虚拟化及容器技术，配置管理，容器编排等，便于在日常工作中使用相关技术来管理和发布应用。从工具层面看，Docker与k8s等技术发展速度较快，主要还是根据官方文档来学习为主。浙大之前出版的《Docker - 容器与容器云》一书中有一些更深入的话题的探讨，另外《Kubernetes in Action》中也值得一读。从方法论层面看，《Infrastructure as Code》和《Site Reiliability Engineering》是两本非常不错的学习资料。与算法应用结合的虚拟化，运维，持续集成等都是比较新的领域，需要我们探索出一条可行路线。

* 自我考核
  * 对于已有的算法项目，总结制定一套开发，测试，发布，运维的标准流程，且尽可能自动化执行。

**分布式存储**

前些年最流行的分布式存储是脱胎于Google经典的GFS论文实现的HDFS，不过随着硬件技术的发展，计算存储分离思想的逐渐兴起，不但灵活性更高，成本更低，且各自架构的复杂度也大大降低了。因此目前更建议学习简单的object store形式的分布式存储，例如s3，minio等。在此基础上的一些存储系统，例如Delta Lake，提供了事务，高效的upsert，time travel等功能，也值得关注与学习。原理方面，还是推荐《数据密集型应用设计》这本。

* 自我考核
  * 在项目中实现不同机器能够访问同一个s3路径的文件，并进行正常的数据读写，模型文件读写等功能。

**分布式计算**

大数据时代的分布式计算的鼻祖来自于Google经典的MapReduce论文，后续在Hadoop系统中做了开源实现，在前几年是非常火热的一项技术。目前业界的主流是Spark和Flink，前者在批处理计算中处于霸者地位，后者是流处理领域的领先者。目前我们的业务应用中，Spark是比较常用的分布式计算引擎，其基本操作相关内容比较简单，参考官方文档或者《Spark快速大数据分析》即可。后续的主要难点会有大数据量下的问题排查与性能调优，执行复杂计算或与Python相关UDF的交互配合方式等。这方面需要对Spark的系统架构，内部原理有一定了解，例如master，worker，driver，executor等之间的关系，lazy evaluation，DAG的lineage与stage概念，shuffle优化，wholestage codegen等技术细节。这方面暂时没有找到比较好的资料，主要还是依赖实际问题解决的经验积累。

* 自我考核
  * 用Spark来实现项目中的特征工程，并在一定数据量情况下取得比单机Pandas更好的性能效果。

**其它话题**

其它云服务基础设施还包括分布式数据库，消息队列，zk/raft分布式协作系统，虚拟网络，负载均衡等。这些话题离算法应用方面会比较远一些，基本上达到遇到需求时会使用的能力即可，在这里不做展开。

#### 算法深入方向

**AutoML**

* [走马观花AutoML](https://zhuanlan.zhihu.com/p/212512984)

**超参优化**

自动化机器学习中比较传统的一块是超参数优化，进而可以推广到整个pipeline的超参优化，包括数据预处理，特征工程，特征选择，模型选择，模型调优，后处理等部分。目前业界应用比较广泛的技术手段主要是随机搜索，贝叶斯优化，进化算法，Hyperband/BOHB等，在特征工程方面有Featuretools，tsfresh，AutoCross等自动化特征工程工具。学术界有一些进一步的探索研究，包括multi-fidelity优化，多任务优化，HPO结合ensemble learning，pipeline planning，data diff自动数据分布探测等方面。可以参考[automl](http://automl.org)上的各类参考资料与书籍进行学习了解。主要难点包括automl算法的泛化能力，scalability，整体pipeline组合的搜索与生成，针对不同学习算法的自动优化手段等。

* 自我考核
  * 了解超参优化的基础概念，能够在项目中应用框架工具来实现模型超参的贝叶斯优化流程。

**元学习**

Meta learning是近年来非常活跃的一个新兴领域，其主要思路是希望能通过元学习模型方法，去积累建模调优的先验知识，跨任务推断模型效果并warm start新的训练任务，或者指导学习算法来进行更高效的具体任务的训练过程。这方面在工业界的主要应用基本上集中在建模调优先验知识的积累方面，比如通过一系列公开数据集搜索寻找出表现较好的起始参数，用于指导在新任务上做超参优化的起始搜索点。学术研究中除了configuration space的研究，还包括从learning curve中进行学习推断，元特征提取与建模，HTN planning在pipeline构建中的应用，以及MAML等few-shot learning方向的探索。这方面推荐[Lilian Weng的一系列文章](https://lilianweng.github.io/lil-log/2018/11/30/meta-learning.html)，以及[automl](http://automl.org)网站上的资料。

* 自我考核
  * 设计一系列meta feature与meta learning手段，实现对新任务的参数选择的初始化。

**NAS**

AutoML领域比较火，但也是比较特别的一个方向，目前需要大量的计算资源投入才能做这方面的研究与尝试，因此主要建议了解一下这个方向的一些工作即可，不做深入探索学习。

**AutoML系统**

自动化机器学习相关的框架工具也非常多，比较有代表性的框架有auto-sklearn(来自http://automl.org团队)，nni(microsoft)，auto-gluon(amazon)，H2O，ray tune等，在工具级别也有如hyperopt，SMAC3，featuretools等。可以通过学习这些工具框架，了解AutoML系统的架构与实现方式，并应用到实际项目中。

* 自我考核
  * 使用一种AutoML系统来进行项目的模型自动优化，并与手工优化的结果进行比较，看是否有所提升，及寻找背后的原因。

**模型解释**

* [初探Explainable AI](https://zhuanlan.zhihu.com/p/238202269)

**模型解释技术**

主要有三个方面，

* 一是模型本身的解释性
  * 例如线性回归，决策树等，模型结构简单，根据其原理，可以直接对预测结果，特征使用等方面给出解释
  * 另外一些复杂模型，例如EBM，神经网络，Bayesian rule lists，SLIMs等，也可以利用一些本身的特性给出一些解释，例如GradCAM方法等
* 二是模型无关的解释方法
  * 包括经典的PDP，ICE等特征图，LIME等surrogate model方法，以及基于博弈论的Shapley方法。
* 三是基于sample的解释方法，例如conterfactual explanations，adversarial examples，prototypes，influential instances，kNN等，不过看起来这类方法对于计算的开销一般都会比较大，不太容易在工程中实现落地。 这方面的资料可以学习《Interpretable Machine Learning》和《Explainable AI》（关于深度学习的内容会更多）。另外学术界也有很多前沿探索，比如针对模型解释的降维工作，自动的时间序列分析及报告生成，因果模型，模型公平性及社会影响等方面，可以保持关注。
* 自我考核
  * 理解LIME，Shapley的运作原理，并分析其局限性，尝试提出改进方案

**模型解释应用**

从工具框架方面，有许多可以使用的开源项目，例如微软的interpret，eli5，shap，AIX360等。另外也有一些非传统意义上的模型解释，例如manifold，tensorboard这类模型debugging工具，自动化的误差分析与模型改进方案，因果模型框架，模型公平性评估与纠正工具等，都可以涵盖在广义的模型解释领域中。在工具基础上，如何结合业务领域知识，给出更有针对性的解释方案，也是值得思考深挖的方向。

* 自我考核
  * 使用shap，eli5等工具来进行模型解释，并在此基础上形成面向开发者的模型debug，误差分析及改进方案，或形成面向业务的what-if分析看板。

## 总结

目前机器学习应用领域还在高速发展与演进过程中，除了上述提到的技能方向，后续很可能会不断有新的主题引入进来，需要练就快速学习并应用落地的能力。在掌握前面编程，软件工程，机器学习的基础上，后半部分的研究方向，大家可以根据个人兴趣，选择几个进行深入探索与实践。仅阅读相关书籍和文章，只能对知识内容有一个初步的认识，必须要通过深入的动手实践，反复试错思考和修正，才能逐渐内化为自己的技能，并构建起较为坚实的知识体系。

## 参考文献

* [AI-Job-Notes](https://github.com/amusi/AI-Job-Notes)
  * AI算法岗求职攻略：涵盖校招时间表、准备攻略、刷题指南、内推、AI公司清单和答疑等资料
  * AI算法岗方向：深度学习、机器学习、计算机视觉、自然语言处理、图像处理和SLAM等
* [mapattacker的博客](https://mapattacker.github.io/datascience/)
  * [数据科学](https://mapattacker.github.io/datascience/)
  * [AI工程师指导书](https://mapattacker.github.io/ai-engineer/)
  * [AI科学家指导书](https://mapattacker.github.io/ai-scientist/)
* [算法工程师从零到一](https://dongfengchi.github.io/algo\_engineer\_zero\_to\_one/)
  * 作者是字节跳动推荐算法工程师，介绍了行业背景，求职过程，算法日常工作等知识
* [AI算法工程师手册](https://www.huaxiaozhuan.com/)
  * 作者是阿里巴巴资深算法工程师，介绍了算法岗的数学基础、统计机器学习、深度学习及相关工具
* [2022 算法岗实习资料汇总](https://github.com/DeclK/algorithm-nju-sme)
  * 收集了面经、B站视频、面试资料、概率智力题、招聘公司官网等资料
* [awesome-algorithm-engineer](https://github.com/anorakj/awesome-algorithm-engineer)
* [目标推荐算法工程师，求推荐一条学习路线？ - Cv大法代码酱的回答 - 知乎](https://www.zhihu.com/question/287219861/answer/2451928435)
* [算法工程师技术路线图 - 字节的文章 - 知乎](https://zhuanlan.zhihu.com/p/192633890)
* [Datawhale人工智能培养方案](https://datawhale.feishu.cn/docs/doccn0AOicI3LJ8RwhY0cuDPSOc)
* [圆圆干货算法笔记（持续更新）](https://www.yuque.com/docs/share/84cc1c03-d671-4c6b-a6a0-084310f5ba0b?)
* [算法岗&秋招&实习 实际情况与需求 - HelloWorld的文章 - 知乎](https://zhuanlan.zhihu.com/p/569854146)
