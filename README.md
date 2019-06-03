# 基于U-Net的眼底图像血管分割
## 实验目的 
对眼底图像中的血管进行分割，保证最大限度的分割出眼部的血管，以便更好好的对眼部血管进行检测、分类等 
## 数据集 
数据集名称 | 血管标注数量 | 分辨率 | 数据集划分
:---------: | :---------: | :---------: | :---------: |
DRIVE | 40 | 565*584 | train:test=1:1 |

<br><br><b>数据集下载：http://www.isi.uu.nl/Research/Databases/DRIVE/
<br>百度网盘数据集下载：https://pan.baidu.com/s/1UpQtbhgtVdlqc0QGbESx3A 密码：4l7v
## 数据集简介
眼底图像  
<img src="https://github.com/yuanxing-syy/U-Net_for_fundus_image_segmentation/raw/master/src_images/眼底图像.png" width="60%" height="60%"></img>  
血管图像     
<img src="https://github.com/yuanxing-syy/U-Net_for_fundus_image_segmentation/raw/master/src_images/血管图像.png" width="60%" height="60%"></img>  
## 模型结构 
<img src="https://github.com/yuanxing-syy/U-Net_for_fundus_image_segmentation/raw/master/src_images/U-net.png" width="50%" height="50%"></img>  

## 数据预处理 
直方图均衡化，数据标准化，并且压缩像素值到0-1，将其的一个数据符合标准正态分布  
## 实验结果   
<img src="https://github.com/yuanxing-syy/U-Net_for_fundus_image_segmentation/raw/master/src_images/实验结果.png" width="60%" height="60%"></img> 
## 参考资料  
U-Net: Convolutional Networks for Biomedical Image Segmentation MICCAI 2015  
## 安装依赖
numpy >= 1.11.1  
keras >= 2.1.0  
PIL >=1.1.7  
opencv >=2.4.10  
h5py >=2.6.0  
configparser >=3.5.0b2  
scikit-learn >= 0.17.1  