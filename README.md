# Tool-installation

Download address of various tools

## 一、spyder

1.下载spyder ide，网址如下：

https://bitbucket.org/spyder-ide/spyderlib/downloads/

进行正常的安装即可，没有什么特别需要注意的地方；

2.安装后，运行桌面的快捷方式，发现报错，错误如下：
![error](https://github.com/H-YMing/Tool-installation/blob/master/image/1.png)

这是因为没有安装必需的PyQt4 4.6以上版本

解决方法：下载相应版本的PyQt4，地址如下：

http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqt4

3.下载后，用cmd命令进入到下载目录下，运行命令：

pip intall PyQt4-4.11.4-cp27-cp27m-win_amd64.whl

![cmd](https://github.com/H-YMing/Tool-installation/blob/master/image/2.png)

这里需要注意，如果你是第一次安装whl文件，首先需要使用命令：

pip install wheel

![cmd](https://github.com/H-YMing/Tool-installation/blob/master/image/3.png)

而后，打开spyder不报错，即可正常使用。
