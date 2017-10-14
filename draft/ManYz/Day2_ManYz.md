##A Decade of Faces in the Wild

###Chapter 1: Elements of Face Rocognation System
#####A canonical pipeline:
1. From the input image, detect face 
2. Alignment
3. Feature Extration
4. Feature similarity

###Chapter 2:
In-plane alignment
2D alignment -> 3D alignment

#####How to get a 3D face shape
3D models don't make much differences

###Chapter 3: The Problem with Facial Landmarks
Vices:
1. Slow
2. Very sensitive to bounding boxes
3. Require special care to train and apply to frontal v.s. profile image

#####FacePoseNet: FPN
A simply AlexNet

**Where is the data?** ( To make the student better than his teacher)
1. Take 500k in CASIA
2. Run existing faces on traditional and get the landmarks
3. then transfrom the image with its corresponding landmarks to get the final input data

###Chapter 4:
For a well-trained trained model, a same person get a very much close vector, and vice versa.

More data -> more variability ?
inter-class variability is not enough, only 50 images per person, for 500 million images.

solve this by **data augmentation**:
We can do 3D augmentation.
- change the 3D models slightly
- wear fake sunglasses, etc.


##陈熙霖：计算机视觉的未来

未来的挑战与问题：
1. 超越计算机视力（视力、视觉和视觉智能）
2. 元视觉概念集
3. 从任务驱动走向事件、数据驱动
  - 场景图(Scene Gragh)
  - 知识图

视觉物体是高维空间的点，可以使用欧氏距离作为相关性

对事实的描述：
- 描述物体间的空间关系
- 对物理知识的理解

####一些尝试：

1. Dual Purpose Hashing (类别 + 属性)
  相似和类别：类别的相似和表现的相似。
  两种标签：
- 类别标签：
- 属性标签：

门控比特控制的损失函数：应对属性不全的情况

图像扩展至视频，BBT和PB

结果的获得是有语义支持的 

####如何识别未知类别的属性描述 (零样本学习)
隐属性：自动挖掘属性间的关系


想着讲 vs. 抢着讲 
吃了没有知识的苦，构建知识数据库

未来的方向：
- 超越视力
- 超越桌面的



##医学图像Forum
####浙大孔教授
- 数理医学
- 精准诊疗

####西工大教授



