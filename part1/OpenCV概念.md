> `2020/04/27新規`

## 计算机视觉

计算机视觉可以被定义为一个学科，解释如何根据场景中存在的结构的属性，从其2D图像重构，中断和理解3D场景。 它使用计算机软件和硬件处理建模和复制人类视觉。

### **计算机视觉与图像处理**

图像处理涉及图像到图像的转换。 图像处理的输入和输出都是图像。

计算机视觉是从物体形象中对物理物体进行**明确而有意义的描述**。 计算机视觉的输出是对3D场景中结构的描述或解释。



## OpenCVとは

### 定義

OpenCV是一个跨平台的库，使用它我们可以开发实时的计算机视觉应用程序。 它主要集中在图像处理，视频采集和分析，包括人脸检测和物体检测等功能。

### OpenCV库的特点

使用OpenCV库，可以 

- 读取和写入图像
- 捕获并保存视频
- 过程图像(过滤，变换)
- 执行功能检测
- 检测视频或图像中的特定对象，例如脸部，眼睛，汽车。
- 分析视频，即估计其中的运动，减去背景，并跟踪其中的对象。

### OpenCV库模块

- 核心功能

  该模块涵盖了用于构建OpenCV应用程序的基本数据结构，如标量，点，范围等。 除此之外，还包括用于存储图像的多维数组`Mat`。 在OpenCV的Java库中，这个模块包含在一个名字为`org.opencv.core`的包内。

- 图像处理

  该模块涵盖了各种图像处理操作，如图像过滤，几何图像转换，颜色空间转换，直方图等。在OpenCV的Java库中，该模块包含在一个名称为org.opencv.imgproc的包内。

- 视频

  本模块涵盖了运动估测，背景扣除和对象跟踪等视频分析概念。 在OpenCV的Java库中，这个模块包含在一个名字为`org.opencv.video`的包内。

- 视频I/O

  本模块解释了使用OpenCV库的视频捕获和视频编解码器。 在OpenCV的Java库中，该模块由名称为`org.opencv.videoio`的包提供。

- calib3d

  该模块包括有关基本多视图几何算法，单个和立体摄像机标定，对象姿态估计，立体对应和三维重建元素的算法。 在OpenCV的Java库中，该模块由名称为`org.opencv.calib3d`的软件包提供。

- features2d

  该模块包含特征检测和描述的概念。 在OpenCV的Java库中，该模块由名称`org.opencv.features2d`的包提供。

- Objdetect

  该模块包括检测对象和预定义类的实例，例如面孔，眼睛，杯子，人物，汽车等。在OpenCV的Java库中，该模块由名称为`org.opencv.objdetect`的包提供。

- Highgui

  这是一个易于使用的界面，具有简单的UI功能。 在OpenCV的Java库中，这个模块的功能包含在两个不同的包中，即`org.opencv.imgcodecs`和`org.opencv.videoio`。

