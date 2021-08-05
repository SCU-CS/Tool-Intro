# 工具推荐

网络代理工具仅线下分享

先按工具类别分类，再按照系统/平台分类

>   若无特别说明，均为免费或开源软件

## Windows装机

>   Hugh个人瞎扯环节

首先排除2345全套和360全套，其次，腾讯除了游戏和腾讯会议外，装个微信+QQ/Tim就够了

不要**好压**，7zip或bandzip都行

浏览器用edge或chrome或firefox

>   如果你喜欢国内浏览器，那无所谓了

安全软件用Windows defender+火绒基本够了

然后截图可以用 snipaste

其他的暂时没想到了，可以看看下面的内容

## 编程工具

> Windows 下初学 C/C++ 建议 先点击[这里](https://scu-cs.github.io/C-Cpp/#/)
> 
> 软件的话 可以先使用 Dev-Cpp 或者 线上工具

### 编辑器

Windows
- notepad3(代替notepad)~~不推荐 notepad++？是因为作者台独~~
- Sublime~~可以一直试用~~
- typora(markdown 编辑器)~~实话实说 比VSCode香~~
- VSCode

Ubuntu/Debian(Linux)
- typora
- VSCode
- Vim/Emacs(上古俩神器，不过Emacs确实学习曲线抖)
- gedit(Ubuntu的记事本~~比Windows的好，起码可以调Tab宽度~~)

macOS
- typora
- VSCode
- ~~我不了解了~~

### IDE

>   最通用的就是**Jetbrain**自选的 Toolbox 和 VSCode+插件



Windows

|       编程语言       | 首选                                                | 备选                                         |
| :------------------: | --------------------------------------------------- | -------------------------------------------- |
|        C/C++         | VSCode/CLion(需要JB License)/VS~~(Hugh点名不喜欢)~~ | Vim/Dev                                      |
|         Java         | Intellij IDEA（社区版免费）                         | Eclipse/VSCode~~据说巨硬有一站式安装服务了~~ |
|        Python        | VSCode/Jupter/...                                   | Sublime/...                                  |
| Web（html，css，js） | VSCode                                              | WebStorm                                     |
|          C#          | VS/Rider                                            | ~~我觉得下面的东西都没什么写的必要了~~       |
|       Haskell        | VSCode                                              |                                              |
|        Scheme        | `rlwrap scheme`/Emacs                               |                                              |

其他平台差不多 macOS主要有个Xcode



>   Debian系的似乎一般还是装一个 **build-essential**



Android

|  编程语言  | 有就不错了                             |
| :--------: | -------------------------------------- |
|   C/C++    | C4droid                                |
|    Lua     | AndroLua+                              |
|   Python   | QPython/Python Compiler                |
|            | Dcoder(编码器) 支持不少语言 就是容易崩 |
| JavaScript | d/node.js                              |

>   大部分是在Google Play找到的



iOS上知乎找吧



### 虚拟化工具

Windows

-   VirtualBox/VMWare（本来不免费的东西，现在都免费了）
-   sandbox
-   win11的话应该不需要手机模拟器吧？
-   wsl 点击[这里]([Tool-Intro/README.md at main · SCU-CS/Tool-Intro (github.com)](https://github.com/SCU-CS/Tool-Intro/blob/main/WSL-install/README.md))看安装指南
-   mobaXterm

Ubuntu

-   VirtualBox
-   Wine

macOS

~~好像VB和VM都有~~

Android

-   一些虚拟机如光速虚拟机（Android上虚拟Android）
-   **Aid Learning** Android上的Linux xfce桌面

### 其他工具

git cmake之类的该装就装

不过Windows可以装 Github Desktop~~不会翻墙就算了~~



Ubuntu下 使用`xdg-open`使用默认软件打开文件，如`xdg-open demo.pdf`

-   valgrind : 一套专业工具
-   tldr : too long don't read 神级辅助工具
-   dotfile : 看需要（去GitHub搜是干嘛的

都可以 `apt` 装

### **[KDE connect](https://kdeconnect.kde.org/)**

>   A project that enables all your devices to communicate with each other.
>
>   一个让你多设备互通的项目

包括不限于

1.   剪切板共享
2.   文件贡献
3.   发送ping
4.   command

### [ManicTime]([Download Windows Client - ManicTime](https://www.manictime.com/download/))

一个全平台的软件使用计时工具

## 文件相关

### PDF

>   浏览器也能看

Windows

-   Acrobat（非免费
-   PDF XChange Viewer
-   福昕阅读器（国产，可能有广告
-   ...

Ubuntu

-   自带一个
-   Calibre
-   ...

Android

-   Acrobat（非免费
-   福昕阅读器
-   WPS

### epub

>   mobi epub

Android

-   **厚墨**（强推

Windows

-   calibre
-   bazaar（不太行

### 类型转换

>   主要是 PDF 相关的

**pandoc** 是比较强的工具

Windows

-   word
-   pandoc
-   Icecream PDF Candy
-   Acrobat



Ubuntu

-   pandoc

### 一些Windows工具

| 工具类型 | 软件名                                                   | 原因                                                         |
| -------- | -------------------------------------------------------- | ------------------------------------------------------------ |
| video    | [PotPlayer64](http://www.potplayercn.com/)               | 倍速等功能好得不行                                           |
| zip      | [Bandizip](https://www.bandisoft.com/bandizip/)          | 比7zip好 不过有付费版本和广告                                |
|          | [7-Zip](https://www.7-zip.org/)                          | 免费 好用                                                    |
| 搜索类   | [Wox](http://www.wox.one/)                               | 软件搜索（An effective launcher） ~~不过我用的时候 那个版本有CPU突发高占用的bug~~ |
|          | [everything](https://www.voidtools.com/zh-cn/)           | 文件搜索神器                                                 |
| 图片     | [HoneyView](https://cn.bandisoft.com/honeyview/)         | 快速的图片查看器                                             |
| 安全工具 | [火绒]([火绒安全 (huorong.cn)](https://www.huorong.cn/)) | 谁能拒绝一个免费安静不扰民，还能防弹窗的完全软件             |
| 共享软件 | [spacedesk](https://www.spacedesk.net/)                  | 让手机变成第二屏幕的软件                                     |
| 截图软件 | snipaste（微软商店                                       | 用了就知道了                                                 |
| 思维导图 | [Xmind](https://soft.scu.edu.cn/product.html?id=243)     | 学校有免费的Xmind8pro~~感觉还不如Xmind2020~~                 |

## 插件推荐

### 编程相关

-   [Wakatime](https://wakatime.com/) IDE的计时插件
-   



### 浏览器插件

>   浏览器插件中心/商店下载或者 [GreasyFork](https://greasyfork.org/zh-CN)

-   Tampermonkey 使用插件的好宝贝
-   Video Speed Controller 浏览器倍速播放控制器
-   
