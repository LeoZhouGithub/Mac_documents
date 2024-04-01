### git communite with github

*  https
* ssh

SSH pattern is recommended. 

https模式在使用过程中经常会遇到clone 不下来，或者push不上去。

使用SSH公钥和私钥对会使得操作过程很简单。

#### SSH公钥私钥配对方式

配对方式可以参照网络。B站

Tips：

* 公钥私钥位置放在～/.ssh 文件夹中
* 在命令行窗口 使用cat 命令读取的公钥 在输入github后，大概率会出错，建议打开原始文件夹对其中的内容进行复制。
* 公钥和私钥的概念目前还不清楚。之间的隐私性如何保护尚有待学习。
* git 的使用说明也已经包含在文件夹中。



#### 修改了文件，但是属于误修改，撤销修改命令

git checkout -- filename 

#### macOS新建文件，有推荐的插件，但是建议使用终端生成

touch +文件名 

