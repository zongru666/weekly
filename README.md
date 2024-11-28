# 每周科技补全

本项目是[玄离199](https://space.bilibili.com/67079745)每周科技补全视频中提到的软件和开源项目总结，方便观众收藏和搜索。文档内容来自视频文稿，所以部分内容直接读起来会比较奇怪，建议配合视频观看。


## 第25期【2024年11月16日-2024年11月23日】

### 科技推荐

这，是一个 Windows 上的小说软件，看起来很普通，甚至有点简陋，

但当我按下 F12，把边框隐藏掉，按下 Ctrl + T，把它置顶，

再使用 Ctrl + 滚轮，调整一下透明度，

它就变成了这样，可以完美的隐藏在电脑的任何一个角落，

哪怕是老板站在身后，也不一定能发现。
<br/>
<br/>
<br/>
它叫 Reader，是一个开源、免费、绿色的开源小说软件，

但我认为，最大的作用，就是像我上边演示的那样，非常隐蔽的摸鱼。
<br/>
<br/>
<br/>
而类似这样的摸鱼小说软件，还有很多，

建议收藏本视频，你早晚用得到；
<br/>
<br/>
<br/>
如果你是一个程序员，可以在 VSCode 的扩展商店中，搜索一个叫 Thief-Book 的插件，

安装完之后，在插件设置里，设置一下小说目录，

小说内容就会出现在左下角的状态栏中，

按下 Ctrl + 逗号 和 Ctrl  + 句号，进行翻页，

如果有人来了，按下 Ctrl + M，它就会随机变成一种语言的 Hello World，快速隐藏。
<br/>
<br/>
<br/>
使用 IDEA 或 PyCharm 比较多的，可以在扩展中，搜索 chapter_reader，

安装完之后，在 Tools 菜单中，就能找到它的设置，

可以选择在线阅读，或者本地阅读。

chapter_reader 支持三种阅读形式，默认是在左下角，

也可以调整为代码弹出框，

导航栏。
<br/>
<br/>
<br/>
Thief 是一个支持 Windows、Mac、Linux 的多平台摸鱼软件，

不止可以用来看小说，还支持 网页摸鱼、视频摸鱼、直播摸鱼、PDF摸鱼，

它的口号就是，一款真正的创新摸鱼神器。

Reader（摸鱼看小说）：
https://github.com/binbyu/Reader

Thief（创新摸鱼神器）：
https://github.com/cteamx/Thief


### 开源项目

#### 1.ScriptCat 

这是一个可以执行用户脚本的浏览器扩展，

这么说可能比较难理解，换种方式来说：

它是一个兼容油猴所有脚本，且提供了更强大的 API、更多功能、更好看页面 的浏览器脚本管理器。

它可以从原版油猴上无缝迁移过来，

且在油猴的基础上，增加了后台脚本、定时脚本、云同步、脚本合集、编辑器等多项功能，

在使用油猴的用户，可以尝试一下。

ScriptCat（油猴脚本替代者）：
https://github.com/scriptscat/scriptcat

#### 2.Bulk-Crap-Uninstaller

这是一个 Windows 上的卸载工具，

使用它，可以快速大量移除 Windows 上不想要的软件，

支持批量卸载、强制卸载，且卸载之后可以清理残留文件，轻松整治流氓软件。

Bulk-Crap-Uninstaller（Windows卸载工具）：
https://github.com/Klocman/Bulk-Crap-Uninstaller

#### 3.FileCodeBox

这是一个用来匿名分享文件的文件快递柜，

用户可以上传文件，同时选择有效期，之后，会生成一个五位数的取件码。

其它用户可以通过取件码，就像取快递一样，把文件取走。

FileCodeBox（文件快递柜）：
https://github.com/vastsa/FileCodeBox

## 第24期【2024年11月9日-2024年11月16日】

### 科技推荐

不知道你现在，还有没有在用 QQ，还会不会发说说。

如果没有在用，不知道你是否会怀念曾经的青春。
<br/>
<br/>
<br/>
本周最火的开源软件之一，就和 QQ 空间有关，

它叫 GetQzonehistory，功能非常简单，就是恢复你 QQ 空间曾经发过的说说。
<br/>
<br/>
<br/>
想使用它也非常容易，首先在 GitHub 搜索 GetQzonehistory，找到它，

点击旁边的 Releases，下载你系统对应的版本。
<br/>
<br/>
<br/>
下载完成后，把压缩包解压，直接双击运行。
<br/>
<br/>
<br/>
点击左边的【获取内容】按钮，扫码登录 QQ 账号，程序就会自动读取数据，稍微等待一会儿即可。

数据读取完之后，它会自动分析享，

显示你一共发过多少说说，谁和你交互的最多，以及第一条说说是什么。
<br/>
<br/>
<br/>
点击左侧的说说列表，就可以按时间顺序，看到全部说说了，

嗯，越往前，越中二...
<br/>
<br/>
<br/>
同时，还可以看到 QQ 空间的留言、好友、转发、照片墙等内容。
<br/>
<br/>
<br/>
我简单了解了一下，发现它是使用爬虫，获取到了 QQ 空间的消息列表，从而读取到说说。

所以，只要曾经和人有过互动的说说，基本上都能获取到。
<br/>
<br/>
<br/>
其实微信曾经也可以用这种方法，获取到已经被隐藏的朋友圈，可惜后来被修复了。

GetQzonehistory（获取QQ空间说说）：
https://github.com/LibraHp/GetQzonehistory

### 2.开源项目

#### 1.Qwen2.5-Coder

阿里在本周，开源了新的模型 Qwen2.5-Coder，

该模型专门为代码打造，一共有六款，

其中的 32B 版本，在多种测试标准中，均刷新了开源记录。

甚至在代码修复、多语言编程等项目，超过了 GPT-4o。

根据我在多个程序员社区的观察，本次开源的模型，很多人都给了极高的评价。

Qwen2.5-Coder（最新开源的千问代码大模型，本地部署效果很好）：
https://github.com/QwenLM/Qwen2.5-Coder

#### 2.wechat-dump-rs

微信 4.0 版本，还没有公测，数据库解密就已经被搞定了，

该项目使用 内存暴力搜索，从微信进程中寻找出 key，并自动解密数据库，

感兴趣的可以试一下，或者基于它进行二开。

wechat-dump-rs（解密微信数据库）：
https://github.com/0xlane/wechat-dump-rs

#### 3.ToastFish

这是一个利用 Windows 通知栏背单词的软件，

在开启之后，它会在电脑的右下角，弹出一个小窗口，

然后你就可以 上班、上课等恶劣环境下，安全隐蔽地背单词了。

它支持多种语言，且能设置词库，背完之后还可以进行随机测试，功能相当齐全。

ToastFish（摸鱼背单词）：
https://github.com/Uahh/ToastFish

#### 4.hello-algo

上周给大家简单分享了一点我的刷题心得，其中就提到了这个项目，

Hello 算法，是一本开源免费、新手友好的 数据结构与算法 入门教程，

只要跟着教程走，它就会一点一点的，从最基础的概念起，

让你一步步的了解 各种数据结构 和 算法，

整个内容深入浅出，且配有简单易懂且准确的动画，

感兴趣的，希望能进大厂工作的，可以跟着学习一下。

hello算法：
https://github.com/krahets/hello-algo

## 第23期【2024年11月2日-2024年11月9日】

### 科技推荐

李跳跳作者自 23 年 8 月 24 日，收到某大厂的律师函之后，

就宣布了无限期停更，再也没有更新过软件。

不过，我最近发现，李跳跳-真实好友，

竟然在几天前，偷偷更新了 5.0 内测版。
<br/>
<br/>
<br/>
李跳跳-真实好友，是李跳跳开发的一个，检测微信单向好友的软件。
<br/>
<br/>
<br/>
大家都知道，在微信上，如果你被好友删掉，是不会有任何提示的。
<br/>
<br/>
<br/>
但是，如果这时候，你给对方转账，就能发现端倪，

一是，正常好友转账时，会显示好友的实名信息，而单向好友什么都不会显示。

二是，随便输入一个金额，点击转账按钮，会提示对方不是你的好友，或者你已经被拉黑。
<br/>
<br/>
<br/>
通过这种方式检测单向好友，是目前最靠谱、最不打扰别人的方式，

李跳跳-真实好友，就是利用这种原理，加上手机的无障碍权限，

逐个打开好友的转账页面，用来判断好友的状态。
<br/>
<br/>
<br/>
它使用起来也非常简单，

首先，打开真实好友，给它添加无障碍权限，

然后点击开始检测，它会自动打开微信的通讯录界面，

并通过上边我们所讲的方式，对好友进行检测。

这中间会打开转账页面，但软件不知道你的密码，所以不用担心。
<br/>
<br/>
<br/>
如果检测过程发生了中断，你可以在真实好友中，重新开始，

它会中断位置，继续检测。
<br/>
<br/>
<br/>
检测完成后，你就可以在真实好友中，看到有哪些好友出异常。
<br/>
<br/>
<br/>
在真实好用的首页，可以选择批量备注，给这些人加上备注，

把你删除的人，备注后边会自动加上 @bsc，

在微信中搜索 @bsc，就可以对他们批量管理了。

李跳跳真实好友：https://www.123pan.com/s/ZYAZVv-jmGjd.html

### 开源项目

#### 1.GitHub520

我给大家推荐过很多 Github 的开源项目，

但我发现很多人因为网络原因，根本上不去 Github，

Github 520，是一个帮助你优化 Github 访问速度的项目，

它收集了大量国内访问比较快的 Github 服务器 IP，

只需要把它添加到电脑的 hosts 文件里，Github 就可以畅通无阻了。

还可以用 SwitchHosts 等软件，对 hosts  自动管理、自动更新。


那么问题来了，这个项目也是在 Github 上的，如果访问不了 Github，怎么访问这个项目呢？

大家可以看我之前的这期视频。

Github520（流畅访问Github）：
https://github.com/521xueweihan/GitHub520

下面的地址无需访问 GitHub 即可获取到最新的 hosts 内容：
文件：https://raw.hellogithub.com/hosts
JSON：https://raw.hellogithub.com/hosts.json

#### 2.Hunyuan3D

腾讯这周忽然开源了两个开源模型，

一个是 Hunyuan-Large（混元-Large），拥有 3890 亿参数的 MoE 模型。
<br/>
<br/>
<br/>
但我比较感兴趣的是另一个，Hunyuan3D（混元3D），

这是一个用来生成 3D 建模的 AI 模型，

只需要写一段简单的描述，或者上传一张图片，

稍微等一会儿，一个建模就生成好了，

给大家看一下生成的效果，我感觉对于目前的 AI 来说，还是很不错的。

hunyuan3D（生成3D建模）：
https://github.com/Tencent/Hunyuan3D-1

#### 3.How To Live Longer

看名字就知道，这个项目的目标，是教你怎么多活几年，

它用程序员的方式，对人身体的输入和输出做了规定，

并设定了语气目标和关键结果。

并且，每项内容都不是空穴来风，而是有相应的论文做支撑，

健康生活想长寿，可以拿来当作参考资料。

HowToLiveLonger（怎么多活几天）：
https://github.com/geekan/HowToLiveLonger

## 第22期【2024年10月26日-2024年11月2日】

### 科技推荐

#### 1.Drive Icon Manager

如果你在电脑上使用 国产网盘类软件 比较多，

那打开资源管理器，你就很有可能在 “设备和驱动管理器”、和左侧的快速访问栏中，看到类似这样的图标，

并且，它还不能删除，需要到软件设置里边，找到隐藏很深的设置，才能关掉。

如果你和我一样，不喜欢这些图标，那 Drive Icon Manager 就正是你需要的，

它可以 一键删除和管理 此电脑、资源管理器侧边栏 中的应用图标，

还可以修改注册表权限，直接把应用添加图标的权限禁用掉。

Drive Icon Manager：
https://github.com/Return-Log/Drive-Icon-Manager

#### 2.OSSQ 系统版本转换

不知道你在用的 Windows 是什么版本？

我猜大部分人可能都是买电脑时预装的家庭版，

但因为家庭版的 Windows 售价比较便宜，

所以它缺少了很多功能，比如组策略编辑器、Hyper-V 虚拟机。
<br/>
<br/>
<br/>
有时候，这些缺少的功能就很可能影响使用，

走官方的渠道升级，需要补上近千元的差价，

OSSQ 系统版本转换，是一个用来转换系统版本的工具，支持一键转换专业版、企业版、教育版、家庭版等等版本，

感兴趣的可以收藏一下。

OSSQ 系统版本转换：
https://ossq.cn/switching.html

### 开源项目

#### 1.Magpie

如果你喜欢玩老游戏，你会发现，它们在现在的电脑上，

很多时候都不能全屏，只有一个小窗口，并且画质很差。

Magpie 是一个游戏窗口缩放工具，它主要有两个功能，

一是把不支持全屏的游戏全屏显示，

二是，通过 AI 算法，对游戏进行超分，提升游戏的画质。

比如，这是我随便下载的一个老游戏，这是超分之前的画质，这是超分之后的画质。

Magpie：
https://github.com/Blinue/Magpie

#### 2.state-of-the-art-shitcode

这是一个教你写代码的教程，但并不是教你写好代码，而是专门教你写垃圾代码，
 
比如，创建变量的时候，不要取有实际意义的名字，而是要用无意义的字符，

一定不要写注释，如果必须要写，也要用小语种，

尽量把代码写成一行，创建很多没有意义的变量，等等等等。

把这些学会，你就成为一个制造屎山的大师。

state-of-the-art-shitcode：
https://github.com/trekhleb/state-of-the-art-shitcode

#### 3.No Code

这是一个非常神奇的项目，它足足有 60 多 k Star，多次登顶排行榜，

它的目的是教你怎么编写 安全、可靠、没有 BUG 的应用，

对于这个千古难题，No Code 提出了一个一劳永逸的办法：就是不要写任何代码，

程序员们纷纷称赞，称它：

无既是有，有既是无。

大象无形，大道至简。

大巧在所不为，大智在所不虑。

No Code：
https://github.com/kelseyhightower/nocode

## 第21期【2024年10月19日-2024年10月26日】

### 科技推荐


文字，是我们每天上网的时候，都能遇到的，

尤其是在 图片和视频 里，经常会有各种长相不同的字体。
<br/>
<br/>
<br/>
但，这些字体并不是凭空产生的，它们都是有人设计出来的，

并且，设计者会拥有字体的版权。
<br/>
<br/>
<br/>
拿来做设计、做视频，或做其它商业内容，很可能会有被告上法院的风险。
<br/>
<br/>
<br/>
所以，在用到字体的场景，最好直接使用 免费可商用 的字体，祛除隐患，

建议收藏本视频，早晚用得到。
<br/>
<br/>
<br/>
我平时用得最多、最喜欢的，其实是各家手机厂商定制的字体，

因为手机厂商财大气粗，并且是要用在手机系统里的，

所以一般设计都非常考究好看，并且很多都可以商用。

比如华为的 HarmonyOS Sans，小米的 MiSans，vivo 的 vivo Sans，OPPO Sans，都非常棒。
<br/>
<br/>
<br/>
不过，它们一般都会比较正式，

如果你想要更多不同的商用字体，可以到猫啃网，

这是一个专门分享可商用字体的网站，足足有 677 款，绝对能满足各种需求了。

猫啃网：
https://www.maoken.com/


### 开源项目

#### 1.智元灵犀X1

百大 UP 主、野生钢铁侠 “稚晖君” 的创业项目开源了，

这是一个人形机器人项目，包括所有的软件、硬件、图纸、代码、文档均已开源，

资料总大小超过 1.2 GB，有想要自己做机器人的，可以拿来模仿或做参考资料。

智元灵犀X1（开源机器人）：
https://www.bilibili.com/opus/991734208102662148

#### 2.self-llm

这是一份《开源大模型食用指南》，

目的是教会你如何基于 Linux 环境，快速 部署和微调 开源大模型，是一个更适合中国宝宝的教程。

self-llm（开源大模型食用指南）：
https://github.com/datawhalechina/self-llm

#### 3.GoGoGo

这是一个基于 Android 调试 API，实现的虚拟定位工具，

把它安装到手机上，可以任意修改手机 GPS 定位的位置，

修改之后，手机软件获取到的定位也会改变，感兴趣的可以试一下。

Gogogo：
https://github.com/ZCShou/GoGoGo

## 第20期【2024年10月12日-2024年10月19日】

### 科技推荐


如何白嫖正版的游戏、软件 和 其它资源？

今天给大家推荐几个网站：
<br/>
<br/>
<br/>
提到白嫖正版，最出名的就是 Epic 喜加一，Steam 偶尔也会有一些游戏限免。
<br/>
<br/>
<br/>
it之家喜加一，是 it 之家旗下的一个板块，

这里收集了 Steam、Epic、索尼 等平台限免游戏的资讯，

点击标题即可查看游戏的详细介绍，和它们的领取地址。
<br/>
<br/>
<br/>
如果你更喜欢在手机上看这些资讯，可以到 “小黑盒”，

这里有一个【喜加一】板块，同样是收集了各大游戏平台的限免信息，

并且可以直接登录在线领取。
<br/>
<br/>
<br/>
除了游戏，软件同样也会有很多限免，

比如这个叫 “反斗限免” 的网站，就是专门收集各种 收费软件限免 消息的，

不管是 iOS、Android、Mac，还是 Windows，都能在这里找到相关的板块。
<br/>
<br/>
<br/>
苹果用户，可以关注 “果粉GoFans”，

顾名思义，这是一个苹果软件的咨询网站，不管是 优惠、打折、还是限免，这里全都有。
<br/>
<br/>
<br/>
如果你不想每天去关注这些信息，可以用这个 “mergeek”，

它可以一键订阅这些信息，每天主动推送给你。

it之家喜加一：
https://www.ithome.com/zt/xijiayi

反斗限免：
http://free.apprcn.com/

GoFans：
https://gofans.cn/

Mergeek：
https://mergeek.com/free/apps

### 开源项目

#### 1.Luxirty Searc

这是一个基于 Google 开发的搜索引擎，

根据作者的自述，它在搜索的时候，被垃圾网页激怒，

然后就基于 google cse 开发了这个项目，

它在 Google 搜索结果的基础上，

屏蔽了 某n、某云、某发者社区 等低质量网站和爬虫生成的内容农场，

所以搜索结果质量会更高。

LuxirtySearch（搜索引擎）：
https://github.com/KoriIku/luxirty-search

#### 2.RunCat

这是一个一直在奔跑的小猫，打开之后，它就会出现在电脑任务栏上 ，

并且会根据电脑 CPU 占用变多，而越跑越快，

如果它跑得飞快，就说明你电脑运行的东西太多了，

没有什么太大的实际作用，但确实挺好玩的。

RunCat（奔跑小猫）：
https://github.com/Kyome22/RunCat_for_windows

#### 3.video2x

video2x 是一个开源的 视频、图片 超分和插帧 工具，

比如给它上传一个 480P 的视频，可以直接超分到 1080P 甚至 2K、4K，

30 帧的视频，可以插帧到 120 帧，

如果你需要这样一个 图片、视频 画质增强工具，可以试一下。

video2x（视频图片超分工具）：
https://github.com/k4yt3x/video2x

## 第19期【2024年10月5日-2024年10月12日】

### 科技推荐

在使用电脑时，如果磁盘空间不足，那将会是一件非常痛苦的事，

因为你有很大概率不知道，到底是什么在占用空间，也不知道怎么清理。
<br/>
<br/>
<br/>
所以，今天就推荐几个用来扫描磁盘，分析电脑空间占用的软件。
<br/>
<br/>
<br/>
Windows 上，我最喜欢的软件是 WizTree，

安装打开之后，在左上角选择要扫描的分区，

稍等几秒，磁盘的占用情况就分析好了。
<br/>
<br/>
<br/>
左上角，是按大小排序的树形目录，比如我的电脑上，最大的文件夹是微信数据，

可以点击前边的加号，把目录展开，进一步深度分析，找到占用空间的罪魁祸首。
<br/>
<br/>
<br/>
点击【文件查看】，可以直接看 具体某个文件 的占用，从大到小查看磁盘内的文件。
<br/>
<br/>
<br/>
右上角，是按文件类型排序的视图，用来查看 某种类型文件 的占用情况，

比如我电脑排第一的 “dat” 文件，就是微信加密后的图片。
<br/>
<br/>
<br/>
下方，是 文件占用情况 的可视化视图，面积越大，就代表占用越大，

点击图形，上方就会自动选中对应的文件。
<br/>
<br/>
<br/>
另一个用的比较多的是 SpaceSniffer，

打开之后，先选择一个磁盘，软件就会自动扫描，并用图形化的方式，展示空间占用情况，

占用空间越大，面积就越大，点击之后可以继续向下查看子文件夹，

双击上方的标题，能返回上一级。

我不太喜欢这种图形化的方式，但如果有喜欢的可以尝试。
<br/>
<br/>
<br/>
另外，搜索软件 Everything，也可以拿来分析空间占用情况，只需要在 “排序” 中，切换成按大小排序即可。
<br/>
<br/>
<br/>
在 macOS 上，可以使用腾讯的 Lemon，点击【磁盘空间分析】按钮，等待一会儿，

就可以直观的查看电脑文件占用情况了。

WizTree（磁盘分析）：
https://diskanalyzer.com/

SpaceSniffer（磁盘分析）：
http://www.uderzo.it/main_products/space_sniffer/

Lemon（磁盘分析macOS）：
https://lemon.qq.com/


### 开源项目

#### 1.Kazumi

Kazumi 是一个 开源的、基于自定义规则的 番剧 APP，

它采用了枪弹分离的模式，

导入别人分享的规则后，就能在线观看番剧了，

约等于是阅读的番剧版，几乎没有它不能看的，感兴趣的可以关注一下。

Kazumi（基于自定义规则的番剧APP）：
https://github.com/Predidit/Kazumi

#### 2.BackgroundMusic

这是 mac 上，一个开源的音量控制软件，

安装后，它可以对 mac 上的软件，进行单独的音量控制。

BackgroundMusic（单独控制mac应用音量）：
https://github.com/kyleneideck/BackgroundMusic

#### 3.CS-Books

这个项目中，收集了超过 1000 本计算机相关的经典书籍，涉及各个领域，喜欢读书的可以关注一下。

CS-Books（超过1000本的计算机经典书籍）：
https://github.com/forthespada/CS-Books

#### 4.MIMO

MIMO 是阿里新公开的一个项目，

它可以把视频中的一个人物，替换成另一个人物，或者动漫角色，

根据演示来看，效果相当不错，

但是和之前的几个项目一样，只是建了代码仓库，公开了论文，但是没有开源代码。

MIMO（替换视频人物）：
https://github.com/menyifang/MIMO

## 第18期【2024年9月28日-2024年10月5日】

### 科技推荐


网盘，是很多人分享资源的第一选择，

无数的宝藏，都会通过网盘的形式，被分享出去，

甚至，你想要的大部分资源，都很有可能有人用网盘分享过。
<br/>
<br/>
<br/>
不过很可惜，这些资源，分布在互联网的角角落落，想要找到它们，并不容易。
<br/>
<br/>
<br/>
比如我在普通的搜索引擎，直接搜 “某某电视剧 网盘下载”，

很大概率找不到什么有价值的内容。
<br/>
<br/>
<br/>
但有一种特殊的搜索引擎，是专门为了寻找 网盘资源 设计的，

它们叫做 “网盘搜索引擎”。
<br/>
<br/>
<br/>
目前，已经有很多网盘搜索引擎在运行了，

网上随便一搜，就能找到无数个，

但这些搜索引擎的质量良莠不齐，甚至有很多是完全不能用的。
<br/>
<br/>
<br/>
盘搜 VIP，是一个由 “人工亲测精选的 网盘搜索工具 导航”，

这里一共收集了 76 个网盘搜索工具，

每一个都是人工亲测过的，确保可以使用的。
<br/>
<br/>
<br/>
并且，网站的作者还会给出每一个搜索引擎的 评分、优点、缺点、评价，和它的数据来源。

经过我的二次测试，盘搜 VIP 给出的评价大部分都非常准确。
<br/>
<br/>
<br/>
比如这个叫 “咔帕搜索” 的引擎，优点非常多，

唯一的缺点是，“搜索准确度较低，建议使用精准搜索”。
<br/>
<br/>
<br/>
我亲测的时候，使用它搜 “李跳跳”，

默认情况下，确实会出来一堆无关内容，

把默认的 “智能搜索”，改成 “精准搜索”，情况就完全不一样了，搜到的全部都是我想要的。
<br/>
<br/>
<br/>
这也说明了，盘搜 VIP 的作者 ，在整理的时候非常用心，

如果你想要找到各种资源，来这里搜一搜，一定没错。

盘搜vip：
https://www.pansou.vip/

### 开源项目

#### 1.Loaf

这是一个专门为摸鱼而生的项目，

安装到电脑上之后，点击摸鱼按钮，

屏幕上就会跳出来一个全屏的 Windows 更新界面，

然后你就可以放下电脑、放下工作，做一些其它的事了。

Loaf：
https://github.com/DinoChan/Loaf

#### 2.chsrc

如果你是一个在中国的程序员，一定会遇到这样的事：

想要下载一个代码的包或者依赖，但每秒只有几 KB 的速度，甚至还大概率会下载失败。

一般这种时候，大家都会选择换源，换一个国内组织搭建的镜像源，

但不同的包管理器，换源方式都是不太一样的，

单独处理，还是比较麻烦。

chsrc 是一个 全平台通用的换源工具，支持各大操作系统，和 编程语言，

可以一键切换到速度最快的下载源。

同时，它还是一个换源框架，可以使用它，很简单的编写出新的换源方法，

饱受网络折磨的程序员，可以关注一下这个项目。

chsrc：
https://github.com/RubyMetric/chsrc

#### 3.Game-Cheats-Manager

这是一个下载和管理 “单机游戏修改器” 的工具，

使用起来非常的简单。

比如，我想要黑神话的修改器，

只需要在右边的搜索框，搜索 “黑神话”，找到结果后，双击下载就可以了。

下载完成的修改器会出现在左边，双击名字就能打开。

目前 Game-Cheats-Manager 的修改器，都来自风灵月影 和 WeMod，支持的游戏有近 4000 款，

喜欢用修改器玩单机游戏的，可以关注一下。

Game-Cheats-Manager：
https://github.com/dyang886/Game-Cheats-Manager

## 第17期【2024年9月21日-2024年9月28日】

### 科技推荐

2024 年，如何在浏览器上使用 Flash，玩各种网页小游戏，目前一共有几种解决方案。
<br/>
<br/>
<br/>
一、使用内置 Flash 的浏览器，

Chrome 最后一个内置 Flash 的版本是 53，

使用它，就能直接访问需要 Flash 的网页。
<br/>
<br/>
<br/>
如果不想用这么低的版本，

还可以使用开源的 CefFlashBrowser，这是一个专门为 Flash 而生的项目，

它把 Flash 直接集成到了浏览器当中。
<br/>
<br/>
<br/>
第二种方式，使用支持 Flash 的浏览器，并在电脑上安装 Flash 软件，

Chrome 最后一个支持 Flash 的版本是 87，

各种国产浏览器，基本上也都可以用 Flash。

Edge 浏览器可以在 IE 模式下，加载 Flash。

如果是为了玩游戏，360 曾经推出过一款游戏浏览器，

不但内置了 Flash，还专门为游戏场景做了优化，支持多开、分屏。
<br/>
<br/>
<br/>
任意挑选一个装在电脑上，准备好浏览器，再安装一个 Flash 软件就可以了。

目前直接搜索，会下载到特供版，广告非常多，

但还好有一些开源项目可以解决，我比较推荐 FlashPatch 和 cleanflash，

它们都纯净无广，兼容性也不错。
<br/>
<br/>
<br/>
第三种方式，使用一些替代方案，

Ruffle 是一款开源费的 Flash 模拟器，有客户端和浏览器插件两种模式，

目前能兼容 95% 的 Flash 语言功能和 78% 的 API 功能。
<br/>
<br/>
<br/>
第四种方式，如果是玩游戏，可以找一些替代方案，

比如这个叫 Flash 保存计划的开源项目，收集了上万个 Flash 项目，

不但可以在浏览器打开直接玩，还能下载 SWF 源文件。
<br/>
<br/>
<br/>
这个叫 oldswf 的网站，收集了五万款 Flash 小游戏，打开就能玩。
<br/>
<br/>
<br/>
CefFlashBrowser：https://github.com/Mzying2001/CefFlashBrowser

cleanflash：https://gitlab.com/cleanflash/installer

360游戏浏览器：https://www.ghxi.com/360yxllq.html

FlashPatch：https://github.com/darktohka/FlashPatch

Ruffle：https://ruffle.rs/

Flash保存计划：https://flash.homes/

oldswf：https://oldswf.com/4


### 开源项目


#### 1.Libcimbar

以后看到这种二维码，一定要注意，

这不是一个普通的码，而是被精心设计出来的码。
<br/>
<br/>
<br/>
我们平时看到的二维码，通常只能容纳几 KB 的数据，

所以只是会被拿来存储一些链接或者文本。
<br/>
<br/>
<br/>
而这个二维码，足足可以存储 33MB 的文件，

也就是说，我们常见的很多资源，包括小说、图片、漫画、软件、音乐，都能被压缩到这一个码内。
<br/>
<br/>
<br/>
收到码的人，只需要用摄像头扫一下，就能获取到里边的资源。

这个项目叫做 libcimbar，感兴趣的可以关注一下。

Libcimbar：
https://github.com/sz3/libcimbar

#### WeChatMsg

这是一个可以 解密微信数据库，导出 聊天数据 的开源项目，

把它安装到电脑上，按照指引启动，就可以把 微信聊天记录 提取出来，

并且还能保存成网页 和 文本，供你永久收藏，自己的数据自己做主。

WeChatMsg：
https://github.com/LC044/WeChatMsg

#### image-matting

这是一个用来处理图片的开源项目，

它使用开源算法开发，完全基于本地运行，

可以对图片进行抠图，制作各种样式的证件照，转换图片的格式，

根据我的实际测试，几个功能的效果都还不错，运行速度也很快，

并且因为完全本地运行，所以还能很好的保护隐私。

image-matting：
https://github.com/pangxiaobin/image-matting


#### PintreeNewTab

这是一个开源的浏览器插件，

把它安装到浏览器之后，只需要点一下图标，

就能把浏览器的书签，转换成一个好看的导航网页。

PintreeNewTab：
https://github.com/tangxiaoqi-tangxiao/PintreeNewTab

## 第16期【2024年9月14日-2024年9月21日】

### 科技推荐

在 Windows 系统中，

其实有一个隐藏的上帝模式，也被叫做 “完全控制面板”，默认是看不到的，

只需要在任意位置，新建一个由一串代码组成的文件夹，就能看到它。

在这里，几乎包括了 Windows 上的所有设置功能，

不管是常用的，还是不常用的，都能在这里找到，足足有 200 多项。

如果你嫌麻烦，

在 Github 上还有一个叫做 Windows-Super-God-Mode 的开源项目，可以一键打开上帝模式。
<br/>
<br/>
<br/>
但我今天要分享的并不只这个，

刚刚创建上帝模式文件夹时，用的的那串代码，叫做 “Windows类标识符”，

像这样的标识符，还有很多。

比如屏幕上这串，

把一个文件夹名字修改成它之后，就能把普通文件夹，变成【我的电脑】，

打开之后，也是【我的电脑】的功能。
<br/>
<br/>
<br/>
有了这个特性，就可以用它，来对文件夹作伪装，

比如，我这个文件夹里，有不想让人看到的内容，就可以把文件夹名字修改成它，

然后，其它人就没办法直接查看了，因为双击打开的，只会是【我的电脑】。
<br/>
<br/>
<br/>
但里边的文件，其实还存在，

只需要使用 WinRAR，找到这个文件夹，就能查看里边的内容了。

如果想解除伪装，就在 WinRAR 里，直接把它重命名掉，它就会恢复。

任意搜索引擎搜索 “Windows类标识符”，就能找到很多这样的代码，

可以把文件夹伪装成各种 Windows 自带功能。
<br/>
<br/>
<br/>
Windows-Super-God-Mode：
https://github.com/ThioJoe/Windows-Super-God-Mode

### 开源项目

#### 1.GKD

在李跳跳、轻启动等软件停更之后，

一个叫【搞快点】的开源项目，扛起了跳过开屏的大旗，

它的使用体验，完全不输李跳跳，但是拥有更强的自定义规则能力。
<br/>
<br/>
<br/>
它不仅可以在软件开屏的时候，跳过广告，

通过 高级选择器、订阅规则、快照审查 三个功能，

还几乎能帮你 自动点击 屏幕上的任意元素。
<br/>
<br/>
<br/>
你可以自己编写规则，或使用其它人分享的规则，实现很多高级操作，

比如，打开 玄离199 的视频，就自动点赞。

GKD：
https://github.com/gkd-kit/gkd

#### 2.Xiaomi-BootLoader-Questionnaire

在最近两年的层层加码之后，

小米手机想要解锁 BootLoader，已经变得越来越困难了，

不但要求社区 5 级，还要答各种手机相关的题目，

就连知名玩机软件 太极 和 kernelSU 的开发者【维术】，

在六月份答题时，都折戟沉沙，只获得了 30 分。

Xiaomi-BootLoader-Questionnaire，

是一份 小米 BootLoader 解锁的考试真题，

有志于解锁手机的小米用户，可以好好学习一下，争取早日成功。

Xiaomi-BootLoader-Questionnaire：
https://github.com/MlgmXyysd/Xiaomi-BootLoader-Questionnaire/

#### 3.Lux 

Lux 是一款开源的视频下载工具，

它几乎可以从现在所有的 知名视频网站上，下载视频，

感兴趣的可以尝试一下。

Lux：
https://github.com/iawia002/lux

4.geektime-books

极客时间电子书，全部都是各种技术相关的书籍，

足足有 199 本，很多书都非常经典和实用，

由于这个项目的 Star 数足够多，并且书籍的数量 199 和我的名字有缘，

所以就推荐一下。

极客时间：
https://github.com/it-ebooks-0/geektime-books

## 第15期【2024年9月7日-2024年9月14日】

### 软件推荐

很多高校、大型企业、机关单位，都会购买一些常用的正版软件，放在官网上，供内部人员下载使用。

不过如果我们找到了下载页面，即使不是内部人员，也有一部分是可以直接下载使用的。
<br/>
<br/>
<br/>
比如，在搜索引擎搜索 “大学正版软件下载中心”，就能找到很多这样的下载页，

在这些下载页里，提供最多的软件就是各种版本的 WPS，

相对于官网下载的个人版 WPS，

这些版本 基本上 不会有任何广告和弹窗，并且还可能 会有一些更专业的功能，

比如有的可以用 VB 宏，有的会有 1T 云空间，

总而言之，如果你只是想用 文字、表格、PPT 等功能，这些版本会更省心。
<br/>
<br/>
<br/>
在搜索引擎，搜索【WPS政企版合集】、【WPS教育版合集】，就能找到很多分享帖，

感兴趣的可以尝试一下。


### 开源项目

#### 1.PULSE

PULSE 是一个开源的去马赛克算法，也可以把低像素图片变高清，

它适用于各种人脸图片，

具体的原理是，先使用 StyleGAN 生成清晰人脸图，再对生成的 人脸图 低像素化处理，

然后和用户上传的图片做对比，重复运行多次之后，把最像的一张作为结果保存下来。

所以，如果运行次数足够，它有很大概率能还原的非常相似。

PULSE：
https://github.com/adamian98/pulse

#### 2.The Most Dangerous Writing App

这是一款非常危险的写作软件，

使用它写作，可以解决掉你偷懒，和效率不高的问题，

因为在你打字时，如果停止输入超过五秒，屏幕上的字就会变模糊，并在三秒内消失，

所以，为了保留已经写的内容，你必须一直输入，不能停下来，从而被迫提高效率，

The Most Dangerous Writing App：
https://github.com/maebert/themostdangerouswritingapp?tab=readme-ov-file

#### 3.Watt Toolkit

Watt Toolkit 原名叫 Steam++，听名字就知道，这是一款 Steam 工具箱，

首先，它可以通过本地反代的方式，提供网络加速功能，解决 Steam 国内访问缓慢的问题，

然后，是很多专门为 Steam 开发的功能，比如 管理和快速切换 游戏平台账号，

查看 Steam 库存、监控下载进度，实现下载完成后自动关机、

管理云存档、挂机游玩时长、优化游戏体验等等，

如果你经常玩 Steam 游戏，那它有很大概率能帮到你。

Watt Toolkit：
https://github.com/BeyondDimension/SteamTools

## 第14期【2024年8月24日-2024年8月31日】

### 软件分享

MusicFree，是一个开源免费的、多平台的、无广告的，插件化、定制化 音乐播放器，

目前一共支持多个手机、电脑系统，我拿 Windows 版来举一个例子，

安装打开之后，你会发现，几乎所有功能都是空的，

甚至连 排行榜 和 热门歌单 都没法用，

这是因为，它采用了我们之前讲过的【枪弹分离】模式，所有的内容都需要自己安装插件才能使用，
<br/>
<br/>
<br/>
点击插件管理，选择【从网络安装】，输入项目 Readme 中给的这个链接，

就能自动安装上十个插件，

这十个插件，对应了十个平台，然后我们就能听歌了。

没错，这个插件的功能，和某些软件的源是一样的，

这也就意味着，你导入什么网站的源，就能听什么网站的歌，

也就是说在听歌方面，MusicFree 等于是和【阅读】一样的神器，能让你彻底实现音乐自由。
<br/>
<br/>
<br/>
在任意搜索引擎，搜索 【MusicFree源】，就能找到很多分享帖，喜欢听歌的一定要收藏。

MusicFree：
https://yinghe.app/musicfree-chajian/
https://github.com/maotoumao/MusicFree
https://linux.do/t/topic/90828

### 开源项目

#### 1.HivisionIDPhotos

HivisionIDPhotos，是一个开源的轻量级 AI 证件照算法，

它最主要的功能，就是生成 各种各样 的证件照，

任何尺寸的大小，任意颜色的背景，甚至还能自定义图片的体积，抠图效果也还不错。

因为它是开源项目，所以有人制作了一键启动包，

拿来应急，或者应付非正式的证件照需求，基本上够用了。

HivisionIDPhotos：
https://github.com/Zeyi-Lin/HivisionIDPhotos
https://github.com/zhaoyun0071/HivisionIDPhotos-windows-GUI

#### 2.Upscayl

图片超分算法，也就是把模糊图片变高清的算法，目前已经挺多了，

但大部分都是需要收费，或用起来比较麻烦的，

Upscayl 是一个完全开源免费，且运行在本地的图片超分软件，

目前支持三大电脑系统，使用起来非常简单，

上传图片、选择放大倍数，点开始，图片就会变高清很多倍。

Upscayl：
https://github.com/upscayl/upscayl

#### 3.Umi-OCR

OCR，中文名叫【图像文字识别】，

它可以通过图像识别的方式，把屏幕上任意地方的文字给提取出来，

Umi-OCR 是目前最火的开源 OCR 工具之一，

可以通过在屏幕上截图，或者上传图片的方式，

把图片、视频中不能复制的文字直接提取出来，

识别效果还算不错，用起来也很方便，并且还支持 批量识别 和 保存排版，

是一个很优秀的 OCR 工具。

Umi-OCR：
https://github.com/hiroi-sora/Umi-OCR

## 第13期【2024年8月24日-2024年8月31日】

### 科技软件

不知道你有没有想过，其实我们日常用的很多收费软件，都有可选的替代产品？

比如剪视频用的 PR，就可以选择能免费使用的 Kdenlive 或者 达芬奇来替代，

不想用收费的 PS，如果不是拿来工作，开源的 gimp 和  Krita 也能满足处理图片的需求，

市面上的远程控制软件不喜欢，Rustdesk 可以让你搭建自己的私有服务，

那么，如何找到这种免费的替代软件呢？
<br/>
<br/>
<br/>
AlternativeTo 是一个专门收集 各类软件费替代品 的网站，目前已经收集了十几万款，

我们常用的各种软件，都可以在这里找到替代品，

你还可以按照分类，查看各大 电脑系统、手机系统、浏览器扩展、Web 服务 中，有哪些好用的应用。
<br/>
<br/>
<br/>
OpenAlternative 也是一个查找 软件替代品 的网站，

但不同的是这里收集的都是开源项目，且基本都是优质的开源项目。
<br/>
<br/>
<br/>
目前这两个网站都积极维护、持续更新，内容在快速扩充中。
<br/>
<br/>
<br/>
Similarsites 则是一个寻找相似功能网站的工具，

比如我搜索 百度的网址，它就会给我推荐一些 资讯网站 和 搜索引擎，

输入 youtube，它就会推荐一些视频网站，

输入一些不能提的网址，它也会给推荐不能提的网址。

OpenAlternative（软件开源替代）：
https://openalternative.co/

AlternativeTo（软件免费替代）：
https://alternativeto.net/

Similarsites （相似网站）：
https://www.similarsites.com/

### 科技项目

#### 1.SmartSystemMenu

SmartSystemMenu 是 Windows 上的一个窗口增强软件，

把它安装到电脑上之后，使用右键点击任意软件的窗口栏，就会发现这里多了很多功能，

可以查看窗口的信息、把窗口置顶、把窗口移动到最底层、

对窗口截图、在资源管理器打开程序文件夹、调整窗口的透明度、把窗口在近期任务中隐藏，

一共十几个功能，这些功能很多时候都能提高效率，

部分功能组合起来，也有一些意思的效果，

比如我想上班看小说，可以把小说窗口设置一个透明度，然后在任务中隐藏掉。

SmartSystemMenu（Windows 窗口增强）：
https://github.com/AlexanderPro/SmartSystemMenu

#### 2.Docker-OSX

Docker-OSX 可以让你在 Docker 中，运行 Mac OS X 系统，

这也意味着，你可以随时在 Windows 上运行 macOS，在 Linux 上运行 macOS，在 macOS 上运行 macOS，

并且经过多层转译之后，它还有不错的性能。

不管你是想体验 mac，还是拿来做开发研究都很不错，

这个项目由于太火，本周刚刚被苹果投诉，在 Docker Hub下架，感兴趣的可以自己找一下镜像。

Docker-OSX：
https://github.com/sickcodes/Docker-OSX

#### 3.YesPlayMusic

不知道大家现在有没有在用网易云音乐，对网易云的客户端评价怎么样，

YesPlayMusic 是一个高颜值的第三方网易云电脑客户端，

软件页面非常简约大气，保留了网易云的核心功能，

同时去除了广告和没有意义的模块，

它支持使用网易云账号直接登录，可以替换源激活变灰的歌曲。

并且它除了网页版，还有各大电脑系统的客户端，喜欢用网易云的可以尝试一下。

YesPlayMusic（网易云）：
https://github.com/qier222/YesPlayMusic

## 第12期【2024年8月17日-2024年8月24日】

### 科技软件

本周黑神话悟空正式发布，并且打破了 Steam 单机游戏在线记录，

不知道大家都玩上没，

今天给大家分享一些黑神话的辅助工具，

在支持正版的同时，可以用这些工具提升游戏体验。
<br/>
<br/>
<br/>
游戏发布以来，我看到最多的吐槽就是没有地图，

经常走着走着就迷路，还会错过很多东西，

所以首先要分享的就是两款互动地图，分别来自 游民星空和小黑盒，

两款地图在表现方式和细节上略有不同，

但功能是类似的，都标注了路上会遇到的怪物和各种材料，

大家可以在游玩的时候当作参考。
<br/>
<br/>
<br/>
如果平时玩 动作游戏 或者 魂类游戏 比较少，

可能会感觉黑神话的难度比较高，经常一个 BOSS 很久都打不过，

如果你也遇到这种情况，可以在支持正版的同时，使用这款风灵月影修改器，

它可以修改游戏内的各种属性，

根据自己的实力进行合理调整，能辅助实现最佳游戏体验。
<br/>
<br/>
<br/>
然后，是两个画质补丁，

其中一个可以让非 40 系 N 卡用户，同时开启 DLSS 和 FSR 3.1 帧生成，

使用方式我放在了公屏上，大家也可以参考【南山星】的视频。
<br/>
<br/>
<br/>
另外一个可以降低游戏的锐化，可以让不喜欢过度锐化的玩家，感觉游戏画面更舒服。
<br/>
<br/>
<br/>
最后，还是那句话，如果喜欢，请支持正版。

游民星空互动地图
https://www.gamersky.com/tools/map/wukong/?ref=BZ

小黑盒互动地图
https://web.xiaoheihe.cn/tools/map?game_name=bmw&zoom=8

风灵月影修改器
flingtrainer.com/trainer/black-myth-wukong-trainer

来自：@南山星 使用教程和效果可以看南山星主页视频
非40系N卡用户同时开启 DLSS的超分辨率 +FSR3.1的帧生成
补丁来源：https://www.nexusmods.com/site/mods/738
网盘方便大家下载的地址：https://pan.baidu.com/s/1IIGVbRkpyoYoXxVA6K81Mg?pwd=8hm3

悟空画面调整补丁
转自：https://github.com/Lyall/WukongTweak
补丁网盘地址：https://pan.baidu.com/s/1ZjQZfXC5G_b-m_x2Yg2URA?pwd=1f77

### 科技项目

#### 1.eSearch

这是一款非常强的开源截图工具，拥有常见的各种截图功能，

包括截屏、文字OCR、翻译、贴图、录屏、长截图、简单的图像处理，

目前这个项目还在持续更新优化，

由于之前的截图神器 Snipaste 已经长期摆烂，

所以我认为 eSearch 是它的有效替代者之一。

eSearch：
https://github.com/xushengfeng/eSearch

#### 2.Perplexica

Perplexity 是目前最强的 AI 搜索引擎之一，但它是一个商业项目，
 
而 Perplexica，是 Perplexity 的一个开源替代产品，

拥有和目前绝大多数的 AI 搜索相似的功能，

如果你对 AI 搜索感兴趣，想自己搭建或者实现这样一个的搜索引擎，可以关注此项目。

Perplexica：
https://github.com/ItzCrazyKns/Perplexica

3.rubick

utools，是电脑上一个非常好用的效率工具，

但它目前也是一个商业项目，很多功能都需要开会员才能用，

rubick 是 utools 的一个开源替代产品，

按下快捷键，呼出输入框，输入关键词，它就能快速使用各种功能，

比如，快速启动电脑上的软件，搜索电脑上的文件，

使用 内置插件，还能实现 系统剪切板增强、快速翻译、计算器、录屏 等几十项功能。

rubick：
https://github.com/rubickCenter/rubick

## 第11期【2024年8月10日-2024年8月17日】

### 科技软件

在使用电脑时，有时会需要重装系统，

但是很多人不知道，去哪里找系统镜像，

随便去网上下载，最后很可能得到，一个被预装了大量垃圾软件的系统。
<br/>
<br/>
<br/>
今天，就给大家推荐几个，能下载到 各版本纯净 Windows 镜像的网站。

建议收藏起来，迟早用得到。
<br/>
<br/>
<br/>
最权威的，肯定还是微软自己的网站，也就是 software-download，

但这里，一般只提供比较新的系统，下载流程也比较麻烦，

所以，我更建议使用下边的几个第三方网站。
<br/>
<br/>
<br/>
其中，比较出名的是 i tell you，它已经持续运营了 17 年，

除了 Windows，还提供 macOS，和多种 Linux、Unix 系统镜像

版本也非常齐全，从 XP 到 Win11 都有，并且提供了几乎全部的大版本。

这里提供的是 ED2K 和 BT 地址，可以用专门的下载软件，或者迅雷下载。
<br/>
<br/>
<br/>
这样的网站，还有很多，比如这个 山己几子木，

也是提供了各种版本的 Windows 镜像，

除了迅雷链接，还有百度云盘、阿里云盘两种下载方式。
<br/>
<br/>
<br/>
系统库、HelloWindows，也是类似的纯净系统下载网站，都很不错。

微软系统镜像下载：
https://www.microsoft.com/zh-cn/software-download

i tell you：
https://next.itellyou.cn/

山己几子木：
https://msdn.sjjzm.com/

系统库：
https://www.xitongku.com/

### 2.科技项目

#### 1.FLUX

本周最火的开源项目，应该就是它了，

这是一个开源的 AI 画图模型，在外网已经被玩疯，

连 Hugging Face 的 Trending 榜单，都被它屠榜。

FLUX 支持中文输入，拥有超强的 语言理解能力 和文本控制能力，

且在 清晰度、细节 方面，都是目前最顶级的存在，连文字都能准确生成。

比如这套使用 FLUX 生成的经典照片，不管是表情、手指、还是人物细节，都几乎无懈可击。

FLUX在线体验：
https://replicate.com/black-forest-labs

FLUX整合包：
https://pan.baidu.com/s/1yObLpTp8iXA7xaXYiHCxkw?pwd=yfhm（来自下1个好软件）

FLUX模型：
https://huggingface.co/spaces/black-forest-labs/FLUX.1-schnell

#### 2.learn_python3_spider

爬虫，是一类程序的统称，

它可以让你通过代码，自动把 网页、APP 上的数据，批量保存下来。

比如，自动下载视频网站的视频，保存壁纸网站的图片，获取网页上的各种文字，

learn python3 spider 是一个爬虫教程项目，

它会从 0 开始，教你一步步的学会爬虫，以及各种常用的爬虫手段，

如果你对爬虫感兴趣，可以学一下。

learn_python3_spider：
https://github.com/wistbean/learn_python3_spider?utm_source=gold_browser_extension

#### 3.pyvideotrans
 
py video trans 是一个视频翻译配音工具，

它的主要功能是，把 A 语言的视频，翻译成另外一种语言的视频，并自动配音和添加字幕。

整个项目主要分为三部分，

一：识别视频语音内容，并去除声音。

二：翻译文字。

三：把翻译成的文字转译成语音，再添加到视频中。


其中每一步，都有很多模型可以选择，

你可以根据自己的喜好和实际效果，选择最合适的模型。

pyvideotrans 目前一共支持 20 多种语言，非常强大。

pyvideotrans：
https://github.com/jianchang512/pyvideotrans?utm_source=gold_browser_extension

## 第十期【2024年8月3日-2024年8月10日】

### 科技软件


之前，我给大家讲过 DNS 的作用，

它在互联网中，就像是一个指路的，可以把域名转换成 IP 地址，

如果没有它，那我们的网络请求，将会无法访问到服务器。

并且，不管是手机还是电脑，DNS 都是可以自定义的。
<br/>
<br/>
<br/>
既然如此，

如果在 DNS 中，把所有广告相关的域名，全部给屏蔽掉，

那是不是就能去除广告呢？

确实是这样。
<br/>
<br/>
<br/>
就像我之前给大家推荐过的 18Bit，它就是采用了这种原理，

安卓、鸿蒙、iOS、Windows、macOS，都能通过简单的修改 DNS 设置，来达到去广告的效果。

比如像安卓设备，只需要在设置中找到 私人 DNS，并填入 18Bit 的域名即可。
<br/>
<br/>
<br/>
类似这样的去广告 DNS 还有很多，清新云 DNS、AdGuard DNS，都可以达到同样的效果。

大厂开发的 NextDNS、DNSPod，也可以订阅 AdGuard 规则，达到去广告的目的，

并且能生成自己的私有链接，更加安全。
<br/>
<br/>
<br/>
如果你有动手能力，甚至可以通过开源的 AdGuard Home，

在服务器或者路由器上，搭建一个自己专属的 DNS。

但注意，这种方式只能去除大部分广告，并不能完全屏蔽，且在部分情况下，可能会对网速有一些影响。

[18Bit：https://go.18bit.cn/](https://go.18bit.cn/)

[清新云DNS：https://ipv4dns.com/](https://ipv4dns.com/)

### 科技项目

#### 1.CodeGeeX 4

之前给大家推荐过很多编程类 AI，

评论区总会有人问，在没有网络的情况下，能不能使用。

最近，我推荐过的、由清华大学开发的 CodeGeeX，

正式开源了它们的 4 系列大模型，支持代码生成、补全。

感兴趣的可以自己离线部署。

[CodeGeeX4：https://github.com/THUDM/CodeGeeX4](https://github.com/THUDM/CodeGeeX4)


#### 2.avp_teleoperate

头部机器人公司宇树科技,开源了一款人形机器人第一视角遥操作方案，

可以通过 Vision Pro 等设备上，远程控制机器人，让它做出和自己同样的动作。

[avp_teleoperate：https://github.com/unitreerobotics/avp_teleoperate](https://github.com/unitreerobotics/avp_teleoperate)


#### 3.Deep-Live-Cam

Deep-Live-Cam 是一个 AI 面部替换的开源项目，

它可以仅仅通过一张图片，就能完成对视频中的人物面部替换，

在复杂的光线下，效果也非常良好。


[Deep-Live-Cam：https://github.com/hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)


#### 4.MiniCPM-V

8 月 6 日，MiniCPM-V 发布了 2.6 版本，

仅需 8b 参数，就能很好的完成 图片理解、视频理解 等多模态任务，

并且在这些方面，超越 GPT-4V 的效果。

而 8B 参数的模型，由于足够小，可以轻松的在个人电脑、甚至手机上运行起来。


[MiniCPM-V：https://github.com/OpenBMB/MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V)


#### 5.CogVideo

CogVideo 是一个文本转视频类 AI 模型，由清华大学开发，

目前已经开源，它生成的视频效果如下：

[CogVideo：https://github.com/THUDM/CogVideo](https://github.com/THUDM/CogVideo)


## 第九期【2024年7月27日-2024年8月3日】

### 科技软件

有一个非常火的开源小说软件，叫做【阅读】，使用它几乎可以免费看各种电子书，

但是，【阅读】本身是没有任何书籍资源的，需要导入书源才能使用。
<br/>
<br/>
<br/>
李跳跳在停更之后，也是需要导入规则，进行复活。
<br/>
<br/>
<br/>
这种软件模式，叫做【枪弹分离】模式，是目前很多资源类软件，为了规避风险常用的模式，

即：软件本体不包含任何内容，需要用户自己导入源才能使用。

比如异次元，是一个可以添加图源的软件，导入漫画网站的源后，就可以看漫画，

TVbox，是一个影视类软件，导入视频源后可以看各种视频和电视直播。
<br/>
<br/>
<br/>
目前，【枪弹分离】的软件越来越多，你可以把你知道的在评论区分享。
<br/>
<br/>
<br/>
分享各种软件源的 网站 和 帖子 也很多，

比如这个【源仓库】，就整理了五个资源类软件的源，可以一键生成链接订阅。


[源仓库：https://www.yckceo.com/](https://www.yckceo.com/)


### 科技项目

#### 1.Github Ranking

GitHub，是没有官方的排行榜的，只有一个趋势榜，

Github Ranking 是一个仓库排名的项目，它每天会自动抓取数据，并制作排行榜，

其中有按 Star 数排行的榜单，按 Fork 数排行的榜单，各大语言的榜单，

如果你想知道哪些项目在 Github 最火，那关注这一个项目就够了。

[Github仓库排名，每日自动更新：https://github.com/EvanLi/Github-Ranking](https://github.com/EvanLi/Github-Ranking)


#### 2.30-Days-Of-Python

这个项目的作用看名字就知道，30 天学会 Python，

并且它有官方的简体中文版本，但目前好像还没有翻译完，正在更新。


[30 天学会 Python：https://github.com/Asabeneh/30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python)


#### 3.PlayCover

PlayCover 是一个 Mac 系统上的 iOS 模拟器，

可以让我们在系统高于 12.0，且是 M 系列芯片的 Mac 设备上，运行 iOS 平台的软件和游戏，

并且，支持和安卓模拟器类似的，鼠标键盘操作。


[PlayCover Mac上运行 iOS 游戏：https://github.com/PlayCover/PlayCover](https://github.com/PlayCover/PlayCover)


#### 4.MinerU

MinerU 是一个一站式数据提取工具，

它可以把 PDF、网页、电子书文献 中的内容提取出来，转换成 Markdown 格式，并自动排版。

[一款一站式、开源、高质量的数据提取工具：https://github.com/opendatalab/MinerU](https://github.com/opendatalab/MinerU)


#### 5.awesome

之前给大家分享过，awesome 是在 Github 上最大的一个项目系列，

这个系列的项目很多都非常实用，

比如，我想找 Windows 上好用的软件，那就可以搜 awesome windows，这里全都是各种好用资源。

比如，我想找 Java 相关的内容，就可以搜 awesome java，这里全都是 Java 开发的优质软件。

而名字就叫 awesome 的这个项目，则收集了各种类型的优质开源资源，

就像是开源界的永乐大典和四库全书，足足有 317 k Star。

[awesome：https://github.com/sindresorhus/awesome](https://github.com/sindresorhus/awesome)


## 第八期【2024年7月20日-2024年7月27日】

### 科技软件

不知道大家平时有没有遇到过这样的场景，

在各种平台看到有意思的视频、帖子，

然后用 APP 的分享功能，把它直接发送给好友看。
<br/>
<br/>
<br/>
但你可能不知道的是，在你分享的各种链接中，

其实被加入了大量的参数，而这些参数，却很有可能会暴露你的信息，

比如像这个链接，其中就包含了系统类型、APP 版本号，

甚至还可能包含了 你的账号名称、主页地址。
<br/>
<br/>
<br/>
有一个网站，叫做 “你分享的链接泄露隐私了吗 ?”，就可以专门检测这些链接中是否泄露了数据。

比如我在某书，通过分享功能，随便复制一个其它人帖子的链接，

粘贴进去检测一下，它直接就检测到了我在某书的名字，和我的首页。
<br/>
<br/>
<br/>
并且，这种情况还是大面积存在的，这个网站目前已经支持了 17 个平台的检测。
<br/>
<br/>
<br/>
如果你在各大平台的账号是隐私账号，经常发不想让熟人知道的内容，那一定要注意这个问题。


[你分享的链接泄露隐私了吗：https://uid.ejfkdev.com/](https://uid.ejfkdev.com/)


### 科技项目


#### 1.Stirling-PDF

PDF 格式的文件，在诞生时，就被有意设置成了几乎不可编辑，

所以，和 PDF 相关的软件，尤其是能编辑 PDF 的软件，大都需要付费，

Stirling PDF 是一个开源免费的、操作 PDF 文件的项目，

可以对 PDF 文件进行拆分、合并、重组、旋转、转换格式，等各种操作。

你可以把它放在自己的电脑上使用，也可以部署在服务器上，让大家一起用。

[Stirling-PDF：https://github.com/Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)


#### 2.Llama 3.1

Meta 开源了最新的大模型，Llama 3.1，

一共有 8B、70B、405B 三个版本，

其中的 405B 版本，在多项测试中，表现都非常优秀，

甚至可以和 GPT-4o、Claude 3.5 Sonnet 等头部闭源大模型媲美。

[Llama 3.1：https://llama.meta.com/](https://llama.meta.com/)


#### 3.ShareDrop

ShareDrop 是一个受 苹果 AirDrop 启发的开源项目，

在同一个局域网下，两台设备同时打开它的网址，就能互相分享文件。

[ShareDrop文件共享：https://github.com/szimek/sharedrop](https://github.com/szimek/sharedrop)

#### 4.UTM

我上周给大家分享过，UTM 模拟器在 APP Store 上架的消息，

UTM 其实是一个开源的项目，

它的功能是在 Mac、iPhone 和 iPad上运行 Windows、Linux 等系统，

如果你对模拟器感兴趣的话，可以关注一下这个项目。

[UTM模拟器&虚拟机：https://github.com/utmapp/UTM](https://github.com/utmapp/UTM)

## 第七期【2024年7月13日-2024年7月20日】

### 科技软件

Everything，是 Windows 上一个非常出名的搜索软件，

使用它，可以瞬间搜索出电脑上的任何文件，

比 Windows 自带的搜索体验要好很多，

但它是一个独立的软件，界面长这个样子，看起来并不算特别好看。

EverythingToolbar，是一个可以将 Everything，无缝集成到 Windows 任务栏的工具。

它可以完美的替换掉 Windows 的搜索功能，

按下快捷键，直接呼出，看起来和自带的开始菜单一样，但功能和 Everything 几乎没有任何区别，

只需要设置一个顺手的快捷键，就能把电脑的搜索体验，带到一个新的高度，

是我认为 Windows 必装的软件之一，非常推荐大家尝试。

[EverythingToolbar搜索软件：https://github.com/srwi/EverythingToolbar](https://github.com/srwi/EverythingToolbar)

### 科技项目

### 1.koroFileHeader

这是一个可以给代码自动添加头部注释、函数注释的 VSCode 插件，

但我认为最有意思的功能是这个，

一键添加佛祖保佑、龙图腾、程序员之歌、喷火神兽，等十几种有意思的注释图案。

[koroFileHeader代码注释：https://github.com/OBKoro1/koro1FileHeader](https://github.com/OBKoro1/koro1FileHeader)

### 2.LivePortrait

这是可灵团队，全新开源的一个视频生成框架，它的作用是，

控制图片中的人物、动物，生成各种面部表情、口型视频，效果非常灵动和真实，

最重要的是，它已经放出了源代码和模型，

是完全开源，并且能任意使用的。

[LivePortrait视频框架：https://github.com/KwaiVGI/LivePortrait](https://github.com/KwaiVGI/LivePortrait)

### 3.mem0

这是一个可以让大语言模型，拥有 超强记忆力、上下文连续性 的开源框架，

和大模型对接之后，你们的任何聊天内容，都能被它牢牢记住并理解，

并且，它不是基于 RAG 技术的，

因为太过实用，还获得了 OpenAI 的投资，

短短开源一天，就迅速登顶 Github，获得了 10k 的 Star。

[Mem0大语言模型记忆层：https://github.com/mem0ai/mem0](https://github.com/mem0ai/mem0)

### 4.HowToCook

程序员做饭指南，这是一个神奇的项目，

由无数的程序员共同努力，长期维护，所以，它充满了程序员风格，

从最基础的油类科普，到如何计算应该做多少菜，各种调料厨具的使用方式，

当然，更重要的还是菜谱，

如果你想学做饭，那这个项目非常值得关注，尤其是前 30 页。

[HowToCook程序员做饭指南：https://github.com/Anduin2017/HowToCook](https://github.com/Anduin2017/HowToCook)

## 第六期 【2024年7月6日-2024年7月13日】

### 科技软件

这，是我在网上随便下载的一个游戏，

可惜，全是日语，根本看不懂。

而当我把它，拖动到这个神奇的输入框上后，奇迹发生了，

在屏幕上，出现了一个对话框，会实时把游戏中的内容，翻译成汉字。
<br/>
<br/>
<br/>
这，是一个漫画，

很可惜，不是中文的，我还是看不懂，

而这时，我点一下这个按钮，然后框选一下，汉字就出来了。

甚至我把图片导进去，还能帮我直接完成汉化，

把图片再导出来，一个人就是汉化组。
<br/>
<br/>
<br/>
没错，现在的翻译软件，已经强大到了这种地步。
<br/>
<br/>
<br/>
第一个翻译游戏的软件，叫做 RenpyThief，来自 up 主林虎，

它采用内存注入的方式进行翻译，

不但支持各种 Galgame 游戏，甚至连 Unity、Renpy、RPGMaker MV 等一系列引擎都能通通搞定。
<br/>
<br/>
<br/>
第二个翻译漫画的软件，叫做团子翻译器，

它采用的是 OCR 文字识别，识别屏幕上的内容，

所以，不光是图片，

就连游戏、文本，它也通通都能使用。
<br/>
<br/>
<br/>
类似的翻译器还有很多，比如御坂翻译器 和 Luna 翻译器，可以用注入和 OCR 两种方式，

所以能支持市面上绝大部分游戏、漫画的翻译。

MTool 和 VNR 这两个是专门翻译游戏的，

它们都开发了很久，功能非常强，也有丰富的教程和生态。

最近又有一个新开源的翻译器，叫做 comic-translate，是专门翻译漫画用的，

并且因为使用了 GPT4，所以一共支持足足十种语言。

[RenpyThief：https://lion.craft.me/RenpyThief](https://lion.craft.me/RenpyThief)

[团子翻译器：https://github.com/PantsuDango/Dango-Translator](https://github.com/PantsuDango/Dango-Translator)

[mtool：https://trs.mtool.app/release.php?lang=chs](https://trs.mtool.app/release.php?lang=chs)

[VNR 翻译器：https://e-sim.org/article.html?id=98724](https://e-sim.org/article.html?id=98724)

[luna 翻译：https://github.com/HIllya51/LunaTranslator](https://github.com/HIllya51/LunaTranslator)

[漫画翻译：https://github.com/ogkalu2/comic-translate/blob/main/docs/README_zh-CN.md](https://github.com/ogkalu2/comic-translate/blob/main/docs/README_zh-CN.md)

[御坂翻译器：https://github.com/hanmin0822/MisakaTranslator](https://github.com/hanmin0822/MisakaTranslator)

### 科技项目

#### 1.Paints-Undo

这是 ControlNet 作者开源的全新项目，

它的功能是，根据图片，生成绘画的过程，

包括线稿、着色、阴影等各个步骤，

目前，秋葉大佬已经做出了整合包，感兴趣的可以试试。

[Paints-UNDO 生成AI绘画过程：https://github.com/lllyasviel/Paints-UNDO](https://github.com/lllyasviel/Paints-UNDO)

#### 2.Awesome-AITools

之前给大家分享过，在 Github 上，有一系列 Awesome 开头的项目，

Awesome-AITools 就是其中之一，这个仓库整理了大量 AI 相关的实用工具。

一共有几十种分类，

包含 大语言模型、搜索引擎、阅读、写作、编程、画图、语音识别 等各种领域，

当你需要 AI 工具的时候，可以先到这里看看有没有合适的。

[Awesome AI Tools：https://github.com/ikaijua/Awesome-AITools](https://github.com/ikaijua/Awesome-AITools)

#### 3.linux-command

使用过 Linux 系统的都知道，在 Linux 上有大量的命令，

尤其是在服务器领域，几乎完全是靠命令操作。

但人类的记忆是有限的，很少有人能把他们都记下来，

Linux Command 是一个 Linux 命令大全搜索工具，

一共收集了 580 多条 Linux 命令，

每一个都有详细的介绍、选项、参数、示例，

当你需要查询 Linux 命令时，到这里搜一下准没错。

[Linux命令大全：https://github.com/jaywcjlove/linux-command](https://github.com/jaywcjlove/linux-command)

#### 4.Dive into Deep Learning

动手学深度学习，这是一个面向中文读者的人工智能教材，

从最基础的数学，到各种技术的介绍、应用，

内容非常详尽可靠，又提供足够的技术深度，

已经被全球 70 多个国家、500 多所大学，当做教材，用来教学使用。

[动手深度学习：https://github.com/d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh)

#### 5.wechat-bot

不知道你有没有想过，把自己的微信接入大模型，帮你自动回复消息呢？

wechat-bot 就是这样的一个工具，

并且，它功能还不止如此，

还能用它来管理好友和群，或者检测有哪些人删除了你。

[微信机器人：https://github.com/wangrongding/wechat-bot](https://github.com/wangrongding/wechat-bot)

#### 6.CosyVoice

这是阿里刚刚开源的一个文本转语音工具，

效果非常真实，情感丰富、媲美真人，并且能控制情绪和音色克隆，

下边是它的一小段演示。

[CosyVoice：https://github.com/FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice)

#### 7.MAA Assistant Arknights

这是一个明日方舟的游戏小助手，基于图像识别技术实现，可以一键完成全部日常任务，

如果你是明日方舟玩家，那非常值得试一下。

[明日方舟小助手：https://github.com/MaaAssistantArknights/MaaAssistantArknights](https://github.com/MaaAssistantArknights/MaaAssistantArknights)

## 第五期【2024年6月29日-2024年7月6日】

### 科技软件

近期，中国移动推出了垃圾短信防骚扰功能，

在【中国移动高频骚扰电话防护】公众号即可设置，

打开这个功能后，可以通过填写号码，一键屏蔽指定号码的短信，

还能勾选不同的行业，一键屏蔽指定行业的短信。
<br/>
<br/>
<br/>
屏蔽生效后，用户将不会再收到对应短信，但是可以在【中国移动高频骚扰电话防护】内手动查询。

在这儿，不但可以屏蔽骚扰短信，骚扰电话的屏蔽功能也早已上线，

可以通过号码设置黑白名单，也可以屏蔽指定行业，或者号码段，还能通过亲情防护功能，给家人也开启防骚扰。
<br/>
<br/>
<br/>
实际上，其它运营商也有类似的服务，电信用户可以在【天翼防骚扰】中开启，

联通用户可以在【联通助理】中开启。

除了骚扰防护，三大运营商还有一些其它的服务，比如联合工信部和各大互联网公司推出的一证通查，

可以通过身份信息，一键查询自己名下的手机卡数量，

通过手机号信息，一键查询在各大互联网平台的账号，并且支持解绑和投诉。

### 科技项目

#### 1.generative-ai-for-beginner

这是由微软制作的生成式 AI 入门课，

一共 18 节课程，学完之后，你就能了解什么是 生成式人工智能 和 大型语言模型，

怎么构建一个生成式 AI，怎么使用 RAG 技术，怎么进行微调等等，

通过这些课程，你对生成式 AI 的理解，就能超越大部分人，

除了这个项目，微软还开源了很多其它的课程，包括机器学习、数据科学、Web 开发、物联网等等。

[generative-ai-for-beginner：https://github.com/microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)

#### 2.public-apis

这是一个开源的公共 API 收集项目，

公共 API，一般是某些组织或者个人免费开放给大家使用的 API，

调用这些 API，就能免费获取他们提供的数据和服务，

比如查询天气信息、查询汇率信息、查询 IP 地址。

这个项目收集了几十个行业，近千个 API，里边不仅有实用的，还有好玩的，

比如像这个叫 HTTP Cats 的热门 API，它会用不同的小猫的图片，表达不同的HTTP状态。

这个项目由于太过实用，目前在 GitHub 已经有了 298 k Star，是 GitHub Star 数最多的项目之一。

[public-apis：https://github.com/public-apis/public-apis](https://github.com/public-apis/public-apis)

#### 3.GraphRAG

这是微软刚刚开源的一个新一代 RAG 框架，

相对于传统的 RAG，GraphRAG 拥有多方面的优势，

如果你是一个 AI 相关的开发者，这个项目值得关注。

[graphrag：https://github.com/microsoft/graphrag](https://github.com/microsoft/graphrag)

#### 4.Free Programming Books

这个项目汇集了大量的免费编程书籍、在线课程等资源，

在计算机方面，可以说是无所不包、无所不有，

Java、Python、C 语言、C++，各种编程语言，

操作系统、大数据、数据库多种领域。

这个项目的 Star 数也非常夸张，足足有 326 k，就连中文翻译版，都有 100 多 k，

属于是 GitHub 必关注项目之一。

[Free Programming Books：https://github.com/justjavac/free-programming-books-zh_CN](https://github.com/justjavac/free-programming-books-zh_CN)

#### 5.freeCodeCam

freeCodeCam 是一个免费学习编程的开源项目，

涵盖各种 Python、前端、数据库、数据分析、信息安全、机器学习 等多方面，

目前该项目在 Github 上有 393k 的 Star，应该是 Star 数最多的项目。

[freeCodeCam：https://github.com/freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)

## 第四期 【2024年6月22日-2024年6月29日】

### 科技软件-各种模拟器

在手机上，其实有很多模拟器软件，可以让你玩童年怀旧游戏、掌机游戏、甚至电脑游戏，

比如我之前讲过的 Termux，可以用它在手机上运行 Linux 系统，安装 Python、Java、MySQL 等软件，

还能使用桌面环境，运行 VS Code、WPS 等桌面软件。
<br/>
<br/>
<br/>
Winlator 是一个在手机上的 Windows 模拟器，我之前已经详细讲过一次，

可以在手机上模拟 Windows 环境，直接玩电脑游戏，甚至 3A 大作。

掌机和怀旧游戏的模拟器则更多。

比如像本世代最火的掌机 Switch，

就有 Yuzu（Suyu）（被任天堂告了但还能用），Ziunx，Sudachi 等多款模拟器，

动森、塞尔达，都可以在手机上玩。
<br/>
<br/>
<br/>
爱吾游戏盒，应该是最良心的模拟器软件，

在它上边，可以玩 PSP、PSV、 PC、GBA、塞班 等 30 多种老游戏机、掌机上的游戏，

包括魂斗罗、各种版本的口袋妖怪、合金弹头、狂野飙车、侠盗猎车手等等，

基本上你小时候玩过的游戏，都能在这里玩到，童年回忆拉满。
<br/>
<br/>
<br/>
小马模拟器，也内置了 20 种童年的掌机和游戏机，

包括街机、3DS、PS2、Java 等，游戏非常齐全。
<br/>
<br/>
<br/>
类似的软件还有小鸡模拟器、悟饭游戏厅等，都挺不错，非常适合情怀党。

[termux：https://termux.dev/cn/index.html](https://termux.dev/cn/index.html)

[Winlator：https://winlator.org/]([https://winlator.org/](https://winlator.org/))

[爱吾游戏盒：https://m.25game.com/]([https://m.25game.com/](https://m.25game.com/))

[小马模拟器：http://www.ponyemu.com/index_m.html](http://www.ponyemu.com/index_m.html)

### 科技项目

#### 1.RTranslator

电影中的同声传译，被一个开源项目实现了，

只需要对着自己的手机说话，AI 就会实时翻译成对方能听懂的语言，

显示在对方的手机屏幕上，同时进行语音播报。
<br/>
<br/>
<br/>
它叫 RTranslator，是全球首款开源的实时翻译软件，支持几十种语言。

除了上边的对话模式，它还有对讲机模式，双方对着同一个手机说话，AI 会自动翻译，

适合在国外拿来问路，购物时和店员交流，

也支持传统的翻译功能，直接翻译文本。

[RTranslator翻译：https://github.com/niedev/RTranslator](https://github.com/niedev/RTranslator)

#### 2.Duix

近期，硅基智能开源了全球首个 AIGC 数字人项目，

该数字人可以比较简单的在本地部署，对网络依赖比较小，

适合多种场景，能实时交互、直播，拥有真人级的表现，

并且对算力要求不高，手机、平板、电脑都能运行。

该项目还提供了详细的文档，供开发者二次开发。

首批一共开放了十几个数字人形象，下边是其中一个的 Demo。

[Duix数字人：https://github.com/GuijiAI/duix.ai](https://github.com/GuijiAI/duix.ai)

#### 3.MimicBrush

选中图片中的部分区域，再上传一张参考图，AI 就能自动融合。

也可以只迁移纹理，给选中区域更换贴图，

还能对图片进行更多处理，给人物换衣服、给衣服换图案、给物体换背景，

它叫 MimicBrush，由阿里和清华大学团队共同开发，目前已经开源。

[MimicBrush图像处理：https://github.com/ali-vilab/MimicBrush](https://github.com/ali-vilab/MimicBrush)

#### 4.Microsoft-Activation-Scripts

MAS 项目再次登顶，它的功能从名字就能看出来，

用脚本永久激活微软产品，包括 Windows、Office 等。

这种项目能在微软的 Github 上存在这么久，并且有 80 多 k Star，不得不说微软是有开源精神的。

[MAS微软激活：https://github.com/massgravel/Microsoft-Activation-Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts)

## 第三期【2024年6月15日-2024年6月22日】

#### 1.广告滚蛋

Win11 更新以来，微软虽然增加了很多新功能，但也强行在系统中塞入了不少广告，

广告滚蛋，就是一个可以一键关闭这些广告的开源项目，

只需要勾一下 文件管理器广告、开始菜单广告、锁屏界面广告，通通说再见。

[广告滚蛋原版：https://github.com/zetaloop/OFGB](https://github.com/zetaloop/OFGB)

[广告滚蛋汉化版：https://github.com/zetaloop/OFGB](https://github.com/zetaloop/OFGB)

#### 2.PowerToys

微软开源的一个系统工具套装，提供了很多大家想要，但 Windows 没有的功能。

PowerToys Run 快速启动器，只需按下快捷键，然后打字，

就能快速搜索电脑上的 软件、文件、并且能执行命令。

文本提取器，按下快捷键，轻轻框选，电脑屏幕上任何文本都能提取出来。

Keyboard Manager 快捷键管理，自由更换电脑上的快捷键。

PowerRename 批量重命名，选中多个文件，对它们批量重命名。

类似这样的功能，它足足有几十个，很多都非常好用，最了解微软的，还是微软。

[PowerToys：https://github.com/microsoft/PowerToys](https://github.com/microsoft/PowerToys)

#### 3.CopyQ

在 Windows 系统上，按下 Crtl + V 是粘贴，按下 Win + V 是打开剪切板，可以管理之前复制的内容，

但这个剪切板功能较少，并不算非常好用，比如：没办法永久保存，没法办搜索。

CopyQ 是一个开源的剪切板增强工具，它可以永久保存剪切板内容，

可以对之前复制的内容搜索，能打标签，支持多标签页，可以直接保存剪切板中的图片，

还能创建命令，添加脚本，总之就是非常好用。

[CopyQ：https://hluk.github.io/CopyQ/](https://hluk.github.io/CopyQ/)

#### 4.可信镜像中心

前段时间很多国内的 Docker 镜像站下线，但还是有一些能用的，

比如这个由 开放原子开源基金会牵头，华为等多家企业参与的 可信镜像中心，

就致力于给大家提供安全可信的镜像，

但比较遗憾的是，从数量上来看，目前的可信镜像还不算太多，只有 300 多个，且基本上都是基础镜像，

希望各位开源作者多多努力，早日达到可信级别。

[可信镜像中心：https://atomhub.openatom.cn/](https://atomhub.openatom.cn/)

#### 5.开源模型 Index-1.9B

6 月 18 日，B 站开源了它们的大语言模型 Index-1.9B，

6 月 18 日，开源大语言模型 Index-1.9B 发布，

由于使用了大量互联网语料训练，

该模型主打 懂互联网 和 趣味性，特别了解 ACG 梗，尤其擅长阴阳怪气和玩抽象。

[Index-1.9B大模型：https://huggingface.co/spaces/IndexTeam/Index-1.9B](https://huggingface.co/spaces/IndexTeam/Index-1.9B)

[Index-1.9B大模型 Github：https://github.com/bilibili/Index-1.9B](https://github.com/bilibili/Index-1.9B)

###

## 第二期【2024年6月9日-2024年6月16日】

无

## 第一期【2024年6月3日-2024年6月9日】

#### 1.ChatTTS

全新的语音生成模型，ChatTTS 近期在开源社区爆火，短时间内就收获了 20 多 k Star，

ChatTTS 生成的语音效果非常真实，几乎和真人难以区分，并且可以添加笑声、停顿、语气词，

项目作者本人称，该项目的效果已经突破了开源天花板，并且，目前放出的还不是最强版本。

目前基于该项目，已经诞生了大量的周边项目，一个叫 ChatTTS-ui 的项目，也短时间内收获了 3.4 k Star，

该项目支持 ChatTTS 在各大系统上的一键运行，并且提供了好用的 UI 界面，感兴趣的可以进行尝试。

[ChatTTS：https://github.com/2noise/ChatTTS](https://github.com/2noise/ChatTTS)

[ChatTTS webUI：https://github.com/jianchang512/ChatTTS-ui](https://github.com/jianchang512/ChatTTS-ui)

#### 2.GLM4、Qwen2开源

清华的 GLM 和 阿里的千问，本周纷纷开源了自己的全新版本，GLM4 和 Qwen2，

其中 GLM 拥有 长文本、多语言、工具调用、多模态等能力，目前在 Github 已经收获了 2.3k Star，

Qwen2 拥有 代码、数学、长文本等能力，目前在 Github 拥有 4k Star。

[GLM-4：https://github.com/THUDM/GLM-4](https://github.com/THUDM/GLM-4)

[Qwen2：https://qwenlm.github.io/zh/blog/qwen2/](https://qwenlm.github.io/zh/blog/qwen2/)
