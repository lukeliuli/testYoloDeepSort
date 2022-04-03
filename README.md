# testYoloDeepSort
测试YOLO和DeepSort
pytorch YOLO5+DEEPSORT  
1.下载miniconda安装，并建立 pytorch环境。注意python=3.7  

2.激活环境后，运行命令（重要）  

pip install torch==1.7.0+cu101 torchvision==0.8.1+cu101 torchaudio===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html  

https://zhuanlan.zhihu.com/p/378766432  

3.更新驱动  
http://www.nvidia.com/Download/index.aspx  

4.运行DEMO. 注意下载测试视频1.mp4,以及如果是CPU，把half()改为float() 
git clone  https://github.com/ultralytics/yolov5.git
git clone https://github.com/Sharpiless/Yolov5-Deepsort.git
pip install easydict
https://blog.csdn.net/m0_51931246/article/details/123536233  
