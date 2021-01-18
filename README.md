# 我的世界开发者中文指南
![](https://img.shields.io/badge/license-CC--BY--SA--4.0-green) ![](https://img.shields.io/github/stars/Mouse0w0/MinecraftDeveloperGuide) [![](https://img.shields.io/badge/%E5%A4%87%E7%94%A8%E5%9C%B0%E5%9D%80-Gitee-red)](https://gitee.com/Mouse0w0/MinecraftDeveloperGuide)

**我的世界开发者中文指南的维护需要各位中文开发者的共同努力，欢迎各位[在此](https://github.com/Mouse0w0/MinecraftDeveloperGuide/issues/new)提交各类我的世界开发相关教程、资料、文档。**

## 目录
- [新手的疑问](#新手的疑问)
- [提问的方法](#提问的方法)
- [Java基础教程](#java基础教程)
- [Forge模组开发](#forge模组开发)
- [Bukkit/Spigot插件开发](#bukkitspigot插件开发)
- [BungeeCord插件开发](#bungeecord插件开发)
- [Sponge插件开发](#sponge插件开发)
- [Fabric模组开发](#fabric模组开发)
- [LiteLoader模组开发](#liteloader模组开发)
- [基岩版开发](#基岩版bedrock-edition开发)
- [PocketMine插件开发](#pocketmine插件开发)
- [Nukkit插件开发](#nukkit插件开发)
- [其他开发资源](#其他开发资源)
- [版权声明](#版权声明)

## 新手的疑问
初学者都有很多疑问，在这里对这些疑问进行一一解答。

- 我英语不好，可以学习编程吗？  
对于初学者来说，英语不是主要的障碍，国内有着充足的中文教程。但在接下来的学习过程中，需要阅读大量的英文文档，所以还是需要有一些英语基础和理解学习能力，配合翻译工具（如百度翻译）进行理解。

- 我数学不好，可以学习编程吗？  
对于初学者来说，有必要掌握数学逻辑思维和解决问题的思路，这些能力都在数学学习中得到锻炼，想必学习编程的人数学成绩肯定不错。初学者不需要多高的数学知识水平，但在未来的学习过程中需要更高级的数学知识，应随时做好接受学习新知识的准备。

- 我想学习编程，大佬可以教教我吗？  
一般我是拒绝的，我认为学习是互相促进的过程，而不是单方面的输出，并且我也有很多事情要做。不仅是我，绝大多数人都会拒绝。

- 学习编程是使用IDE好还是Notepad好？  
最近看到有人在争论这个问题，使用IDE是新手的不二选择。

- 好吧，我自学编程，有问题可以问大佬吗？  
可以，但是我拒绝回答书中的基础问题和可以通过搜索引擎解决的问题。

- 自学编程是看书好还是看视频好？  
萝卜青菜，各有所爱，关键是看哪种方式能让你更好理解和学习。我个人是喜爱书本，可以随时查阅资料，非常方便。

- 我学习了很久，但没有成效，我是不是没有天赋？    
我个人觉得对于入门的学习来说，天赋对于学习的影响微乎其微，如果你的学习效率低下，考虑是不是以下原因：
  - 单纯的努力不足，三天打鱼两天晒网。如果不能改正，不如考虑干点别的。
  - 数学逻辑思维和解决问题的能力不足。这个可以学习一些简单易懂的教程，看看视频等，慢慢锻炼，没有任何捷径。
  - 学习方法不对，主要是练得少。只翻书和看视频是没有用的，必须配合大量的练习。个人推荐的方法是：
    - 看完书以后把书上给出的例题再敲一遍，不是照着书上写。
    - 做几个自己感兴趣的项目，在做自己感兴趣的事情的时候才有动力学习。
    - 对于枯燥乏味的课后习题，也应该尝试做一遍，并思考各行代码的效果。
    - 将自己学到的知识用简单的文字形式记录下来，建议使用博客或日志。
    - 对于自己不懂的问题，先看看书和视频，再使用搜索引擎如百度谷歌，最后才询问他人。
    
- 我已经Java入门了，也能自己写一些简单的小程序了，该如何提高自己呢？    
当你Java基本入门，具有一定的编码能力了，可以通过以下多种途径提高自己：
  - 编写一个自己不怎么知道实现的程序，并在编写过程中通过搜索引擎的帮助学习。
  - 阅读别人的源代码和设计文档，了解别人的编码和设计思想，提升自己的编码水平。
  - 学习编码规范（如《代码整洁之道》）、设计模式（如《大话设计模式》）、软件架构（如《架构简洁之道》）和一些重要的类库（如Guava、Commons、OpenGL、Netty）。

## 提问的方法
当你遇到**使用搜索引擎、查阅相关文档、进行Debug（如果没有做过上述操作的话，请立刻去做）** 也无法解决的问题的时候，你可能会向别人求助。现在就来讲讲如何正确提问。

当你进行提问时，请保证你准确提供了以下信息：      
- 准确的描述你的需求和实际问题情况。
- 准确的描述你所在的平台的信息。例如：        
  - Java 版本
  - 所用开发工具（IDE）
  - MineCraft 版本
  - Bukkit/Spigot/Forge/Sponge/Fabric 任一所在平台及其版本
  - 依赖的类库及其版本
- 提供你的源代码，将源代码包括开发环境完整上传至源码托管平台（如Github）。
- 提供你的完整日志、异常输出。

如果你通过发帖的方式提问，请在你的标题也简略的包含问题描述和平台信息。例如《[Forge][1.7.10]载入Mod时出现NullPointerException》

**请记住，不要认为他人的回答是理所应当的**。如果你想学习更多关于提问的方法、技巧、礼仪，看看[提问的智慧](https://lug.ustc.edu.cn/wiki/doc/smart-questions)会给予你许多帮助。

## Java基础教程

### 《Java 8 编程入门(参考)官方教程》
本书分两本，一本是 《Java8编程入门官方教程》，一本是 《Java8编程参考官方教程》。入门版本内容较少，适合新手入门；参考版本内容较多，可以当作参考书使用。  

### 《Java 从入门到精通》
我的Java入门书，但内容有些老旧。

### 《Java 核心技术》
非常不错的一套书，共2本，解决了我的很多疑问，可以当作参考书使用。

### Java 中文在线教程（我绝对不是打广告）
- [易百](https://www.yiibai.com/java/)
- [菜鸟](http://www.runoob.com/java/)
- [W3CSchool](https://www.w3cschool.cn/java/)

### [Java 官方教程（英文）](http://docs.oracle.com/javase/tutorial/)

### [Google Java 编程风格指南](http://hawstein.com/2014/01/20/google-java-style/)

### Java 8 文档（[英文](http://docs.oracle.com/javase/8/docs/api/)/[中文](https://www.matools.com/api/java8)）

## Forge模组开发

### [【1.16】Boson 1.16 Mod 开发教程](https://boson.v2mcdev.com/)
基于1.16的中文模组开发教程。

### [【1.8.9】zzzz的模组开发教程](https://fmltutor.ustc-zzzz.net/)
基于1.8.9的中文模组开发教程。  

### Forge官方文档
介绍了Forge增加的部分功能。[中文文档](http://mcforge-cn.readthedocs.io/zh/latest/)，[英文文档](http://mcforge.readthedocs.io/en/latest/)。

### MDK（Minecraft开发工具包）
- [Forge官方下载](http://files.minecraftforge.net/)
- [【1.14+】ForgeGradleCN — MDK配置新解决方案](https://v2mcdev.com/t/topic/589)
- [【1.7.10+】耗子的MDK离线包](https://www.mcbbs.net/thread-896542-1-1.html)（[百度云盘 提取码：jmrv](https://pan.baidu.com/s/1dE0EJnz)）
- [【1.12.2+】FledgeXu的MDK离线包](https://v2mcdev.com/t/topic/249)（[Github](https://github.com/FledgeXu/ForgeGradleOffline/tags)）

### 国内相关资料
> 有删除线的资料可能存在误导、内容欠缺、表述不清、不够严谨和已有同类更优秀的资料等情况，仅作参考。

- [【1.15】Neutrino 1.15 Mod 开发教程](https://neutrino.v2mcdev.com/)
- [【1.14+】Forge能量系统简述](https://www.mcbbs.net/thread-1034965-1-1.html)
- [【1.13+】1.13+ 中 Forge 与 Bukkit 的通信](https://www.mcbbs.net/thread-873219-1-1.html)
- [【全版本】 原版 / FML CoreMod 开发教程](http://www.mcbbs.net/thread-850737-1-1.html)（[GitBook](https://xfl03.gitbook.io/coremodtutor/)/[码云](http://xfl03.gitee.io/coremodtutor/)）
- [【1.13+】浅析1.13世界生成](http://www.mcbbs.net/thread-846195-1-2.html)
- [【1.12.2】Harbinger Forge 模组开发指南](https://harbinger.covertdragon.team/)
- [【1.7.10-1.12.2】EnumHelper的前世今生](https://www.mcbbs.net/thread-1054951-1-1.html)
- [【全版本】雪崩式的灾难：严重滞后的世界生成](http://www.mcbbs.net/thread-797425-1-1.html)（[Bilibili](https://www.bilibili.com/read/cv545451/)）
- [【全版本】简单网络通信包装类(SimpleNetworkWrapper)](http://www.mcbbs.net/thread-711966-1-1.html)
- [【全版本】GUI开发教程](http://www.mcbbs.net/thread-836858-1-1.html)
- [【1.11.2】基于代码的简单方块/物品贴图渲染](http://www.mcbbs.net/thread-697765-1-1.html)
- [【1.11.2】ChinaCraft2代码详解——大型模组开发笔记](http://www.mcbbs.net/thread-705995-1-1.html)（[Github](https://github.com/UnknownStudio/ChinaCraft2CodeExplanation/wiki)）
- [【1.10.2+】1.10.2以上的方块与物品渲染](http://www.mcbbs.net/thread-733132-1-1.html)
- [Minecraft模组开发知乎专栏](https://zhuanlan.zhihu.com/c_200546589)
- [ustc-zzzz的博客](https://blog.ustc-zzzz.net/)
- [【1.8.9-1.7.2】风之工坊(当风过时的博客)](http://www.windworkshop.cn/?page_id=525)
- [【1.7.10】261Day](https://www.261day.com/minecraft-forge%E6%95%99%E7%A8%8B/)
- [【1.8.9】白玉楼之梦(szszss的博客)](http://blog.hakugyokurou.net/?page_id=126)
- ~~[【全版本】Coremod导论—从切比雪夫多项式说起](http://www.mcbbs.net/thread-822754-1-1.html)~~
- ~~[【全版本】俩车的 Coremod 介绍](http://www.mcbbs.net/thread-849970-1-1.html)~~
- ~~[【1.12.2】3024358263的Minecraft1.12.2模组开发教程](http://www.mcbbs.net/thread-833033-1-1.html)（[备用链接](http://baobaojk.web3v.vip/)）~~
- ~~[【1.12】Re:从零开始的基于Forge的mod开发生活](http://www.mcbbs.net/thread-702594-1-1.html)（[备用链接](https://blog.hookan.top/2017/12/25/forge/)）~~

### 国外相关资料
由于没有详细的阅读过，不做评论，但大都全面，非常推荐外语水平好的同学前去阅读。排名依照支持版本先后排序。
- [【Youtube】【1.15.2-1.12.2】TurtyWurty的模组开发视频教程](https://www.youtube.com/channel/UCicAXLV4w2X6bn2EuM4To4w)
- [【1.15.2-1.12.2】Cadiboo的模组开发教程](https://cadiboo.github.io/tutorials/)
- [【1.15.2-1.12.2】Suppergerrie2的模组开发教程](https://suppergerrie2.com/category/forge-tutorial/)
- [【Youtube】【1.15.2-1.14.2】McJty的模组开发视频教程](https://www.youtube.com/playlist?list=PLmaTwVFUUXiBKYYSyrv_uPPoPZtEsCBVJ)
- [【1.14.4-1.8】TheGreyGhost的模组开发教程](http://greyminecraftcoder.blogspot.com/)
- [【1.14.2-1.9.4】McJty的模组开发教程](https://wiki.mcjty.eu/modding/index.php?title=Main_Page)
- [【Youtube】【1.14/1.12.2】Harry Talks的模组开发视频教程](https://www.youtube.com/channel/UCUAawSqNFBEj-bxguJyJL9g)
- [Darkhax的模组开发教程](https://tutorials.darkhax.net/pages/tutorials/)
- [如何用Kotlin开发模组](http://couchdoescode.blogspot.com/2018/01/minecraft-modding-tutorial-with-kotlin.html)
- [【1.12.2】Cubicodere的模组开发教程](https://cubicoder.github.io/)
- [【1.12.2-1.10.2】shadowfacts的模组开发教程](https://shadowfacts.net/tutorials/)
- [【Youtube】【1.10-1.9】MrCrayFish的模组开发视频教程](https://www.youtube.com/playlist?list=PLy11IosblXIH-OIKa5yYs-KEA2LCohV8g)
- [【Youtube】【1.10-1.9】DisgultGA的模组开发视频教程](https://www.youtube.com/playlist?list=PLkhfw1xGCrIPpgIGXuhFmkjPK5427q4e6)
- [【Youtube】【1.10-1.8】Ash5357的模组开发视频教程](https://www.youtube.com/playlist?list=PLMgygZJ6uqwOSrAaGAOgnUIMAirtPG7w-)
- [【1.10.X】国外网友自己整理的模组开发教程合集](http://www.minecraftforum.net/forums/mapping-and-modding/mapping-and-modding-tutorials/2718726-list-of-minecraft-1-10-x-modding-tutorials)
- [【1.9-1.8.X】结构生成教程](http://www.minecraftforum.net/forums/mapping-and-modding/mapping-and-modding-tutorials/2666351-1-8-x-and-1-9-structure-generation-tutorial)
- [【1.9-1.8.X】复杂结构生成教程](http://www.minecraftforum.net/forums/mapping-and-modding/mapping-and-modding-tutorials/2667034-1-8-x-and-1-9-complex-structure-generation)
- [【1.8-1.6.4】coolAlias的模组开发教程](https://github.com/coolAlias/Forge_Tutorials)
- [【1.8-1.3】wuppy29的模组开发教程](http://www.wuppy29.com/minecraft/modding-tutorials/forge-modding/)
- [【1.8-1.7】TheXFactor117的模组开发教程](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/mapping-and-modding-tutorials/2282788-1-7-1-8-thexfactor117s-forge-modding-tutorials-20)
- [【1.8】Blfngl的模组开发教程](http://forgetutorials.weebly.com/)
- [【1.8】日本的模组开发百科](http://minecraftjp.info/modding/index.php/Minecraft_Modding_Wiki)
- [【1.7.10】jabelar的模组开发教程](http://jabelarminecraft.blogspot.com/)
- [【1.7.10】模组开发教程](http://www.minecraftforum.net/forums/mapping-and-modding/mapping-and-modding-tutorials/1571600-1-7-10-minecraft-forge-modding-tutorials-begginer)
- [【1.7.10】EMX的教程](https://emxtutorials.wordpress.com/)
- ~~[附属模组开发工作空间设置](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/modification-development/2358564-how-do-i-use-another-mod-as-a-dependency-for-my)~~

### 模组示例代码
- [【1.15.2-1.8.9】McJty的模组示例代码](https://github.com/McJty/ModTutorials)
- [【1.15.2-1.8】TheGreyGhost的模组示例代码](https://github.com/TheGreyGhost/MinecraftByExample)
- [【1.12.2-1.8】Choonster的模组示例代码](https://github.com/Choonster/TestMod3)

### 模组开发讨论
很多问题都能在这里解决
- [国外Minecraft论坛Mod开发讨论版块](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/modification-development)
- [Forge官方论坛Mod开发讨论版块](http://www.minecraftforge.net/forum/index.php?board=73.0)
- [Forge官方论坛Mod开发教程版块](http://www.minecraftforge.net/forum/index.php?board=120.0)

### 模组开发相关工具

#### Mod Coder Pack
- [MCPConfig的发布页](http://files.minecraftforge.net/maven/de/oceanlabs/mcp/mcp_config/)
- [MCPConfig的Github仓库](https://github.com/MinecraftForge/MCPConfig)
- [Mod Coder Pack](http://www.modcoderpack.com/)（[旧版本](http://mcp.llbit.se/)）
- [MCPBot Data Exports](http://export.mcpbot.bspk.rs/)

## Bukkit/Spigot插件开发

### [tdiant的Bukkit插件开发教程](http://www.mcbbs.net/thread-808820-1-1.html)

### 官方教程
- [新版本（现Spigot）](https://www.spigotmc.org/wiki/spigot/)
- [旧版本（原Bukkit）](http://wiki.bukkit.org/Plugin_Tutorial)

### Bukkit API开发者文档
- [中文文档](https://docs.windit.net/Chinese_BukkitAPI/)
- [英文文档](https://hub.spigotmc.org/javadocs/spigot/)

### [Spigot官方论坛插件开发讨论版块](https://www.spigotmc.org/forums/spigot-plugin-development.52/)
很多问题都能在这里解决。

### 国内相关资料
> 有删除线的资料可能存在误导、内容欠缺、表述不清、不够严谨和已有同类更优秀的资料等情况，仅作参考。
- [优雅地让命令完整支持TAB补全](https://www.mcbbs.net/thread-1075004-1-1.html)
- [怎样写出一个1.12.2-1.15.2通用支持的插件](https://www.mcbbs.net/thread-1023107-1-1.html)
- [如何编写一个可以保留注释的配置类](https://www.mcbbs.net/thread-1016632-1-1.html)
- [使用IDEA快速调试插件](https://www.mcbbs.net/thread-1004767-1-1.html)
- [Scoreboard教程](https://www.mcbbs.net/thread-897858-1-1.html)
- [创建高版本自定义实体，自定义方块原理与应用](https://www.mcbbs.net/thread-966358-1-1.html)
- [如何问玩家“吾与徐公孰美？”](https://www.mcbbs.net/thread-958674-1-1.html)
- [使用BlockData API来操作Sign](http://www.mcbbs.net/thread-860856-1-1.html)
- [1.13+ 中 Forge 与 Bukkit 的通信](http://www.mcbbs.net/thread-873219-1-1.html)
- [ProtocolLib 教程](http://www.mcbbs.net/thread-568714-1-1.html)
- [Placeholder 教程](http://www.mcbbs.net/thread-570703-1-1.html)
- [Vault API 翻译](http://www.mcbbs.net/thread-615396-1-1.html)
- [[插件NMS教程]PathfinderGoal](http://www.mcbbs.net/thread-682004-1-1.html)
- [如何利用Maven来管理你的插件](http://www.mcbbs.net/thread-711754-1-1.html)
- [BukkitAPI 1.10->1.11改动介绍](http://www.mcbbs.net/thread-648659-1-1.html)
- [在使用NMS的同时支持多个版本](http://www.mcbbs.net/thread-694224-1-1.html)
- [自定义物品模型[1.9+]](http://www.mcbbs.net/thread-694674-1-1.html)
- [编辑，获取并使用木牌](http://www.mcbbs.net/thread-697373-1-1.html)
- [如何给物品增加NBT数据](http://www.mcbbs.net/thread-697478-1-1.html)
- [自定义交互式书本](http://www.mcbbs.net/thread-697788-1-1.html)
- [在插件通过发包(ProtocolLib)打开牌子界面(Sign GUI)](http://www.mcbbs.net/thread-706491-1-1.html)
- [HolographicDisplays API 汉化](http://www.mcbbs.net/thread-721009-1-1.html)
- [Forge与Bukkit之间的通信|数据传输——Messenger类](http://www.mcbbs.net/thread-725571-1-1.html)
- [如何给插件加上更新检查](http://www.mcbbs.net/thread-726821-1-1.html)
- [使用Metrics统计信息](http://www.mcbbs.net/thread-295815-1-1.html)
- [Bukkit Conversation API](http://www.mcbbs.net/thread-619632-1-1.html)
- [如何在JavaIDE上调试你的插件](http://www.mcbbs.net/thread-627399-1-1.html)
- [Pathfinder 实体AI教程](http://www.mcbbs.net/thread-775757-1-1.html)
- [Enchantment API 教程](http://www.mcbbs.net/thread-782859-1-1.html)
- [插件使用MySQL数据库](http://www.mcbbs.net/thread-783267-1-1.html)
- [插件粒子特效教程](http://www.mcbbs.net/thread-837600-1-1.html)([备用链接](https://www.jianshu.com/p/cf267acfe719))
- [ItemMeta 使用教程](http://www.mcbbs.net/thread-782974-1-1.html)
- [自定义实体](http://www.mcbbs.net/thread-811096-1-1.html)
- [聊天组件API——自定义你的聊天消息](http://www.mcbbs.net/thread-812136-1-1.html)
- [如何让插件命令支持Tab自动补全](http://www.mcbbs.net/thread-818199-1-1.html)
- ~~[Valkyrie —— 一个面向中文社区的插件开发教程](https://www.mcbbs.net/thread-1088032-1-1.html)（[Github](https://github.com/ElaBosak233/Valkyrie)/[备用链接](https://valkyrie.ela.ac.cn/)）~~
- ~~(已于1.12弃用)Ebean数据库[(上)](http://www.mcbbs.net/thread-628118-1-1.html)[(下)](http://www.mcbbs.net/thread-636860-1-1.html)~~
- ~~[810587921的插件开发教程](http://www.mcbbs.net/thread-283190-1-1.html)~~
- ~~[Day's Bukkit插件开发教程](http://www.mcbbs.net/thread-439856-1-1.html)~~
- ~~[wyt的Bukkit插件开发教程](http://www.mcbbs.net/thread-614388-1-1.html)~~

## BungeeCord插件开发

### [BungeeCord插件开发中文教程](https://github.com/mousesrc/BungeeCordChineseTutorial)

### [官方Wiki](https://www.spigotmc.org/wiki/bungeecord/)

### [官方插件开发教程](https://www.spigotmc.org/wiki/bungeecord-plugin-development/)

### [BungeeCord官方论坛插件开发讨论板块](https://www.spigotmc.org/forums/bungeecord-plugin-development.23/)

## Sponge插件开发

### [官方网站](https://www.spongepowered.org/)

### [官方论坛](https://forums.spongepowered.org/)

### [官方教程(多国语言，含简体中文)](https://docs.spongepowered.org)

### [官方JavaDoc](https://jd.spongepowered.org/7.2.0/)

### 国内相关资料
- [Minecraft 服务端权限上下文系统及其应用](https://www.mcbbs.net/thread-1007917-1-1.html)

## Fabric模组开发

### [Fabric开发文档中文翻译](https://www.mcbbs.net/thread-904854-1-1.html)

### [官方网站](https://fabricmc.net/)

### [官方Wiki](https://fabricmc.net/wiki/start)

### 国内相关资料
- [用EventLib简化fabric mod开发](https://www.mcbbs.net/thread-1030076-1-1.html)
- [Leader——中文社区的一份Minecraft Fabric教程](https://www.mcbbs.net/thread-964580-1-1.html)
- [Mixin官方Wiki中文翻译](http://mouse0w0.github.io/categories/Mixin/)

## LiteLoader模组开发

### [官方网站](http://www.liteloader.com/)

### [zzzz的LiteMod开发引导(简体中文)](http://www.mcbbs.net/thread-659755-1-1.html)

### [官方源码仓库](http://develop.liteloader.com/public)

## 基岩版（Bedrock Edition）开发
> **相关教程收集中，如有意见和建议欢迎提交Pull Request或Issue。**

### [Minecraft官网附加包（Add-Ons）介绍页面](https://www.minecraft.net/zh-hans/addons)

### [Minecraft中文Wiki“附加包（Add-Ons）”页面](https://minecraft-zh.gamepedia.com/%E9%99%84%E5%8A%A0%E5%8C%85)

### 其他资源
- [下载Minecraft官方资源包](https://aka.ms/resourcepacktemplate)
- [下载Minecraft官方行为包](https://aka.ms/behaviorpacktemplate)
- [基岩版着色器材质文件概述](https://github.com/NovaMods/nova-renderer/wiki/Bedrock-Shaders-Simple-Material-File-Walkthrough)

## PocketMine插件开发

### [PocketMine插件开发中文教程](http://www.mcbbs.net/thread-410243-1-1.html)

### PocketMine其他插件开发教程
- [新API的部分事物的讲解](http://www.mcbbs.net/thread-288333-1-1.html)

## Nukkit插件开发

### [Nukkit插件中文开发教程](http://www.mcbbs.net/thread-552265-1-1.html)

### [Nukkit官方论坛插件开发讨论板块](https://forums.nukkit.io/forums/plugin-development.7/)

## 其他开发资源

### [MCBBS开发讨论板块](http://www.mcbbs.net/forum.php?mod=forumdisplay&fid=479)
有很多有用的东西，可以在这里讨论和提问问题哦!

### [MCBBS开发教程索引贴](http://www.mcbbs.net/thread-54579-1-1.html)

### [V2我的世界开发者论坛](https://www.v2mcdev.com/)

### 搜索引擎
有什么事情为什么不先百度或谷歌呢？
- [百度](https://www.baidu.com)
- [谷歌](https://www.google.com)

### 国内开发讨论交流群
- 国内最大的Minecraft开发讨论群: [284633248](https://jq.qq.com/?_wv=1027&k=5UNCnBj)
- Bukkit/Spigot插件开发交流群: [313498121](https://jq.qq.com/?_wv=1027&k=5aoRGzu)
- Sponge插件开发交流群: [613604130](https://jq.qq.com/?_wv=1027&k=52OlyJ7)
- 耗子的Minecraft开发讨论群: [345538010](https://jq.qq.com/?_wv=1027&k=5wTKLI7)

### [Github](https://github.com/)
世界上最大的社交编程以及代码托管网站，可以在这里查看许多模组和插件的源代码

### [Stack Overflow](http://stackoverflow.com/)
国外的一个关于编程的求助网站

### 其他开发资料
- [聊聊区块和 Ticket](https://www.mcbbs.net/thread-1000001-1-1.html)（[备用链接](https://izzel.io/2020/09/09/chunks-and-tickets/)）
- [怎么看崩溃报告和Timings？](http://www.mcbbs.net/thread-860103-1-1.html)
- [如何使用持续集成帮助开发](http://www.mcbbs.net/thread-716920-1-1.html)
- [[调试辅助]JRebel - 给你+1s|再也不需要重启客户端加全局变量了](http://www.mcbbs.net/thread-694119-1-1.html)
- [Minecraft开发资源Maven仓库国内镜像](http://www.mcbbs.net/thread-800729-1-1.html)

## 版权声明

本作品作者为耗子

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。

转载请附上本作品链接： https://github.com/Mouse0w0/MinecraftDeveloperGuide
