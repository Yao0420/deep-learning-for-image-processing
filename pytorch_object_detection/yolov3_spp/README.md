## 代码完善中...
* 将自己数据集中的图像大小缩放到与coco数据集一致(图像预处理算法决定的)
* 测试图像时最好将图像缩放到32的倍数

* 数据集的目录结构如下:
```
├── my_yolo_dataset 自定义数据集根目录
│         ├── train   训练集目录
│         │     ├── images  训练集图像目录
│         │     └── labels  训练集标签目录 
│         └── eval    验证集目录
│               ├── images  验证集图像目录
│               └── labels  验证集标签目录            
```