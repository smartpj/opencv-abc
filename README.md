## OpenCV学ぶ

特徴量マッチングは、 基本的な方法とそれの高速版があるという流れ。 基本的な方法は、OpenCVでAPIになっています。

- 画像処理[6] 

- 特徴抽出[3] 

- 物体認識[3] 

- パノラマ[3]

合計:[15]

OpenCVをつかって、特徴量計算、物体マッチング、座標計算、 という流れが身につきます。



## OpenCVとは？

OpenCV是一个用于图像处理、分析、机器视觉方面的开源函数库. 

OpenCV的全称，是Open source Computer Vision Library,开放源代码计算机视觉库。也就是说，它是一套关于计算机视觉的开放源代码的API函数库。

它的一个目标是提供友好的机器视觉接口函数，从而使得复杂的机器视觉产品可以加速面世。该库包含了横跨工业产品检测、医学图像处理、安防、用户界面、摄像头标定、三维成像、机器视觉等领域的超过500个接口函数



## 计算机视觉概念/画像認識概念

图像处理和计算机视觉の概念：

图像处理实际上就是数字图像处理，是把真实世界中的连续三维随机信号投影到传感器的二维平面上，采样并量化后得到二维矩阵。数字图像处理就是二维矩阵的处理，而从二维图像中恢复出三维场景就是计算机视觉的主要任务之一。

图像处理所涉及到的三个重要属性：连续性，二维矩阵，随机性。

数学知识：连续性▶高等数学（微积分），二维矩阵▶线性代数（矩阵论），随机性▶概率论和随机过程。



## 深度学习概念

传统机器学习：

经验数据存储 以特征（feature）形式存储的数据（data）

机器学习算法依靠这些数据来产生模型（model）

局限：

人们对于特征的定义会限制最终任务性能的天花板。

改善：

特征的学习交由机器自动完成 ▶ 表示学习（represention learning） ▶提高任务的最终性能 ▶可复用 

深度学习便是表示学习的一个代表。

<img src="/Users/leo/Dropbox/note/gitbook/OpenCV-ABC/img/image-20200425221252909.png" alt="image-20200425221252909" style="zoom:33%;" />

深度学习： 原始数据（raw data）输入 ▶ 算法抽象 逐层抽象成任务所需要的特征 ▶ 特征和任务目标的映射（mapping）

**传统机器学习 任务模块模型学习** 

**深度学习 特征学习，特征抽象，模型学习 借助多层任务模块完成最终学习任务。故称为“深度”**

<img src="/Users/leo/Dropbox/note/gitbook/OpenCV-ABC/img/image-20200425173633756.png" alt="image-20200425173633756" style="zoom: 33%;" />

深度学习一类代表算法是神经网络算法

**神经网络算法**

- **深度置信网络（deep belief network）**
- **递归神经网络（recurrent neural netwark）**
- **卷积神经网络（Convolution Neural Network）CNN**

卷积神经网络优势在计算机视觉，自然语言处理，医学图像处理方面。

实验结果表明神经网络模型相对于传统机器学习的**预测能力**突出。

2011年开始进入了深度学习（deep learning）的时代。

deep的含义是人们现在已经训练和掌握了层数更多的网络模型。

**有效数据的极速扩增**，**高性能计算硬件的实现**和**训练方法的大幅改善**，三者作用促成了神经网络的第三次复兴。 ▶产业成产力提升。

它使研究者或者工程师摆脱了复杂的特征工程，从而可以专注于解决更加宏观的关键问题。



## 深度学习开源工具简介

### 常用框架对比

![image-20200425231501189](/Users/leo/Dropbox/note/gitbook/OpenCV-ABC/img/image-20200425231501189.png)

![image-20200425231600154](/Users/leo/Dropbox/note/gitbook/OpenCV-ABC/img/image-20200425231600154.png)****



## 中文书籍

OpenCV 4计算机视觉项目实战（原书第2版）

深度学习实践：计算机视觉

解析卷积神经网络-深度学习实践手册

[画像処理100本ノック](https://github.com/gzr2017/ImageProcessing100Wen)

[OpenCV-Python图像处理教程](https://github.com/ex2tron/OpenCV-Python-Tutorial)
