# XingXiXiangRong
# 自制的第一个Android应用
* 基于Android的控件WebView而做的一个小型浏览器
* 里面添加我做的一个[加密系统](https://github.com/ZhangHeng0805/PassWordSystem)应用界面
# Android简介
 ## 1、应用特色
+ （1）四大组件
> Android系统四大组件分别是活动( Activity)、服务( Service)、广播接收器( Broadcast Receiver )和内容提供器( Content Provider )。
+ （2）丰富的系统控件
> Android系统为开发者提供了丰富的系统控件,使得我们可以很轻松地编写出漂亮的界面。当然如果你品位比较高，不满足于系统自带的控件效果，也完全可以定制属于自己的控件。
+ （3） SQLite数据库
> Android系统还自带了这种轻量级、运算速度极快的嵌人式关系型数据库。它不仅支持标准的SQL语法，还可以通过Android封装好的API进行操作，让存储和读取数据变得非常方便。
+ （4）强大的多媒体
> Android系统还提供了丰富的多媒体服务，如音乐、视频、录音、拍照、闹铃,等等,这一切你都可以在程序中通过代码进行控制，让你的应用变得更加丰富多彩。
+ （5）地理位置定位
> 移动设备和PC相比起来,地理位置定位功能应该可以算是很大的- -个亮点。现在的Android手机都内置有GPS,走到哪儿都可以定位到自己的位置,发挥你的想象就可以做出创意十足的应用，如果再结合功能强大的地图功能，LBS这一领域潜力无限。
## 2、发展历史
> Android系统是目前世界上市场占有率最高的移动操作系统，不管你在哪里，都可以看到Android手机几乎无处不在。2003年10月，Andy Rubin等人一起创办了Android 公司。2005 年8月谷歌收购了这家仅仅成立了22个月的公司，并让Andy Rubin继续负责Android项目。在经过了数年的研发之后，谷歌终于在2008年推出了Android 系统的第一个版本。但自那之后，Android的发展就一直受到重重阻挠。乔布斯自始至终认为Android是一个抄袭iPhone的产品，里面剽窃了诸多iPhone的创意，并声称一定要毁掉Android。而本身就是基于Linux开发的Android操作系统，在2010年被Linux团队从Linux内核主线中除名。又由于Android中的应用程序都是使用Java开发的，甲骨文则针对Android侵犯Java知识产权一事对 谷歌提起了诉论.....，Android从面世以来到现在已经发布了二十几个版本了。在这几年的发展过程中，谷歌为Android王国建立了一个完整的生态系统。手机厂商、开发者、用户之间相互依存，共同推进着Android的蓬勃发展。
## 3、开发技术
### 一、系统架构：Android大致可以分为四层架构: Linux 内核层、系统运行库层、应用框架层和应用层。
+ (1). Linux内核层
> Android系统是基于Linux内核的，这一层为Android设备的各种硬件提供了底层的驱动,如显示驱动、音频驱动、照相机驱动、蓝牙驱动、WiFi驱动、电源管理等。
+ (2).系统运行库层
> 这一层通过一些C/C+t库来为Android系统提供了主要的特性支持。如SQLite库提供了数据库的支持，OpenGLIES 库提供了3D绘图的支持，Webkit 库提供了浏览器内核的支持等。
+ (3).应用框架层
> 这一层主要提供了构建应用程序时可能用到的各种API, Android自带的一些核心应用就是使用这些API完成的，开发者也可以通过使用这些API来构建自己的应用程序。
+ (4).应用层
> 所有安装在手机上的应用程序都是属于这一层的，比如系统自带的联系人、短信等程序,或.者是你从Google Play上下载的小游戏，当然还包括你自已开发的程序。
