reportRl是个啥
-------------------------------------------------------------------------------------------------
reportRl是一个aardio的锐浪报表组件库。[gitee仓库](https://gitee.com/daheian/reportRl) [github仓库](https://github.com/drunkenOstrich/reportRl) 同步更新。  
本仓库包含了reportRl库源码，以及使用reportRl库调用Grid++Report锐浪报表组件的例程。  

目录说明
-------------------------------------------------------------------------------------------------
reportRl目录说明  
├─aardio　　　　　　　**aardio例程**文件夹  
│  ├─02.Normal　　　 Grid++Report 各种格式报表演示(看这个就对了)  
├─Data　　　　　　　　Grid++Report 自带的数据目录  
├─img  
├─lib  
│  └─reportRl　　　　**reportRl库源码**，已制作成[远程扩展库](https://github.com/drunkenOstrich/reportRl/releases/latest)  
└─Reports　　　　　　Grid++Report 自带的报表模板目录  

食用方法
-------------------------------------------------------------------------------------------------
1，在电脑上安装[aardio桌面快速开发编程工具](http://www.aardio.com)；  
2，下载reportRl仓库；  
3，(此步骤可省略) 把reportRl\lib\目录里的reportRl文件夹(**reportRl库源码**) 拷贝(复制-粘贴)到aardio开发工具**根目录**的/lib/ 目录下；  

4，打开`reportRl仓库\aardio\02.Normal\`文件夹观看示例工程。  


组件对象的智能提示并不全，有用到的才会去写一下，还是要以锐浪报表的帮助文档为主要参考依据。  

锐浪的帮助文档在`reportRl\lib\reportRl\.dll`里  

（注：该例程用于练习在aardio中调用Com组件，例程中有什么不对的地方欢迎大家指正交流。）  

远程引用扩展库
-------------------------------------------------------------------------------------------------
在aardio引用[远程扩展库reportRl](https://github.com/drunkenOstrich/reportRl/releases/latest)的示例：  
```
_IMPORTURL["reportRl"] = "https://github.com/drunkenOstrich/reportRl/releases/latest/download/reportRl.tar.lzma"
import reportRl
```
在需要使用reportRl库的工程中，包含以上两句代码即可自动下载本扩展库。  


免注册发布工程
-------------------------------------------------------------------------------------------------
免注册发布工程建议使用[Grid++Report](http://www.rubylong.cn/)锐浪报表6.6.6.2之后的版本  
Manifest文件的修改已经集成到库里，直接发布工程，生成的exe可以在任何windows电脑上免注册使用。

联系方式
-------------------------------------------------------------------------------------------------
QQ:838326505  
aardio编程交流QQ群：70517368(非aardio官方群)  

截个图
-------------------------------------------------------------------------------------------------
![Normal](/img/img.png)