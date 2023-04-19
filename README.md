#### ii.纯净部署

##### 1.优缺点

相比于整合包，自己部署可以对了解一个工具的全貌更有帮助，但缺点是需要硬件支持硬性需求是显卡n卡且显存在8g以上，内存16g以上，而a卡也不是不能用但效率很低不如云端部署，并且需要接触少量代码以及一些奇怪的bug比较劝退新人。

##### 2.准备工作

首先如果是n卡你需要准备以下几个东西

[CUDA ](https://developer.nvidia.com/cuda-downloads)

安装时一直下一步就行

[Git ](https://git-scm.com/downloads)

下载Standalone Installer下的程序，安装时注意更改安装目录，后面一直下一步

[Python Release Python 3.10.6 | Python.org](https://www.python.org/downloads/release/python-3106/)

下载Windows installer (64-bit)

安装时注意勾选add python.exe to PATH(如果忘记勾选可在环境变量里添加)，选择自定义安装更改安装路径



因为本人没有a卡，如果你是a卡可以看以下视频教程

[【AI绘画】AMD显卡利用ONNX玩转Stable Diffusion_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1WM4y1d7Tx/?vd_source=3ce927ad4d409debb889ffe5fe6ef47a)

###### webui

webui官方地址[AUTOMATIC1111/stable-diffusion-webui: Stable Diffusion web UI (github.com)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

（如果无法打开这个网站，可能是网络环境不太好，需要科学上网请自行百度实际使用方法）

在一个文件夹里如：D:\sd

在路径栏里输入cmd

![](https://github.com/slk214/stable-diffusion-/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-18%20232151.png)

在弹出的cmd里输入git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git

（如果出现“fatal: unable to access 'https://github.com/AUTOMATIC1111/stable-diffusion-webui.git/': Recv failure: Connection was reset”请将科学上网软件改为全局）

下载完成后双击webui-user.bat

![](https://github.com/slk214/stable-diffusion-/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-18%20225012.png)

开始下载并安装一些环境文件和sd模型等等。。。

![](https://github.com/slk214/stable-diffusion-/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-18%20224955.png)

![](https://github.com/slk214/stable-diffusion-/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-18%20230008.png)

经过漫长的等待当你看到这个你就成功了！

![](https://github.com/slk214/stable-diffusion-/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-18%20231040.png)

赶紧将红圈里的地址复制到浏览器里打开试试吧。
