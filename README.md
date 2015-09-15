# 动态自动适配按钮

这个插件主要是做按钮。输入多少，图标就在自动撑开，免得调过来跳过去的。

## 更新日志 
[即将发布] Version 2.0
- [增加] 一些吸引人的功能
  
Version 1.2:

- [增加] 支持 Sketch 3.2
- [增加] 可以同时选中多个图层并把他们转化为按钮或一键更新

Version 1.1:

- [增加] 支持 Sketch >= 3.0.2
- [增加] 增加支持css圆角的写法 (10:10, 10:10:10, 10:10:10:10)
- [增加] 操作反馈 ('啥都没选', '错误类型')


## 案例

[![Demo Video](https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/thumb.png)](http://www.youtube.com/watch?v=ZJCYUCU7YxQ)

## 安装
1. [下载插件安装包](https://github.com/sketchplugins/sketch-dynamic-button/archive/master.zip)
2. 双击安装文件，sketch将会提示你安装成功。.
  <img src="https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/success.png" alt="installed" width="534" />
3. 在菜单项中，你也会见到相关的提示. 
 
  <img src="https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/dropdown.png"/>


## 如何使用
你可以像下面的示意图一样，创建一个图层,然后点击插件.也可以创建一个文本图层，然后用快捷键 `Cmd + J`. 使用后，你会发现一个组命名为 "flexible button" ,图层是名为 (0:0:0:0) ，背景名为 ('BG').

<img src="https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/2step.png"/>

0:0:0:0 代表的内间距.这个语法规则和CSS一样.

*比如. 
内间距: 10px 20px 10px 20px (分别代表: 上 右 底 左)
10:20:10:20 (top:right:bottom:left)*

做你想要的内间距 (在图层命名中),选中图层并点击 `Cmd + J`.

<img src="https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/3step.png"/>

如果你修改文本并再次按下 `Cmd + J`.按钮会自动调整.

<img src="https://dl.dropboxusercontent.com/u/1909742/sketch-plugin/4step.png"/>

## 修改快捷键

1. 通过点击菜单，你可以快速的打开安装目录, 点击设置图表按钮并选中"Open Plugins Folder".
2. 用文本或代码编辑器打开 "Dynamic Button.sketchplugin" 文件
3. 快捷键卸载第一行，修改即可:

    ```
    // just a comment (cmd j)
    ```
    
    
[脚本参考](http://bohemiancoding.com/sketch/scripting/)







