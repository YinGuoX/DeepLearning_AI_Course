## TensorFlow2.0实践系列课程
## 1.代码对应的数据集

Course1和Course2和Exercise的数据集
***
链接：https://pan.baidu.com/s/1gSyvfZVnOxXTeMpEcRlB2A 
提取码：0cit 
## 2. Course1代码内容
* Part1：
  * 神经网络的Hello World：了解神经网络工作的大体思路
  * TensorFlow如何构建、编译、训练神经网络
* Part2:
  * 一个CV示例：使用标准的深度神经网络(DNN)识别不同的服装
  * 如何：导入数据、数据预处理、构建、编译、训练神经网络
* Part3:
  * 使用卷积神经网络(CNN)改进Part2的示例
  * 直觉上了解卷积层和池化层的作用
* Part4:
  * 探索卷积层如何工作
  * 卷积==滤波，通过不同的卷积核获得图像中不同的特征，从而获得更加精简有效的信息
  * 卷积核的获取也是通过CNN的不断训练得到
  * Part5:
  * 从头构建一个模型：识别区分人和马图片
  * 大体流程：导入数据、数据预处理、构建、编译、训练、预测、评估神经网络
## 3. Course2代码内容
* Part1:
  * 重新构建一个CNN模型：识别区分猫和狗
  * 分析样本数据、进行数据预处理，使用图片生成器(ImageDataGenerator)作为训练集与测试集数据，进而训练模型
* Part2：
  * 改进Part1模型，解决过拟合，欠拟合？
  * 使用图片生成器(ImageDataGenerator)来增强数据(通过翻转、平移等方式扩大数据集)
  * 使训练集的样本增多，进而改进模型
* Part3:
  * 使用数据增强的方式改进人马识别模型(Course1-Part5)
  * 使用ImageDataGenerator来增强数据
* Part4:
  * 迁移学习：现存的已经在很多数据上训练过的模型，从运用这些模型从中学习到特征，用于自己的项目。
  * 使用InceptionV3模型改进猫狗模型(Course3-Part1)
  * 选择InceptionV3模型中的某些层(不改变其之前训练得到的权重)，再添加一些自定义层(将重新训练获得权重)来重新构建一个模型，进而优化猫狗识别
* Part5:
  * 重新构建一个CNN模型：识别剪刀石头布
  * 使用：CNN、数据扩展
* Part6:
  * 通过Dropout正则化改进人马模型(Course2-Part3)
  * 解决模型过拟合，可以通过Dropout正则化
  
## Course3
Course3的代码是在Colab编写，因此最好在Colab上运行
