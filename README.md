# Python创建虚拟环境的两种方法

## 目录

### 1.使用指令创建

### 2.使用`pycharm`创建



## 1.使用指令创建

### 1.1安装第三方库，用于创建虚拟环境

```sh
pip install virtualenv
```

速度慢的同学可以使用清华园镜像安装：

```
pip install virtualenv -i https://pypi.python.org/simple/
```

### 1.2创建虚拟环境

这里以桌面为路径进行创建

#### 1.2.1在桌面上按住`shift`键并单击鼠标右键，启动`cmd`命令行。

```
virtualenv env
```

这样在桌面就会多出env为文件名的文件夹，这个即是虚拟环境文件夹。

#### 1.2.2cd到Script文件夹中，输入指令`activate.bat`，激活虚拟环境

这时在命令行中会多出(env)字样，表示当前虚拟环境已激活。



## 2.使用Pycharm创建

点击文件——>新建项目，根据提示即可自主创建虚拟环境。

![image-20210630145540941](C:\Users\jiuye\AppData\Roaming\Typora\typora-user-images\image-20210630145540941.png)

不继承全局站点包将意味着当前虚拟环境是“最干净的”，没有任何的第三方库，仅含有标准库。
