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
> - 利用A-Fast-RCNN框架和VGG16模型进行训练，保存两种数据的模型
> - 分别导出两个模型的倒数第二个全连接层数据，进行迁移训练，提高图像识别的mAP

- 项目成果预览
![遥感飞机图像识别](Image/remotePlane.png)

# 文本属性及关系标注
- 操作系统
> Windows

- 开源技术应用
> Window Builder

- 涉及编程语言
> Java

- 项目开发内容
> - 采用Window Builder开发程序的交互界面
> - 采用FTP协议和C/S结构实现在线标注的功能，便于实时提交任务
> - 可根据不同类型的文本，提前设置不同的配置文件并加载，可动态生成标注选项
> - 参考brat标注工具的输入输出文件，统一输入输出流格式
> - 添加快捷按键选项，实现快速文本标注

- 项目成果预览
![文本属性及关系标注](Image/textAnnotation.png)
