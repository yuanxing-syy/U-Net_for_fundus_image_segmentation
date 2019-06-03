# 基于U-Net的眼底图像血管分割
## 实验目的 
对眼底图像中的血管进行分割，保证最大限度的分割出眼部的血管，以便更好好的对眼部血管进行检测、分类等 
## 数据集 
数据集名称 | 血管标注数量 | 分辨率 | 数据集划分
:---------: | :---------: | :---------: | :---------: |
DRIVE | 40 | 565*584 | train:test=1:1 |
来源：https://github.com/orobix/retina-unet
<br><br><b>数据集下载：http://www.isi.uu.nl/Research/Databases/DRIVE/
<br>百度网盘数据集下载：https://pan.baidu.com/s/1UpQtbhgtVdlqc0QGbESx3A 密码：4l7v
<br><br>有关代码内容讲解，<b>请参见CSDN博客</b>：
<br>基于UNet的眼底图像血管分割实例：https://blog.csdn.net/u013063099/article/details/79981097
<br><br><b>【注意】run_training.py与run_testing.py的实际作用为了让程序在后台运行，如果运行出现错误，可以运行src目录下的训练与预测文件。</b>