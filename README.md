# openpose
openpose ,caffe, pytorch

#  pytorch 版 openpose

python demo.py

![image](./pytorch_openpose/images/2.png)
![image](./pytorch_openpose/images/2_keypoint.png)

#  caffe c++ 版 openpose 的安装
参考： caffe_openpose/openpose_setup.md   感谢其他作者的开源代码
注意事项：
* models.rar 和 window.rar 解压到3dpart下，远程下载不了。网盘下载：链接: https://pan.baidu.com/s/1-TbFZwPOy8pniZo59L1TTQ 提取码: yfcj  

* cmake后使用vs打开，如果是debug版，会提示缺少相关debug库，将release对应版复制一份，改名为debug版对应名称即可。
* python调用时，记得将openpose.dll复制的pyopenpose的目标路径下，否则调用时提示找不到对应的moudle

Have a nice day!