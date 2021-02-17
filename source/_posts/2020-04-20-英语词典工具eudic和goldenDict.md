---
title: 英语词典工具Eudic和GoldenDict
date: 2020-04-20 13:51:43
description: 介绍好用的英语词典工具，Eudic以及GoldenDict。
mathjax: false
tags: [英语词典工具,Eudic,GoldenDict]
categories:
- 工具
- 英语
---

## 前言

所谓工欲善其事，必先利其器。想要学习英语，或者想要深入了解下英语，一本词典是必要的，以前是书本，现在是软件。

英语词典类软件或网站还是挺多的，比如有道、金山、百度翻译、谷歌翻译等。嗯，如果你仅仅只是想要知道某个单词的意思或者句子的大概意思，其实上述任何一个都可以满足你，但是，我不满足，因为我想要更多的了解某个单词的内容，也就是像是拿着一本英语词典一样，而且最好是能同时看到好几种词典给出的解释，例子等。

然后我在网上搜索了一番，决定在android上使用Eudic（欧路词典），在windows上使用GoldenDict。有人可能想问，为啥不统一一下软件呢，这样就能同步数据之类的。额，这个就涉及到钱的问题了，在android上Eudic是可以添加多个本地词典，无限制，但是在windows上只能添加两个本地词典，想要更近一步，需要购买专业版。所以就需要找一个在windows上可以使用的软件，然后就选中了goldenDict。

贴个Eudic在windows上使用的截图：

![Eudic-Windows](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-Windows.png)



## Eudic 使用

### Eudic的优点（个人感觉）：

- Eudic支持的平台有android、iPhone、iPad、Windows、Mac、WindowsPhone，几乎能满足所有人的需求。

- Eudic的**屏幕取词**功能实在是太强大了，舔爆！
- 个人感觉，Eudic翻译的句子比一般的网站的机翻更确切些，我就那这个翻译过外文文献，感觉不错。
- Eudic有个学习版块，是用来背单词的，虽然没有专业背单词的功能那么强，但是不想麻烦的话，用这个完全可以，你可以自己选择一本词典设置计划进行记忆。里面的在线背诵词典还是比较丰富的，比如我在上面正在背考研英语 红宝书的单词。

### 下载与使用

下载途径：

- 手机应用市场搜“欧路词典”。
- Eudic官网下载链接 https://www.eudic.net/v4/en/app/download 。在当前链接点击移动设备，下载andriod版本即可。

贴个Eudic在android上的截图：

![Eudic-Android](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-Android.jpg)

图中我调的是暗黑模式，还有一个圆形的Aa字样的悬浮框，这些都是可以设置的，那个悬浮框主要是用来跨应用查单词用的。

贴个悬浮框的图：

![悬浮框](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-悬浮框.jpg)

Eudic的功能可以自行摸索。

Eudic自带的词典只有一些在线词典，可能不能满足咱们的需求，所以很多时候，我们需要**导入本地词典**。词典下载途径可以看这个。

那么如何导入本地词典呢，只需要把下载好的词典以及词典的样式文件打包放到android手机中**eudb_en**这个文件夹中。

贴个图：

![文件夹位置](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-FolderPath.jpg)

![文件夹内部](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-Dict.jpg)

顺手再贴一个背单词的图：

![背单词](/images/2020-04-20-英语词典工具eudic和goldenDict/Eudic-Study.jpg)



## GoldenDict 使用

### GoldenDict的优点（个人感觉）：

- 开源软件，代码地址：https://github.com/goldendict/goldendict 。对于开发爱好者，觉得哪用的不舒服且有能力的人，可以贡献一下自己的力量。
- 我是在windows 10上使用，然后使用下来，屏幕划词没有Eudic出色，但也可以在绝大部分情况下进行屏幕划词，主要是在google chrome 或一些其他软件的单词，用鼠标划词没有任何反应，但是选中单词后使用快捷键`Crtl+C+C`还是有效果的。（注：IE浏览器可以进行鼠标划词）
- 不仅可以添加本地词典，还可以添加翻译网站，维基百科等，或者你可以把这个词典当作一个**浏览器**也行。

### 下载：

1. 目前为止，GoldenDict最新版本的下载地址为：https://github.com/goldendict/goldendict/releases/tag/1.5.0-RC2

2. 直接点击**Source Code**就能下载，解压缩之后点击GoldenDict.exe即可运行该软件，你可以把这个固定到开始界面，方便使用window键进行搜索打开此软件。

### 使用与设置：

#### 系统设置

贴个GoldenDict开始界面：

![开始界面](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-Windows.png)

一开始的词典界面的语言是系统默认语言，你可以在Edit（编辑）--> Preferences（偏好）中设置软件语言。而且，一开始的界面字比较小，你可以使用快捷键crtl和+号进行放大，你也可以到View中Zoom(缩放)中选择缩放。

在偏好中你还可以设置很多东西，我设置过：

- 软件显示样式（Display Style）为Modern，好像好看些。
- Scan Popup(取词工具)的触发条件为按住Alt时，才对选中的单词进行取词翻译。
- Network 设置Use proxy server为开启，这样主要方便查看外国网站对单词的解释，比如维基百科。

设置里有很多，大家可以自行摸索。

#### 导入本地词典

在Edit下拉选择框中选择Dictionaries就可以导入词典了，GoldenDict导入词典的界面是这样的：

![词典导入](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-词典导入.png)

导入本地词典基本上只需要把词典的文件和词典的音频导入即可，即红色框中的东西。如果你的词典的文件和音频都在一个文件夹中，那么在Files和Sound Dirs处都导入你的文件夹即可。

导入成功后，你的菜单栏处会出现你词典的图标，你可以通过点击来进行选择使用此词典或者不使用此词典，如图：

![词典图标](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-词典图标.png)

查询单词：

![查询结果](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-查询结果1.png)

![查询结果](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-查询结果2.png)



#### 添加网站

同样的，也是在Edit中选择词典后选择网站，就进入到了设置面板中。设置截图：

![设置截图](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-WebSetting.png)

需要注意的是：

- **%GDWORD%** 字符串将会替换掉你的搜索关键词
- **已启用** 表示在查询单词时是否使用该网站，默认不开启。
- **作为链接** 是否作为一个链接，默认开启。
- **名称** 备注该网站名称
- **地址** 网站的url

我这里以有道翻译和谷歌翻译为例：

以单词heart为例，
谷歌翻译截图

![谷歌翻译](/images/2020-04-20-英语词典工具eudic和goldenDict/GoogleTranslate.png)

有道翻译截图
![有道翻译](/images/2020-04-20-英语词典工具eudic和goldenDict/YouDaoTranslate.png)

可以看出谷歌翻译的关键词是heart，在url中是放在末尾的，所以**%GDWORD%**就是放在这个url的末尾，这样就组成了网站设置中的地址选项。所以最终的url为https://translate.google.cn/#view=home&op=translate&sl=en&tl=zh-CN&text=%GDWORD% 。

同理，用**%GDWORD%**替换掉有道翻译url中的heart，然后最终的url即为http://youdao.com/w/%GDWORD%/#keyfrom=dict2.top 。

最终的一个效果：

![设置展示](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-WebShow.png)

![效果展示-谷歌翻译](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-GoogleShow.png)

![效果展示-有道翻译](/images/2020-04-20-英语词典工具eudic和goldenDict/GoldenDict-YouDaoShow.png)

### 对于GoldenDict 高CPU使用的解决

一开始用的时候出现过一个问题，那就是这个软件占用的CPU很高，我调用task manager查看到它使用了30%多的CPU，导致我电脑风扇声音有点大，电脑还热，

问题发生的环境：

- windows 10 版本1809
- GoldenDict版本1.5.0-RC2

解决方法：

经过在github上查找和cpu使用高的issue，然后找到解决方案，只需要在Edit的Preferences中的全文搜索选项（Full-text search）中关闭全文搜索即可，至于原因，我没看，主要是我暂时没发现这个全文搜索有啥用( •̀ ω •́ )✧。

## 词典下载途径

其实只要在搜索引擎下搜索**mdx 下载**就能找到许多词典了。

这里分享下我搜集到的好用的词典：

链接：https://pan.baidu.com/s/1XO6-avhbbRM1AbFcxUSCng 
提取码：q0z1

链接：https://pan.baidu.com/s/1y6G35-EIlhdbiJNf8Vn0LA 
提取码：ump5