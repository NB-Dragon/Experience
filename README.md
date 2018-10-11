# 遥感飞机图像识别
- 操作系统
> Ubuntu 16.04 LTS

- 开源技术应用
> A-Fast-RCNN/Caffe/OpenCV

- 涉及编程语言
> Matlab/Python

- 项目开发内容
> - 采用Selective Search算法生成飞机图像训练集和测试集
> - 采用Selective Search算法生成场景图像训练集和测试集
> - 利用A-Fast-RCNN进行训练，保存两种数据的模型
> - 分别导出模型的倒数第二个全连接层数据，进行迁移训练，提高图像识别的mAP

- 项目成果预览
![遥感飞机图像识别](Image\remotePlane.png)
