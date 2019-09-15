# Morn
Morn是一个C语言的基础工具和基础算法库，包括数据结构、图像处理、音频处理、机器学习等，具有简单、通用、高效的特点。

![logo](./doc/logo.PNG)

### 名称

Morn，名叫句芒（音“勾芒“），句芒，又叫芒神、芒童，是神话里的春神、木神、东方之神，主管日出的神（morn是英语早晨的意思），总之Morn是个挺厉害的，而且寓意挺好的神话人物。



### 愿景

Morn并不针对某一种或某一类应用，它是一个广泛涉及的基础算法库。

Morn致力于成为一个简单、通用、高效的C语言库。

* **简单**，Morn充分理解那些脑容量小，记忆力差，记不住繁琐API的码农（因为作者就是这么一个人），所以，简单是Morn的第一目标，风格统一、合理封装是Morn的特点，它所有的数据设计、函数设计都把“简单易用”作为首要任务。
* **通用**，Morn并不针对某一个平台开发，也不想成为某个平台下的算法库，它希望既能在Linux下运行，也能在Windows下运行，既能在x86/x64下运行，也能在Arm、MIPS 或者其它CPU下运行，既能在PC上运行，也能在服务器上运行，还能在终端设备上运行。
* **高效**，Morn的目标是速度不比人慢，资源占有不比人多。在简单、通用的前提下，它尽可能的进行了一些优化，对某些算法进行了一些简化。

当然，这是写Morn的愿景，Morn尽量的朝这个方向写，但并不表示Morn已经达成了此目标。



### 内容

Morn大体上包括以下一些内容。

* **数据结构**：包括各种容器、栈、队列、数组、表格、映射等，包括链表、树、二叉树等。
* **数学相关**：一些数学函数、排序、平面几何、向量、矩阵运算、矩阵文件读写等。
* **图像相关**：图像文件读写、缩放、颜色、滤波、锐化、变形、坐标变换、形态学处理、积分图、直方图、梯度、分割、霍夫线变换等等。
* **音频相关**：音频文件读写、音频波形的傅里叶变换、音频重采样、功率谱滤波，音频特征提取等。
* **机器学习**：暂空（虽然这块是最早写的，但现在还不太敢开源）。
* **深度学习**：一个轻量级的深度学习框架，包括各种卷积层、全连接层、池化层、BatchNomalize、噪声层、一些激活函数、一些损失函数等。
* **文件操作**：比如.ini文件、.json文件的解析、文件的加密解密、文件打包解包等。
* **其它内容**：诸如内存管理、内存检查、日志、异常处理、命令行参数解析等。

更多内容，详见./doc/文件夹下的文档。

Morn并不追求大而全，写这些算法仅仅是因为作者曾经用到过。还有更多的算法，也许明天会用到，那就明天写，也许永远也用不到，就永远也不写。



### 安装和编译

Morn使用Makefile和make工具来编译，具体另见文档。



### 开源协议

看LICENSE吧。



### 联系方式

jingweizhanghuai@163.com







