# 我的世界开发者中文指南
![](https://img.shields.io/badge/license-CC--BY--SA--4.0-green) ![](https://img.shields.io/github/stars/Mouse0w0/MinecraftDeveloperGuide)

**点击右上方的“Watch”按钮以实时获取中文指南的更新情况，点击右上方“Star”按钮以支持中文指南的编撰。**

**欢迎各位[在此](https://github.com/Mouse0w0/MinecraftDeveloperGuide/issues/new?template=request.md)提交各类我的世界开发相关教程、资料、文档、类库。**

## 目录
- [新手的疑问](#新手的疑问)
- [提问的方法](#提问的方法)
- [常用网站与资源](#常用网站与资源)
- [Java基础](#java基础)
- [Forge模组开发](#forge模组开发)
- [Bukkit/Spigot插件开发](#bukkitspigot插件开发)
- [BungeeCord插件开发](#bungeecord插件开发)
- [Fabric模组开发](#fabric模组开发)
- [Sponge插件开发](#sponge插件开发)
- [数据包开发](#数据包开发)
- [Java版启动器开发](#java版启动器开发)
- [网易基岩版开发](#网易基岩版开发)
- [基岩版Addons开发](#基岩版addons开发)
- [过时开发资源](#过时开发资源)
- [版权声明](#版权声明)

## 新手的疑问
在此对初学者的一些疑问做出建议，仅供参考。

- 我英语不好，可以学习编程吗？  
对于初学者来说，英语不是主要的障碍，网络上有着充足的中文教程。但在未来的学习过程中，需要阅读英文资料，因此需要有一些英语基础和英语学习能力，并配合翻译工具进行理解。

- 我数学不好，可以学习编程吗？  
对于初学者来说，有必要掌握数学逻辑思维和问题解决的思路。初学者不需要很高的数学知识水平，但在未来的开发中需要更高级的数学知识，应随时做好学习新的数学知识的准备。

- 我想学习编程，大佬可以教教我吗？  
建议自行跟随本指南的资料，并通过搜索引擎克服编程中的难题，如果遇到难以解决的困难再麻烦他人。
  
- 学习编程是使用IDE（集成开发环境）好还是记事本好？  
使用IDE是新手的不二选择。

- 自学编程是看书好还是看视频好？  
萝卜青菜，各有所爱，关键是看哪种方式能使你更好理解和学习。

## 提问的方法
当你遇到**使用搜索引擎、查阅相关文档、进行Debug（如果没有做过上述操作的话，请立刻去做）** 也无法解决的问题的时候，你可能会向别人求助。现在就来讲讲如何正确提问。

**当你进行提问时，请确保你准确提供了以下信息：**
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

## 常用网站与资源

### [我的世界中文论坛开发讨论板块](http://www.mcbbs.net/forum.php?mod=forumdisplay&fid=479)

### [Github](https://github.com/)
全球最大的社交编程与代码托管网站，可以在这里查看许多模组和插件的源代码。

### [码云](https://gitee.com/)
中文社交编程与代码托管网站。

### [Stack Overflow](http://stackoverflow.com/)
全球最大的编程知识分享与学习社区，你可以在此找到许多编程问题的答案。

### 搜索引擎[百度](https://www.baidu.com)/[谷歌](https://www.google.com)
有什么问题为什么不先百度或谷歌呢？

### [Wiki.vg](wiki.vg)
我的世界反向工程与协议参考文档网站，包含各版本网络通信协议、数据格式、Mojang正版验证协议等参考文档。

### 国内开发讨论与交流群
- 国内最大的Minecraft开发讨论群: [284633248](https://jq.qq.com/?_wv=1027&k=5UNCnBj)
- Bukkit/Spigot插件开发交流群: [313498121](https://jq.qq.com/?_wv=1027&k=5aoRGzu)
- Sponge插件开发交流群: [613604130](https://jq.qq.com/?_wv=1027&k=52OlyJ7)
- 耗子的Minecraft开发讨论群: [345538010](https://jq.qq.com/?_wv=1027&k=5wTKLI7)

### [我的世界中文论坛开发教程索引贴](http://www.mcbbs.net/thread-54579-1-1.html)

### [V2我的世界开发者论坛](https://www.v2mcdev.com/)

### 其他开发资料
- [聊聊区块和 Ticket](https://www.mcbbs.net/thread-1000001-1-1.html)（[备用链接](https://izzel.io/2020/09/09/chunks-and-tickets/)）
- [怎么看崩溃报告和Timings？](http://www.mcbbs.net/thread-860103-1-1.html)
- [如何使用持续集成帮助开发](http://www.mcbbs.net/thread-716920-1-1.html)
- [[调试辅助]JRebel - 给你+1s|再也不需要重启客户端加全局变量了](http://www.mcbbs.net/thread-694119-1-1.html)
- [Minecraft开发资源Maven仓库国内镜像](http://www.mcbbs.net/thread-800729-1-1.html)

## Java基础

### 《Java从入门到精通》
广为人知的Java中文入门书籍。

### 《Java 8 编程入门(参考)官方教程》
本书分两册，入门版本内容较少，参考版本内容较多。中文版翻译较为生硬难懂，仅做参考。

### 《Java核心技术》
本书分两册，经久不衰且内容翔实的Java进阶书籍。

### Java 中文在线免费教程
> 内容未经考究，仅供参考。
- [廖雪峰](https://www.liaoxuefeng.com/wiki/1252599548343744)
- [菜鸟](http://www.runoob.com/java/)
- [W3CSchool](https://www.w3cschool.cn/java/)
- [易百](https://www.yiibai.com/java/)

### Java 8 文档（[英文](http://docs.oracle.com/javase/8/docs/api/)/[中文](https://www.matools.com/api/java8)）

### 扩展阅读
> 进一步提高Java编程能力。
- [Google Java 编程风格指南](http://hawstein.com/2014/01/20/google-java-style/)
- 大话设计模式（[豆瓣](https://book.douban.com/subject/2334288/)）
- Effective Java（[豆瓣](https://book.douban.com/subject/30412517/)）
- 代码整洁之道（[豆瓣](https://book.douban.com/subject/4199741/)）
- 架构整洁之道（[豆瓣](https://book.douban.com/subject/30333919/)）

## Forge模组开发

### [【1.16】Boson 1.16 Mod 开发教程](https://boson.v2mcdev.com/)

### [【1.12.2】Harbinger Forge 模组开发指南](https://harbinger.covertdragon.team/)

### [【1.8.9】zzzz的模组开发教程](https://fmltutor.ustc-zzzz.net/)

### Forge官方文档
介绍了Forge增加的部分功能。[中文文档](http://mcforge-cn.readthedocs.io/zh/latest/)，[英文文档](http://mcforge.readthedocs.io/en/latest/)。

### MDK（Minecraft开发工具包）
- [Forge官方下载](http://files.minecraftforge.net/)
- [【1.7.10+】耗子的MDK离线包](https://www.mcbbs.net/thread-896542-1-1.html)（[百度云盘 提取码：jmrv](https://pan.baidu.com/s/1dE0EJnz)）
- ~~[【1.14+】ForgeGradleCN — MDK配置新解决方案](https://v2mcdev.com/t/topic/589)~~
- ~~[【1.12.2+】FledgeXu的MDK离线包](https://v2mcdev.com/t/topic/249)（[Github](https://github.com/FledgeXu/ForgeGradleOffline/tags)）~~

### 国内相关资料
> 有删除线的资料可能存在误导、内容欠缺、表述不清、不够严谨和已有同类更优秀的资料等情况，仅作参考。
- [从实例的角度出发浅谈TileEntitySpecialRenderer](https://www.mcbbs.net/thread-1165415-1-1.html)
- [【1.15.2】自定义发光效果——浅谈着色器和帧缓冲的运用](https://blog.teacon.org/shaders-and-framebuffers.html)
- [【1.15】Neutrino 1.15 Mod 开发教程](https://neutrino.v2mcdev.com/)
- [【1.14+】Forge能量系统简述](https://www.mcbbs.net/thread-1034965-1-1.html)
- [【1.13+】1.13+ 中 Forge 与 Bukkit 的通信](https://www.mcbbs.net/thread-873219-1-1.html)
- [【全版本】 原版 / FML CoreMod 开发教程](http://www.mcbbs.net/thread-850737-1-1.html)（[GitBook](https://xfl03.gitbook.io/coremodtutor/)/[码云](http://xfl03.gitee.io/coremodtutor/)）
- [【1.13+】浅析1.13世界生成](http://www.mcbbs.net/thread-846195-1-2.html)
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
- ~~[【全版本】Coremod导论—从切比雪夫多项式说起](http://www.mcbbs.net/thread-822754-1-1.html)~~
- ~~[【全版本】俩车的 Coremod 介绍](http://www.mcbbs.net/thread-849970-1-1.html)~~
- ~~[【1.12.2】3024358263的Minecraft1.12.2模组开发教程](http://www.mcbbs.net/thread-833033-1-1.html)（[备用链接](http://baobaojk.web3v.vip/)）~~
- ~~[【1.12】Re:从零开始的基于Forge的mod开发生活](http://www.mcbbs.net/thread-702594-1-1.html)（[备用链接](https://blog.hookan.top/2017/12/25/forge/)）~~
- ~~[【1.8.9】白玉楼之梦(szszss的博客)](http://blog.hakugyokurou.net/?page_id=126)~~
- ~~[【1.7.10】261Day](https://www.261day.com/minecraft-forge%E6%95%99%E7%A8%8B/)~~

### 国外相关资料
由于没有详细的阅读过，不做评论，但大都全面，非常推荐外语水平好的同学前去阅读。排名依照支持版本先后排序。
- [【1.16.4-1.12】【Youtube】TurtyWurty的模组开发视频教程](https://www.youtube.com/channel/UCicAXLV4w2X6bn2EuM4To4w)
- [【1.16-1.9】McJty的模组开发教程](https://wiki.mcjty.eu/modding/index.php?title=Main_Page)
- [【1.15-1.12】Cadiboo的模组开发教程](https://cadiboo.github.io/tutorials/)
- [【1.15-1.12】Suppergerrie2的模组开发教程](https://suppergerrie2.com/category/forge-tutorial/)
- [【1.15-1.14】【Youtube】McJty的模组开发视频教程](https://www.youtube.com/playlist?list=PLmaTwVFUUXiBKYYSyrv_uPPoPZtEsCBVJ)
- [【1.15-1.8】TheGreyGhost的模组开发教程](http://greyminecraftcoder.blogspot.com/)
- [【1.14.3/1.12.2】【Youtube】Harry Talks的模组开发视频教程](https://www.youtube.com/channel/UCUAawSqNFBEj-bxguJyJL9g)
- [如何用Kotlin开发模组](http://couchdoescode.blogspot.com/2018/01/minecraft-modding-tutorial-with-kotlin.html)
- [【1.12.2】Cubicodere的模组开发教程](https://cubicoder.github.io/)
- [【1.12.2-1.10.2】shadowfacts的模组开发教程](https://shadowfacts.net/tutorials/)
- [【1.10-1.9】【Youtube】MrCrayFish的模组开发视频教程](https://www.youtube.com/playlist?list=PLy11IosblXIH-OIKa5yYs-KEA2LCohV8g)
- [【1.10-1.9】【Youtube】DisgultGA的模组开发视频教程](https://www.youtube.com/playlist?list=PLkhfw1xGCrIPpgIGXuhFmkjPK5427q4e6)
- [【1.10-1.8】【Youtube】Ash5357的模组开发视频教程](https://www.youtube.com/playlist?list=PLMgygZJ6uqwOSrAaGAOgnUIMAirtPG7w-)
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
- [Forge官方论坛Mod开发讨论版块](http://www.minecraftforge.net/forum/index.php?board=73.0)
- [Forge官方论坛Mod开发教程版块](http://www.minecraftforge.net/forum/index.php?board=120.0)

### 模组开发相关工具

#### Mod Coder Pack
- [查询MCP名与SRG名](https://mcp.thiakil.com/)
- [MCPConfig的发布页](http://files.minecraftforge.net/maven/de/oceanlabs/mcp/mcp_config/)
- [MCPConfig的Github仓库](https://github.com/MinecraftForge/MCPConfig)
- [MCPBot Data Exports](http://export.mcpbot.bspk.rs/)
- [MCPBot使用帮助文档](http://mcpbot.bspk.rs/help)
- [Mod Coder Pack](http://www.modcoderpack.com/)（[旧版本](http://mcp.llbit.se/)）

## Bukkit/Spigot插件开发

### [Rarity的实例型 Bukkit 插件开发教程](https://www.mcbbs.net/thread-1163259-1-1.html)

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
- [信息的处理与呈现相关应用编程](https://www.mcbbs.net/thread-1181150-1-1.html)
- [生物运动&空间坐标的理论探索与应用编程](https://www.mcbbs.net/thread-1177817-1-1.html)
- [玩转ProtocolLib数据包发包](https://www.mcbbs.net/thread-1123486-1-1.html)
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

## Fabric模组开发

### [Fabric开发文档中文翻译](https://www.mcbbs.net/thread-904854-1-1.html)

### [官方网站](https://fabricmc.net/)

### [官方Wiki](https://fabricmc.net/wiki/start)

### 国内相关资料
- [用EventLib简化fabric mod开发](https://www.mcbbs.net/thread-1030076-1-1.html)
- [Leader——中文社区的一份Minecraft Fabric教程](https://www.mcbbs.net/thread-964580-1-1.html)
- [Mixin官方Wiki中文翻译](http://mouse0w0.github.io/categories/Mixin/)

## Sponge插件开发

### [官方网站](https://www.spongepowered.org/)

### [官方论坛](https://forums.spongepowered.org/)

### [官方教程(多国语言，含简体中文)](https://docs.spongepowered.org)

### [官方JavaDoc](https://jd.spongepowered.org/7.2.0/)

### 国内相关资料
- [Minecraft 服务端权限上下文系统及其应用](https://www.mcbbs.net/thread-1007917-1-1.html)

## 数据包开发
### 文档与教程
- [Minecraft 原版模组入门教程](https://zhangshenxing.gitee.io/vanillamodtutorial/)
- [数据包 - Minecraft Wiki](https://minecraft-zh.gamepedia.com/%E6%95%B0%E6%8D%AE%E5%8C%85)

### 工具
- [MCreator](https://mcreator.net/)（[MCBBS](https://www.mcbbs.net/thread-280267-1-1.html)）
- [数据包生成器](https://misode.github.io/)

## Java版启动器开发
### 文档与教程
- [编写启动器 - Minecraft Wiki](https://minecraft-zh.gamepedia.com/%E6%95%99%E7%A8%8B/%E7%BC%96%E5%86%99%E5%90%AF%E5%8A%A8%E5%99%A8)
- [KMCCC使用教程](https://www.mcbbs.net/thread-492606-1-1.html)
- [JMCCC使用教程](https://www.mcbbs.net/thread-573154-1-1.html)

### 类库
- [【C#】KMCCC](https://github.com/MineStudio/KMCCC)
- [【Java】JMCCC](https://github.com/to2mbn/JMCCC)
- [【Java】HMCL](https://github.com/huanghongxun/HMCL)
- [【易语言】Module-Launcher](https://www.mcbbs.net/thread-815868-1-1.html)
- [【C#】Square](https://github.com/baibao132/SquareMinecraftLauncherCore)
- [【Python】minecraft-launcher-lib](https://minecraft-launcher-lib.readthedocs.io/en/latest/index.html)

## 网易基岩版开发
- [我的世界创造者计划官方网站](https://mc.163.com/dev/index.html)
- [技术手册](https://mc.163.com/dev/mcmanual/mc-dev/mcdocs)（[旧版本](https://mc.163.com/mcstudio/mc-dev/)）

## 基岩版Addons开发

### [Minecraft官网附加包（Add-Ons）介绍页面](https://www.minecraft.net/zh-hans/addons)

### [Minecraft中文Wiki“附加包（Add-Ons）”页面](https://minecraft-zh.gamepedia.com/%E9%99%84%E5%8A%A0%E5%8C%85)

### 其他资源
- [下载Minecraft官方资源包](https://aka.ms/resourcepacktemplate)
- [下载Minecraft官方行为包](https://aka.ms/behaviorpacktemplate)
- [基岩版着色器材质文件概述](https://github.com/NovaMods/nova-renderer/wiki/Bedrock-Shaders-Simple-Material-File-Walkthrough)

## 过时开发资源
<details>
<summary>点击展开折叠内容</summary>

## LiteLoader模组开发

### [官方网站](http://www.liteloader.com/)

### [zzzz的LiteMod开发引导(简体中文)](http://www.mcbbs.net/thread-659755-1-1.html)

### [官方源码仓库](http://develop.liteloader.com/public)

## Nukkit插件开发

### [Nukkit插件中文开发教程](http://www.mcbbs.net/thread-552265-1-1.html)

### [Nukkit官方论坛插件开发讨论板块](https://forums.nukkit.io/forums/plugin-development.7/)

## PocketMine插件开发

### [PocketMine插件开发中文教程](http://www.mcbbs.net/thread-410243-1-1.html)

### PocketMine其他插件开发教程
- [新API的部分事物的讲解](http://www.mcbbs.net/thread-288333-1-1.html)

</details>
<!--过时开发资料-->

## 版权声明
本作品作者为我的世界开发者中文指南所有贡献者。

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。

转载请附上本作品链接： https://github.com/Mouse0w0/MinecraftDeveloperGuide
