﻿========================================================================
    控制台应用程序：Win32Project1(C_AddressList project) 项目概述
========================================================================

本文件概要介绍组成 Win32Project1 应用程序的每个文件的内容。

Win32Project1.vcxproj
    这是使用应用程序向导生成的 VC++ 项目的主项目文件，其中包含生成该文件的 Visual C++ 的版本信息，以及有关使用应用程序向导选择的平台、配置和项目功能的信息。

Win32Project1.vcxproj.filters
    这是使用“应用程序向导”生成的 VC++ 项目筛选器文件。它包含有关项目文件与筛选器之间的关联信息。在 IDE 中，通过这种关联，在特定节点下以分组形式显示具有相似扩展名的文件。例如，“.cpp”文件与“源文件”筛选器关联。

Win32Project1.cpp
    这是主应用程序源文件。

/////////////////////////////////////////////////////////////////////////////
结合了外部数据库sqlite3，详细的API使用说明在：
http://www.sqlite.org/docs.html

/////////////////////////////////////////////////////////////////////////////
资源文件：

sqlite3.lib
sqlite3数据库所必须的静态库（有了静态库，最后生成的.exe文件便可在其他电脑直接运行，不再需要dll文件，因为我不知道你的电脑里有没有相应模块）

/////////////////////////////////////////////////////////////////////////////
其他标准文件:

StdAfx.h, StdAfx.cpp
    这些文件用于生成名为 Win32Project1.pch 的预编译头 (PCH) 文件和名为 StdAfx.obj 的预编译类型文件。

/////////////////////////////////////////////////////////////////////////////
其他说明：
比题目要求多增加了性别这一参数，觉得这是通讯录所必须的。。。如果不需要请删除。