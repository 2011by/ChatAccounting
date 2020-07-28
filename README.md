#  多人协作开发注意事项



## 1. 开发与提交流程

### 1.1 拉取代码

可以直接通过微信开发者工具从远程仓库拉取代码，点击右上角`版本管理`，进入版本管理页面后，点击左上角`拉取`按钮进行代码拉取。每次提交之前需要拉取代码。

![](https://img.sunxiaochuan258.com/20200712085406.png)

### 1.2 提交代码

在`工作区`中勾选需要提交的更改，填写标题，点击提交，此时更改已经提交到本地仓库。

![](https://img.sunxiaochuan258.com/20200712085642.png)

随后点击右上角`终端打开`，键入：(以`origin master`为例)

```git
push -u origin master
```

若成功，此时更改已提交到远程仓库。



## 2. 协作原则

- 每个人只在自己负责的模块作更改。
- 公共区域文件由主页负责人更改。
- 遇到任何问题，在群里说一声即可，或者提交一个工单(issue)。
