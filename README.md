2020.4.29  
基于 eriklindernoren/PyTorch-YOLOv3 修改的  
vedio基于opencv绘制 因为在修改原来的开源项目时 PIL数组和cv2数组通道顺序不一样，训练时没有修改，最后在显示图像的时候就要像转换格式，效率变低  
根据Issues修改了Model的变量类型警告  
根据opencv绘制了新的detect.py文件  
注释掉train.py的模型最终的评测部分 可能会引发bug，还没想好怎么改  
  
