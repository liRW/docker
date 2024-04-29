# 更改软件源

pip安装软件包时，默认使用pip的官方源，在国内经常会出现因网络而导致的连接失败。解决方法是使用国内的镜像源，如阿里云。编辑pip的配置文件

```
* windows操作系统下的位置是%APPDATA%\pip\pip.ini
* linux操作系统下的位置是~/.pip/pip.conf
* macOS操作系统下的位置是~/.pip/pip.conf
默认情况下文件夹pip或.pip是不存在，需要自己手动创建。配置文件的内容为

[global]
index-url = http://mirrors.aliyun.com/pypi/simple/
trusted-host = mirrors.aliyun.com

```