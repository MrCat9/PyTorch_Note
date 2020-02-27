# PyTorch_Note

https://pytorch.org/

https://github.com/pytorch

https://github.com/pytorch/examples

https://github.com/pytorch/tutorials

https://github.com/pytorch/vision

https://github.com/pytorch/text

## 目录

#### 1_DataLoader和Dataset 

Pytorch（五）入门：DataLoader 和 Dataset https://blog.csdn.net/zw__chen/article/details/82806900

#### 2_将文件夹中的图片转为dataset

pytorch Dataset 的ImageFolder https://blog.csdn.net/TH_NUM/article/details/80877435

#### 3_backward()函数

backward()函数 https://blog.csdn.net/huyaoyu/article/details/81059315

#### 4_optimizer.step()和scheduler.step()

optimizer.step()和loss.backward()和scheduler.step()的关系与区别 https://blog.csdn.net/xiaoxifei/article/details/87797935

optimizer.step()和scheduler.step() https://blog.csdn.net/qq_20622615/article/details/83150963

#### 5_torchvision的transforms

```
图像变换，图像处理
```

transforms的二十二个方法 https://blog.csdn.net/qq_38410428/article/details/94719553
```
裁剪（Crop）—— 中心裁剪：transforms.CenterCrop 随机裁剪：transforms.RandomCrop 随机长宽比裁剪：transforms.RandomResizedCrop 上下左右中心裁剪：transforms.FiveCrop 上下左右中心裁剪后翻转，transforms.TenCrop

翻转和旋转（Flip and Rotation） ——依概率p水平翻转：transforms.RandomHorizontalFlip(p=0.5) 依概率p垂直翻转：transforms.RandomVerticalFlip(p=0.5) 随机旋转：transforms.RandomRotation

图像变换（resize） ——transforms.Resize 标准化：transforms.Normalize 转为tensor，并归一化至[0-1]：transforms.ToTensor 填充：transforms.Pad 修改亮度、对比度和饱和度：transforms.ColorJitter 转灰度图：transforms.Grayscale 线性变换：
transforms.LinearTransformation() 仿射变换：transforms.RandomAffine 依概率p转为灰度图：transforms.RandomGrayscale 将数据转换为PILImage：transforms.ToPILImage transforms.Lambda：Apply a user-defined lambda as a transform.

对transforms操作，使数据增强更灵活 transforms.RandomChoice(transforms)， 从给定的一系列transforms中选一个进行操作 transforms.RandomApply(transforms, p=0.5)，给一个transform加上概率，依概率进行操作 transforms.RandomOrder，将transforms中的操作随机打乱
```

transforms用法介绍 https://www.jianshu.com/p/1ae863c1e66d

mnist手写体数据集里的标准化参数transforms.Normalize((0.1307,), (0.3081,)) https://blog.csdn.net/u014453898/article/details/90700904

#### 6_划分数据集(random_split)

Pytorch划分数据集的方法 https://www.cnblogs.com/marsggbo/p/10496696.html

#### 7_模型保存与加载

https://blog.csdn.net/LXYTSOS/article/details/90639524

https://blog.csdn.net/lscelory/article/details/81482586


