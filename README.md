# CG_SpeedStart
You can download it for your games101 in vscode

图形学框架搭建最速传说(vscode+opencv+eigen+c++)

# 摘要：
	四种文件：
	 1.mingw64库
	 2.opencv库
	 3.eigen库
	 4.vscode环境
# 三个path:
	 1.C:\mingw64\bin
	 2.C:\opencv\build\x64\mingw\bin
	 3.C:\opencv\build\x64\vc15\bin

# 前言：
	本教程是在Games101的学习中总结的，一开始踩了许多坑。献给正在学习，有需要的朋友。
	

# 准备工作：
	1.vscode和扩展内的c++插件(up的vc++2005-2022全部安装，VisualStudio的.net和c++相关组件也进行了安装，如若仍然报错，请自查或评论区讨论)
	2.下载搭建包

# 开始搭建：
	1.将mingw64库、opencv库、eigen库放在C盘根目录
	2.向环境变量->系统变量path添加如下参数
		C:\mingw64\bin
		C:\opencv\build\x64\mingw\bin
		C:\opencv\build\x64\vc15\bin
	3.cmd->g++ -v验证是否正确
	4.将.vscode放在项目目录下，新建Debugger文件夹
	5.小作业验证，搭建完成

# 补充总结：
	1.“.vscode"的四个文件可以手动生成，mingw64要下linux版(posix-seh)，opencv的编译失败可能由于网络原因导致的文件下载失败(编译过程中会下载文件)。
	2.c_cpp_properties和tasks里更改文件目录，launch里可以改exe生成文件夹(Debugger)
	3.有耐心的可以去看这位up的视频，非常详细到位，这些文件也是基于他的教程 BV1vM4y1U724






