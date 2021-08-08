# C语言入门



## 为什么要学习C语言

* 结构化编程语言 —— 高级语言的基础模式
* 执行高效 —— 整个世界的基础都是C构建的
* 离硬件很“近” —— 接近异次元世界的边缘



## 前置知识

1. 会使用命令行检索文件和目录
1. 会使用Homebrew安装软件
1. 熟悉Sublime Text文本编辑器
1. 学习过《计算机科学导论》里的 “9. 程序设计语言”


## 高级语言到机器语言

![语言层次](/data/images/langs.png)



## 四步翻译C语言
![gcc](/data/images/gcc.png)



## 环境安装

#### I. 写代码 
<content>安装Sublime Text https://www.sublimetext.com/</content>

#### II. 编译代码
<content>安装GCC http://gcc.gnu.org/</content>
```bash
$ brew install gcc
```



## 第一个C语言程序

<div class="alert">假设代码在目录~/projects/proj-c目录，以下简称 $proj-c</div>

* I. 写代码(By Sublime) 在 $proj-c 目录下编辑 hello.c

>在 $proj-c 目录下编辑 hello.c
![](/data/images/hello-source.png)


* II. 翻译代码(By Terminal)
❶ 进入 $proj-c 目录
```bash
$ cd ~/projects/proj-c
```
❷ 编译 hello.c
```bash
$ gcc ./hello.c -o ./hello
```
生成文件 hello 到 $proj-c 目录下

![](/data/images/hello-compile.png)


* III. 运行代码(By Terminal) 
❸ 仍在 $proj-c 目录执行 hello
```
$ ./hello
```



## C语言结构解析
![](/data/images/c-analysis.png)



## 函数和库
![](/data/images/library.png)



## 第二个C语言程序

* 立即实践
<div class="content">写一个mycode.c文件，编译运行，使在控制台输出“欢迎来到半圆”。</div>