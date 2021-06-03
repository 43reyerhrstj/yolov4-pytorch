
### 源代码地址：https://github.com/bubbliiiing/yolov4-pytorch

# 第一步：
    将图片和xml文件放入VOC2007文件夹中对应的目录

# 第二步：
    执行list.py文件生成txt
    
# 第三步：
    修改voc.py中的类别为自己的类别文件，执行voc.py生成train.txt文件
  
# 第四步：
    执行keans.py生成ahchor文件
    修改model_data里面voc的类别中的类别标签为自己类别
    
# 第五步：
    修改train.py加载权重文件和训练文件的路径，并且根据是否有显卡设置Ture或者False
    执行脚本开始训练
   
# 第六步：
    修改yolo.py文件中自己的图片路径加载和模型加载路径测试模型输出结果
    
  ![](https://github.com/Eric3911/yolov4-pytorch/blob/main/epoch_loss_2021_06_01_10_40_06.png)
  ![](https://github.com/Eric3911/yolov4-pytorch/blob/main/result.jpg)
