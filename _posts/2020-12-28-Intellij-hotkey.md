---
layout: post
title: "intellij 的常用快捷键"
categories: IDE
---

## 编辑

Ctrl + Y 删除光标所在行 或 删除选中的行      
Ctrl + X 剪切光标所在行 或 剪切选择内容     
Ctrl + C 复制光标所在行 或 复制选择内容     
Ctrl + D 复制光标所在行 或 复制选择内容，并把复制内容插入光标位置下面   

Ctrl + P 方法参数提示显示   

Shift + Enter 开始新一行。光标所在行下空出一行，光标定位到新行位置      

Ctrl + O 选择可重写的方法       
Ctrl + I 选择可继承的方法           
Ctrl + + 展开代码       
Ctrl + - 折叠代码           
Ctrl + Shift + +  展开所有代码          
Ctrl + Shift + -   折叠所有代码         
Ctrl + /  行注释        
Ctrl + Shift + / 块注释         

Alt + Enter IntelliJ IDEA 根据光标所在问题，提供快速修复选择，光标放在的位置不同提示的结果也不同        
Alt + Insert 代码自动生成，如生成对象的 set / get 方法，构造函数，toString() 等         

Ctrl + Shift + B 跳转到类型声明处           
Ctrl + Shift + I 快速查看光标所在的方法 或 类的定义             

Shift + F2 跳转到上一个高亮错误 或 警告位置            
F2 跳转到下一个高亮错误 或 警告位置             

## 调试

Shift + F9: Debug       
Shift + F10:  Run       
Alt + F8: 在 Debug 的状态下，选中对象，弹出可输入计算表达式调试框，查看该输入内容的调试结果     
F7 : 在 Debug 模式下，进入下一步(逐过程)        
F8 : 在 Debug 模式下，进入下一步(逐语句)        
Shift + F8: 跳出当前函数        
F9 : 在 Debug 模式下，恢复程序运行，但是如果该断点下面代码还有断点则停在下一个断点上        

## 版本控制

Ctrl + K 版本控制提交项目，需要此项目有加入到版本控制才可用     
Ctrl + T 版本控制更新项目，需要此项目有加入到版本控制才可用     
Alt + ` 显示版本控制常用操作菜单弹出层      

## 其他

Ctrl + Shift + C 复制当前文件磁盘路径到剪贴板       
Shift + F6 对文件 / 文件夹 重命名       

Ctrl + Shift + F 根据输入内容查找整个项目 或 指定目录内文件     
Ctrl + Shift + R 根据输入内容替换对应内容，范围为整个项目 或 指定目录内文件     
Ctrl + F 在当前文件进行文本查找         
Ctrl + R 在当前文件进行文本替换     
Ctrl + N 根据输入的 名/类名 查找类文件      
Shift + F3 在查找模式下，查找匹配上一个     
F3 在查找模式下，定位到下一个匹配处     

Ctrl + G 在当前文件跳转到指定行处       
Ctrl + Alt + L 格式化代码，可以对当前文件和整个包目录使用       

Ctrl + U 前往当前光标所在的方法的父类的方法 / 接口定义      
Ctrl + B 跳转到引用处，等效于 Ctrl + 左键单击       

连按两次Shift 弹出 Search Everywhere 弹出层     

## 声明

本文档摘抄自 https://zhuanlan.zhihu.com/p/61690346 , 结合目前工作中用到的进行修改.

