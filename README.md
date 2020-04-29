# FacialMotionCapture_v2

## Download trained model (lbfmodel.yaml)
https://github.com/kurnianggoro/GSOC2017/tree/master/data

# Install prerequisites:

## Linux:
(may vary between distro's and installation methods) <br/>
This is for manjaro with Blender installed from the package manager
- python3 -m ensurepip
- python3 -m pip install --upgrade pip --user
- python3 -m pip install opencv-contrib-python numpy --user

## MacOS
open the Terminal
- cd /Applications/Blender.app/Contents/Resources/2.81/python/bin
- ./python3.7m -m ensurepip
- ./python3.7m -m pip install --upgrade pip --user
- ./python3.7m -m pip install opencv-contrib-python numpy --user

## Windows:
Open Command Prompt as Administrator
- cd "C:\Program Files\Blender Foundation\Blender 2.81\2.81\python\bin"
- python -m pip install --upgrade pip
- python -m pip install opencv-contrib-python numpy

## Test Facial Capture
You can use the Test.py script to test facial motion capture.  <br/>
Open the script and change the folder for lbfmodel.yaml to the folder that you downloaded it to.

Then run "python3 Test.py"

### blender自带一个python 这里需要切换到那个目录去安装需要的库
### 绑定的模型下载地址 https://cloud.blender.org
### https://cloud.blender.org/p/characters/5718a967c379cf04929a4247
### 报错一般是检测文件的路径没写对

https://www.bilibili.com/video/av967630536/

b站的宣传教程
