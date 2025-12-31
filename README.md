# 我的世界开发者中文指南
![](https://img.shields.io/badge/license-CC--BY--SA--4.0-green) ![](https://img.shields.io/github/stars/Mouse0w0/MinecraftDeveloperGuide) [![](https://img.shields.io/badge/%E7%A0%81%E4%BA%91-Gitee-red)](https://gitee.com/mirrors_Mouse0w0/MinecraftDeveloperGuide) 

**MCBBS关站致使大量教程失效，恳请各位读者协助指南联系相关作者及时迁移教程。**

**点击右上方的“Watch”按钮以实时获取中文指南的更新情况，点击右上方“Star”按钮以支持中文指南的编撰。**

**欢迎各位[在此](https://github.com/mouse0w0/MinecraftDeveloperGuide/issues/new?assignees=&labels=&projects=&template=request.yml)提交各类我的世界开发相关教程、资料、文档、类库。**

**欢迎加入[我的世界开发讨论Q群：345538010](https://qm.qq.com/q/Ou895SBQEE)**

发布定制或承接定制请加入[我的世界定制交流Q群：1047988033](https://qm.qq.com/q/Xs4LacqfOU)

## 目录
- [提问的方法](#提问的方法)
- [常用网站与资源](#常用网站与资源)
- [Java基础](#java基础)
- [Forge模组](#forge模组)
- [NeoForge模组](#neoforge模组)
- [Bukkit/Spigot插件](#bukkitspigot插件)
- [Fabric模组](#fabric模组)
- [BungeeCord插件](#bungeecord插件)
- [Sponge插件](#sponge插件)
- [数据包](#数据包)
- [Java版启动器](#java版启动器)
- [基岩版服务端](#基岩版服务端)
- [基岩版Addons](#基岩版addons)
- [基岩版模组](#基岩版模组)
- [网易基岩版](#网易基岩版)
- [着色器包](#着色器包)
- [过时资源](#过时资源)
- [版权声明](#版权声明)

## 提问的方法
当你遇到<b>使用搜索引擎、查阅相关文档、进行Debug（如果没有做过上述操作的话，请立刻去做）</b>也无法解决的问题的时候，你可能会向他人求助。**当你提问时，请确保你准确提供了以下信息：**
- 准确描述你的需求和实际问题情况。
- 准确描述你所在的平台的信息。例如：        
  - Java 版本
  - 所用开发工具及其版本（如IntelliJ IDEA、Eclipse）
  - 所用自动化构建工具及其版本（如Maven、Gradle）
  - Minecraft 版本
  - Bukkit/Spigot/Forge/Sponge/Fabric 任一所在平台及其版本
  - 依赖的类库、模组或插件及其版本
- 提供你的源代码或SSCCE（最小化、完整、可验证的问题示例），将源代码包括项目描述文件完整上传至源码托管平台（如码云、Github）。
- 提供你的完整日志、崩溃报告。
- 提供你的参考资料（如参考某模组的某一功能）。

如果你通过发帖的方式提问，请在你的标题也简略的包含问题描述和平台信息。例如《[Forge][1.7.10]载入Mod时出现NullPointerException》

**请记住，不要认为他人的回答是理所应当的**。如果你想学习更多关于提问的方法、技巧、礼仪，看看[提问的智慧](https://lug.ustc.edu.cn/wiki/doc/smart-questions)会给予你许多帮助。

## 常用网站与资源

### ~~[我的世界中文论坛开发讨论板块](http://www.mcbbs.net/forum.php?mod=forumdisplay&fid=479)~~

### [Github](https://github.com/)
全球最大的社交编程与代码托管网站，可以在这里查看许多模组和插件的源代码。

### [码云](https://gitee.com/)
中文社交编程与代码托管网站。

### [Stack Overflow](http://stackoverflow.com/)
全球最大的编程知识分享与学习社区，你可以在此找到许多编程问题的答案。

### 搜索引擎[百度](https://www.baidu.com)/[必应](https://www.bing.com)/[谷歌](https://www.google.com)
有什么问题为什么不先百度一下呢？

### ~~[wiki.vg](https://wiki.vg/Main_Page)~~
> wiki.vg已关闭，目前Minecraft Wiki正在合并相关内容，[点击此处访问临时页面](https://minecraft.wiki/w/Minecraft_Wiki:Projects/wiki.vg_merge)。

我的世界反向工程与协议参考文档网站，包含各版本网络通信协议、数据格式、Mojang正版验证协议等参考文档。

### [我的世界中文论坛开发教程索引贴](https://archives.mcbbs.co/read.php?tid=54579)

### [TeaCon模组开发茶会 —— 线上Minecraft模组开发大赛](https://www.teacon.cn/)

### [V2我的世界开发者论坛](https://www.v2mcdev.com/)

### 其他资源
- [MCDReforged：基于Python的Minecraft服务端控制工具](https://mcdreforged.com/zh-CN)
- [Cursemaven：一个CurseForge Minecraft模组的Maven公共仓库](https://www.cursemaven.com/)
- [Minecraft实体运动研究与应用](http://lovexyn0827.space/mcdocs/docs/Minecraft%E5%AE%9E%E4%BD%93%E8%BF%90%E5%8A%A8%E7%A0%94%E7%A9%B6%E4%B8%8E%E5%BA%94%E7%94%A8/Minecraft%E5%AE%9E%E4%BD%93%E8%BF%90%E5%8A%A8%E7%9B%B8%E5%85%B3%E7%A0%94%E7%A9%B6%E4%B8%8E%E5%BA%94%E7%94%A8)
- [基于Architectury的跨加载器模组开发指南](https://turou.gitbook.io/arch/)
- [Minecraft服务端开发指北](https://izzel.io/2021/11/13/how-to-minecraft-server/)
- [Adventure中文文档](https://adventure-docs.minecraft.kim/)（[Github](https://github.com/shaokeyibb/adventure-docs-zh_CN)）
- [[协议] 教你如何从外部Ping通服务器](https://juejin.cn/post/7120946847312510984)
- [Java的模式匹配](https://archives.mcbbs.co/read.php?tid=1207118)
- [聊聊区块和Ticket](https://izzel.io/2020/09/09/chunks-and-tickets/)
- [怎么看崩溃报告和Timings？](https://archives.mcbbs.co/read.php?tid=860103)
- [Mixin官方Wiki中文翻译](https://mouse0w0.github.io/categories/Mixin/)
- [Minecraft开发资源Maven仓库国内镜像](https://blog.lss233.com/lss233minecraft-mod/)
- [如何使用持续集成帮助开发](https://archives.mcbbs.co/read.php?tid=716920)
- [[调试辅助]JRebel - 给你+1s\|再也不需要重启客户端加全局变量了](https://archives.mcbbs.co/read.php?tid=694119)

### 国内开发交流社群
- [Teacon模组开发茶会KOOK频道](https://kook.teacon.cn/)
- [Bukkit/Spigot插件开发交流Q群：914085636](https://jq.qq.com/?_wv=1027&k=FeUg8OUQ)
- [Sponge插件开发交流Q群：613604130](https://jq.qq.com/?_wv=1027&k=52OlyJ7)

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

### JDK 下载
- [Oracle JDK](https://www.oracle.com/java/technologies/java-se-glance.html)：Oracle 的 JDK 下载，下载Java 17以下的JDK存档需登录，商业使用受限
- [OpenJDK](https://openjdk.org/)：JDK 的原始开源项目
- [Azul Zulu](https://www.azul.com/downloads/)：Azul 提供的 OpenJDK
- [BellSoft Liberica JDK](https://bell-sw.com/pages/downloads/)：BellSoft 提供的 OpenJDK
- [Eclipse Temurin](https://adoptium.net/)：Eclipse 基金会提供的 OpenJDK
- [Amazon Corretto](https://aws.amazon.com/cn/corretto/)：亚马逊提供的 OpenJDK
- [Microsoft Build of OpenJDK](https://learn.microsoft.com/zh-cn/java/openjdk/download/)：微软提供的 OpenJDK
- [Dragonwell](https://dragonwell-jdk.io/)：阿里云提供的 OpenJDK
 
### 扩展阅读
> 进一步提高Java编程能力。

- [Google Java 编程风格指南](http://hawstein.com/2014/01/20/google-java-style/)
- [设计模式](https://java-design-patterns.com/zh/)
- [编程原则](https://mouse0w0.github.io/2018/10/04/Programming-Principles/)
- 大话设计模式（[豆瓣](https://book.douban.com/subject/2334288/)）
- Effective Java（[豆瓣](https://book.douban.com/subject/30412517/)）
- 代码整洁之道（[豆瓣](https://book.douban.com/subject/4199741/)）
- 架构整洁之道（[豆瓣](https://book.douban.com/subject/30333919/)）

## Forge模组

### [【1.19-1.18】正山小种 - Forge 模组开发指南](https://www.teacon.cn/xiaozhong)

### [【1.16】Boson 1.16 模组开发教程](https://boson.v2mcdev.com/)

### [【1.12.2】Harbinger Forge 模组开发指南](https://harbinger.covertdragon.team/)

### [【1.8.9】zzzz的模组开发教程](https://fmltutor.ustc-zzzz.net/)

### Forge官方文档
介绍了Forge所增加的部分功能。
- [英文文档（最新版）](https://mcforge.readthedocs.io/en/latest/)
- [中文翻译（1.12.2）](https://mcforge-cn.readthedocs.io/zh/latest/)

### MDK（Minecraft开发工具包）
- [Forge官方下载](http://files.minecraftforge.net/)
- [Minecraft Forge 构建开放环境网络代理配置教程](https://zekerzhayard.gitbook.io/minecraft-forge-gou-jian-kai-fa-huan-jing-wang-luo-dai-li-pei-zhi-jiao-cheng/)
- [【1.7.10+】耗子的MDK离线包](https://github.com/mouse0w0/forge-mdk-offline)（[百度云盘 提取码：jmrv](https://pan.baidu.com/s/1dE0EJnz)）
- [【1.7.10】GTNewHorizons的1.7.10开发环境](https://github.com/GTNewHorizons/ExampleMod1.7.10)
- [通过修改Hosts加速模组环境配置](https://archives.mcbbs.co/read.php?tid=1148912)
- [【1.14+】ForgeGradleCN — MDK配置新解决方案](https://archives.mcbbs.co/read.php?tid=1076799)
- ~~[【1.12.2+】FledgeXu的MDK离线包](https://v2mcdev.com/t/topic/249)（[Github](https://github.com/FledgeXu/ForgeGradleOffline/tags)）~~

### 简体中文资源
> 有删除线的条目可能已有更优秀的资源，或已过时，或链接失效，或存在误导、内容欠缺的问题，仅供参考。

- [【1.20】深入浅出高版本渲染系统 —— GuiComponent的消逝与GuiGraphics的新生](https://turou.fun/minecraft/render-tutor/)
- [【1.20】Polonium - 1.20 实体进阶教程](https://lych.top/polonium/)
- [【1.19】【Bilibili】Flandre芙兰的Forge模组开发视频教程](https://www.bilibili.com/video/BV1mV411u73D)
- [【1.18.2】HoloJaneway模组开发教程](https://holojaneway.uss-shenzhou.cn/holojaneway)
- [【1.18】秦千久的模组开发教程](https://tt432.github.io/ModdingTutorial118)
- [【1.18.2】基于Forge的Datagen教程](https://skyinr.github.io/DatagenBook/#/zh-cn/)
- [【1.16.5】【Bilibili】Flandre芙兰的Forge模组开发视频教程](https://www.bilibili.com/video/BV1WM4y1K7D5)
- [【1.16.1】星断肃昭的Forge模组开发视频教程](https://space.bilibili.com/3537121929332753/channel/collectiondetail?sid=3378523&ctype=0)（[抖音](https://www.douyin.com/video/7279377986187431202)/[西瓜视频](https://www.ixigua.com/home/2562275897255528/pseries/?preActiveKey=video&list_entrance=userdetail&wid_try=1)）
- [聊聊 Forge 工具链](https://izzel.io/2022/09/07/forge-toolchain-teardown/)
- [手把手Mixin+Forge开发示例，从开发环境配置到mod发布](https://archives.mcbbs.co/read.php?tid=1386942)
- [Cobalt - 渲染浅析文档](https://zomb-676.github.io/CobaltDocs)
- [由实例上手快速开发多方块结构](https://turou.fun/minecraft/multiblock-tutor/)
- [再析世界生成：生物群系](http://yaossg.com/biome/index.html)
- [聊聊生物和 AI](https://izzel.io/2021/12/19/living-things/)
- [Forge安装到导出详细入门教程\|各种报错解决方法](https://archives.mcbbs.co/read.php?tid=1193768)
- [从实例的角度出发浅谈TileEntitySpecialRenderer](https://turou.fun/legacy-render-tutor/)
- [[举二反三深入模组开发 第二节] 彩虹桥法杖 + 建筑小助手 = ?](https://turou.fun/analogy/rainbow-gadgets/)
- [[举二反三深入模组开发 第一节] 息壤 + 午餐盒 = ?](https://turou.fun/analogy/hexang-bento/)
- [【1.15.2】自定义发光效果——浅谈着色器和帧缓冲的运用](https://blog.teacon.org/shaders-and-framebuffers.html)
- [【1.15】Neutrino 1.15 Mod 开发教程](https://neutrino.v2mcdev.com/)
- [【1.14+】Forge 能量系统简述](https://blog.ustc-zzzz.net/forge-energy-demo-1/)
- [【1.7.10+】Forge / LiteLoader 与 Bukkit / Sponge 之间的通信](https://izzel.io/2017/08/28/minecraft-plugin-message/)
- [【全版本】 原版 / FML CoreMod 开发教程](https://xfl03.gitbook.io/coremodtutor/)（[码云](http://xfl03.gitee.io/coremodtutor/)）
- [【1.13+】浅析1.13世界生成](https://yaossg.com/site/docs/1-13-worldgen)
- [【全版本】雪崩式的灾难：严重滞后的世界生成](https://www.bilibili.com/read/cv545451/)
- [【1.7.10-1.12.2】EnumHelper的前世今生](https://zhuanlan.zhihu.com/p/144893811)
- [【1.7.10-1.12.2】简单网络通信包装类(SimpleNetworkWrapper)](https://github.com/UnknownStudio/ChinaCraft2CodeExplanation/wiki/%E7%AE%80%E5%8D%95%E7%BD%91%E7%BB%9C%E9%80%9A%E4%BF%A1%E5%8C%85%E8%A3%85%E7%B1%BB-SimpleNetworkWrapper)
- [【1.11.2】基于代码的简单方块/物品贴图渲染](https://archives.mcbbs.co/read.php?tid=697765)（[示例代码](https://github.com/rikka0w0/Material_Warehouse)）
- [【1.11.2】ChinaCraft2代码详解——大型模组开发笔记](https://github.com/UnknownStudio/ChinaCraft2CodeExplanation/wiki)
- [【1.10.2+】1.10.2以上的方块与物品渲染](https://archives.mcbbs.co/read.php?tid=733132)
- [Minecraft模组开发知乎专栏](https://zhuanlan.zhihu.com/c_200546589)
- [ustc-zzzz的博客](https://blog.ustc-zzzz.net/)
- [【1.8.9-1.7.2】风之工坊(当风过时的博客)](http://www.windworkshop.cn/?page_id=525)
- [【全版本】Coremod导论—从切比雪夫多项式说起](https://archives.mcbbs.co/read.php?tid=822754)
- [【全版本】俩车的 Coremod 介绍](https://archives.mcbbs.co/read.php?tid=849970)
- ~~[【1.8.9】白玉楼之梦(szszss的博客)](http://blog.hakugyokurou.net/?page_id=126)~~
- ~~[【1.7.10】261Day](https://www.261day.com/minecraft-forge%E6%95%99%E7%A8%8B/)~~

### 其他语言资源
- [【1.16-1.17】【非官方】Forge社区百科](https://forge.gemwire.uk/)
- [【1.16.4-1.12】【Youtube】TurtyWurty的模组开发视频教程](https://www.youtube.com/channel/UCicAXLV4w2X6bn2EuM4To4w)
- [【1.12+】McJty的模组开发教程](https://wiki.mcjty.eu/modding/index.php?title=Main_Page)
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
- [【1.7.10】jabelar的模组开发教程](http://jabelarminecraft.blogspot.com/)
- [【1.7.10】模组开发教程](http://www.minecraftforum.net/forums/mapping-and-modding/mapping-and-modding-tutorials/1571600-1-7-10-minecraft-forge-modding-tutorials-begginer)
- [【1.7.10】EMX的教程](https://emxtutorials.wordpress.com/)
- ~~[附属模组开发工作空间设置](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/modification-development/2358564-how-do-i-use-another-mod-as-a-dependency-for-my)~~

### 模组迁移指南（英语）
- [1.20.5/6 -> 1.21 模组迁移指南](https://gist.github.com/ChampionAsh5357/d895a7b1a34341e19c80870720f9880f)
- [1.20.4 -> 1.20.5 模组迁移指南](https://gist.github.com/ChampionAsh5357/53b04132e292aa12638d339abfabf955)
- [1.19.4 -> 1.20 模组迁移指南](https://gist.github.com/ChampionAsh5357/cf818acc53ffea6f4387fe28c2977d56)
- [1.19.3 -> 1.19.4 模组迁移指南](https://gist.github.com/ChampionAsh5357/163a75e87599d19ee6b4b879821953e8)
- [1.19.2 -> 1.19.3 模组迁移指南](https://gist.github.com/ChampionAsh5357/c21724bafbc630da2ed8899fe0c1d226)
- [1.18.2 -> 1.19.2 模组迁移指南](https://moddingtutorials.org/1.19.2/updating)
- [1.17.1 -> 1.18.2 模组迁移指南](https://moddingtutorials.org/1.18.2/updating)
- [1.16.5 -> 1.17.1 模组迁移指南](https://moddingtutorials.org/1.18.2/updating-to-1.17)
- [1.15 -> 1.16 模组迁移指南](https://moddingtutorials.org/1.16.5/updating)
- [ForgeGradle 5 -> 6 迁移指南](https://gist.github.com/ChampionAsh5357/98b08c117cb2057d8029a8919c378a4c)

### 模组示例代码
- [【1.20.1-1.16.5】Kaupenjoe的模组示例代码](https://github.com/Tutorials-By-Kaupenjoe)
- [【1.19.3-1.18.1】McJty的模组示例代码](https://github.com/McJty/TutorialV3)
- [【1.15.2-1.8.9】McJty的模组示例代码](https://github.com/McJty/ModTutorials)
- [【1.15.2-1.8】TheGreyGhost的模组示例代码](https://github.com/TheGreyGhost/MinecraftByExample)
- [【1.12.2-1.8】Choonster的模组示例代码](https://github.com/Choonster/TestMod3)
- [【1.12.2】Forge Mixin 示例代码](https://github.com/mouse0w0/forge-mixin-example)

### 模组开发讨论
- [Forge官方Discord群组](https://discord.gg/UvedJ9m)
- [Forge官方论坛Mod开发讨论版块](http://www.minecraftforge.net/forum/index.php?board=73.0)
- [Forge官方论坛Mod开发教程版块](http://www.minecraftforge.net/forum/index.php?board=120.0)

### 模组开发相关工具

#### ForgeGradle
- [FancyGradle - 1.12.2 开发环境修复插件](https://gitlab.com/gofancy/fancygradle/-/wikis/home)
- [Gradle 使用教程及谈谈 ForgeGradle](https://archives.mcbbs.co/read.php?tid=1129351)
- [ForgeGradle 开发之「砖」](https://archives.mcbbs.co/read.php?tid=1107776)
- [ForgeGradle 中文文档](https://forgegradle-cn.readthedocs.io/zh/latest/)

#### Mod Coder Pack
- [查询MCP名与SRG名](https://mcp.thiakil.com/)
- [Linkie 映射表查询](https://linkie.shedaniel.dev/mappings)
- [Linkie Discord群组（映射表查询机器人）](https://discord.gg/sCVXYXVcC3)([指令列表](https://github.com/linkie/linkie-discord/wiki/Commands))
- [MCP-Reborn（1.13及以后版本）](https://github.com/Hexeption/MCP-Reborn)
- [MCPConfig的发布页](http://files.minecraftforge.net/maven/de/oceanlabs/mcp/mcp_config/)
- [MCPConfig的Github仓库](https://github.com/MinecraftForge/MCPConfig)
- [Mod Coder Pack（1.7.10-1.12）](http://www.modcoderpack.com/)
- [Mod Coder Pack的Minecraft Wiki历史留档（a0.2.1-1.12）](https://minecraft.wiki/w/Tutorials/Programs_and_editors/Mod_Coder_Pack)
- [RetroMCP（1.5.2及以前版本）](https://github.com/MCPHackers/RetroMCP-Java)
- ~~[MCPBot Data Exports](http://export.mcpbot.bspk.rs/)~~

#### Parchment
> Minecraft 1.16.5+ 第三方反混淆表
- [入门指南](https://parchmentmc.org/docs/getting-started)
- [Github](https://github.com/ParchmentMC/Parchment)

#### Forge Javadoc
> 本JavaDoc由第三方提供，不能保证其时效性及有效性，以实际开发环境为准。
- [【1.12+】ForgeJavaDocs-NG](https://github.com/Nekoyue/ForgeJavaDocs-NG)
- [【1.7.10-1.12.2】ForgeJavaDocs](https://skmedix.github.io/ForgeJavaDocs/)

## NeoForge模组
> 目前本条目仍在建设中，欢迎各位前往相关[Issue](https://github.com/mouse0w0/MinecraftDeveloperGuide/issues/60)提交意见建议。

### [官方网站](https://neoforged.net/)

### [官方文档](https://docs.neoforged.net/)

### [【1.20.4】Flandre芙兰的NeoForge教程](https://fuwari-ald.pages.dev/archive/category/Minecraft1_20_4_NeoForge_Tutorial/)（[Bilibili视频](https://www.bilibili.com/video/BV1hv421y7fe)/[源代码](https://github.com/Flandre923/NeoForgeTutorialmod-Minecraft1.20.4)）

### [【1.20.4】kitUIN的NeoForge教程](https://arkdust-tutorials.kituin.fun/)

### 简体中文资源
- [【1.21.1】NeoForge 1.21.1 官方文档AI翻译](https://www.328377.xyz/)（[备用地址](https://nolebase-template-snowy.vercel.app/)）

## Bukkit/Spigot插件

### [tdiant的Bukkit插件开发教程](https://bdn.tdiant.net/)（[Github](https://github.com/tdiant/BukkitDevelopmentNote)）

### [Rarity的Bukkit插件开发教程](https://moran0710.github.io/PluginDiary/)（[Github](https://github.com/Andy-K-Sparklight/PluginDiary)）

### [【Kotlin】插件设计与编程](https://bpd.skjsjhb.moe/)

### 官方教程
- [新版本（现Spigot）](https://www.spigotmc.org/wiki/spigot/)
- [旧版本（原Bukkit）](http://wiki.bukkit.org/Plugin_Tutorial)

### Bukkit API开发者文档
- [中文文档](https://bukkit.windit.net/javadoc/)
- [英文文档](https://hub.spigotmc.org/javadocs/spigot/)

### [Spigot官方论坛插件开发讨论版块](https://www.spigotmc.org/forums/spigot-plugin-development.52/)
很多问题都能在这里解决。

### 简体中文资源
> 有删除线的条目可能已有更优秀的资源，或已过时，或链接失效，或存在误导、内容欠缺的问题，仅供参考。
- [正确使用PluginManager#registerEvent的方式](https://archives.mcbbs.co/read.php?tid=1472122)
- [监听“玩家放置末影水晶”的方式](https://archives.mcbbs.co/read.php?tid=1471726)
- [监听“玩家使用盾牌成功格挡伤害”的方式](https://archives.mcbbs.co/read.php?tid=1471663)
- [NBT库获取ItemStack的NBT副本的意义](https://archives.mcbbs.co/read.php?tid=1471572)
- [调试小技巧——Bukkit中构建后自动打开服务端](https://archives.mcbbs.co/read.php?tid=1456687)
- [通过NMS序列化ItemStack 浅谈序列化复杂实体类](https://archives.mcbbs.co/read.php?tid=1456449)
- [事件监听大典 : Bukkit API 文档中文翻译](https://william-shi233.gitbook.io/event-listeners/)
- [图形学基础与MC插件开发 ~ 几乎完美的范围挖掘算法](https://www.iseason.top/mc-scope-mining/)
- [使用 PersistentDataContainer 快速添加自定义数据](https://archives.mcbbs.co/read.php?tid=1248632)
- [聊聊 PaperAPI 提供的自定义生物 AI 系统](https://my.minecraft.kim/tech/393/%E8%81%8A%E8%81%8A-paperapi-%E6%8F%90%E4%BE%9B%E7%9A%84%E8%87%AA%E5%AE%9A%E4%B9%89%E7%94%9F%E7%89%A9-ai-%E7%B3%BB%E7%BB%9F/)
- [关于 ProtocolLib 监听系统的使用与研究](https://archives.mcbbs.co/read.php?tid=1248152)
- [Bukkit NMS 开发实践 —— 创建你自己的自定义实体](https://my.minecraft.kim/tech/260/bukkit-nms-%E5%BC%80%E5%8F%91%E5%AE%9E%E8%B7%B5-%E5%88%9B%E5%BB%BA%E4%BD%A0%E8%87%AA%E5%B7%B1%E7%9A%84%E8%87%AA%E5%AE%9A%E4%B9%89%E5%AE%9E%E4%BD%93%EF%BC%88%E9%80%82%E7%94%A8/)
- [Bukkit编程杂谈：雷点\|模板\|思路\|设计](https://icebear003.github.io/noticements-in-bukkit/)
- [信息的处理与呈现相关应用编程](https://hamsteryds.gitee.io/info-processing-in-bukkit/)
- [生物运动&空间坐标的理论探索与应用编程](https://hamsteryds.gitee.io/kinematics-of-minecraft/)
- [玩转ProtocolLib数据包发包](https://archives.mcbbs.co/read.php?tid=1123486)
- [优雅地让命令完整支持TAB补全](https://archives.mcbbs.co/read.php?tid=1075004)
- [怎样写出一个1.12.2-1.15.2通用支持的插件](https://archives.mcbbs.co/read.php?tid=1023107)
- [如何编写一个可以保留注释的配置类](https://zhuanlan.zhihu.com/p/146322254)
- [使用IDEA快速调试插件](https://archives.mcbbs.co/read.php?tid=1004767)
- [创建高版本自定义实体，自定义方块原理与应用](https://archives.mcbbs.co/read.php?tid=966358)
- [如何问玩家“吾与徐公孰美？”](https://izzel.io/2020/02/12/chat-with-future/)
- [Scoreboard教程](https://www.jianshu.com/p/911edcaf5e79)
- [1.13+ 中 Forge 与 Bukkit 的通信](https://archives.mcbbs.co/read.php?tid=873219)
- [插件粒子特效教程](https://www.jianshu.com/p/cf267acfe719)
- [聊天组件API——自定义你的聊天消息](https://archives.mcbbs.co/read.php?tid=812136)
- [如何让插件命令支持Tab自动补全](https://archives.mcbbs.co/read.php?tid=818199)
- [自定义实体](https://archives.mcbbs.co/read.php?tid=811096)
- [插件使用MySQL数据库](https://archives.mcbbs.co/read.php?tid=783267)
- [ItemMeta 使用教程](https://archives.mcbbs.co/read.php?tid=782974)
- [Pathfinder 实体AI教程](https://archives.mcbbs.co/read.php?tid=775757)
- [如何给插件加上更新检查](https://archives.mcbbs.co/read.php?tid=726821)
- [Forge/LiteLoader与Bukkit/Sponge之间的通信](https://izzel.io/2017/08/28/minecraft-plugin-message/)
- [HolographicDisplays API 汉化](https://archives.mcbbs.co/read.php?tid=721009)
- [如何利用Maven来管理你的插件](https://archives.mcbbs.co/read.php?tid=711754)
- [在插件通过发包(ProtocolLib)打开牌子界面(Sign GUI)](https://archives.mcbbs.co/read.php?tid=706491)
- [自定义交互式书本](https://archives.mcbbs.co/read.php?tid=697788)
- [如何给物品增加NBT数据](https://archives.mcbbs.co/read.php?tid=697478)
- [自定义物品模型[1.9+]](https://archives.mcbbs.co/read.php?tid=694674)
 - [在使用NMS的同时支持多个版本](https://archives.mcbbs.co/read.php?tid=694224)
 - [BukkitAPI 1.10->1.11改动介绍](https://archives.mcbbs.co/read.php?tid=648659)
 - [如何在JavaIDE上调试你的插件](https://archives.mcbbs.co/read.php?tid=627399)
 - [Bukkit Conversation API](https://archives.mcbbs.co/read.php?tid=619632)
 - [Vault API 翻译](https://archives.mcbbs.co/read.php?tid=615396)
 - [Placeholder 教程](https://archives.mcbbs.co/read.php?tid=570703)
 - [ProtocolLib 教程](https://archives.mcbbs.co/read.php?tid=568714)
 - [使用Metrics统计信息](https://archives.mcbbs.co/read.php?tid=295815)
 - [Enchantment API 教程](https://archives.mcbbs.co/read.php?tid=782859)
 - [编辑，获取并使用木牌](https://archives.mcbbs.co/read.php?tid=697373)
 - (已于1.12弃用)Ebean数据库[(上)](https://archives.mcbbs.co/read.php?tid=628118)[(下)](https://archives.mcbbs.co/read.php?tid=636860)
 - [wyt的Bukkit插件开发教程](https://archives.mcbbs.co/read.php?tid=614388)
 - [Day's Bukkit插件开发教程](https://archives.mcbbs.co/read.php?tid=439856)
 - [810587921的插件开发教程](https://archives.mcbbs.co/read.php?tid=283190)

## Fabric模组

### [官方网站](https://fabricmc.net/)

### 官方Wiki（[英文](https://fabricmc.net/wiki/start)/[中文](https://fabricmc.net/wiki/zh_cn:start)）

### [官方模板模组生成器](https://fabricmc.net/develop/template/)

### [官方示例模组仓库](https://github.com/FabricMC/fabric-example-mod)

### 简体中文资源
> 有删除线的条目可能已有更优秀的资源，或已过时，或链接失效，或存在误导、内容欠缺的问题，仅供参考。
- [【1.20.1】【Bilibili】Flandre芙兰的Fabric模组开发视频教程](https://www.bilibili.com/video/BV1Kj411f7Zt)
- [Linkie 映射表查询](https://linkie.shedaniel.me/mappings)
 - [在自己的Mod里添加线缆网络！](https://archives.mcbbs.co/read.php?tid=1385476)
 - [FabricLoomCN-加速你的 fabric 模组依赖拉取以及环境搭建](https://archives.mcbbs.co/read.php?tid=1239261)
- [由现象到本质的Minecraft源码注入艺术](https://turou.fun/minecraft/mixin-tutor/)
 - [用EventLib简化fabric mod开发](https://archives.mcbbs.co/read.php?tid=1030076)
 - [Leader——中文社区的一份Minecraft Fabric教程](https://archives.mcbbs.co/read.php?tid=964580)
 - [Fabric开发文档中文翻译](https://archives.mcbbs.co/read.php?tid=904854)

## BungeeCord插件

### [《BungeeCord插件开发》中文翻译](https://mouse0w0.github.io/BungeeCord-CN-Translation/)

### [官方Wiki](https://www.spigotmc.org/wiki/bungeecord/)

### [BungeeCord插件开发教程](https://www.spigotmc.org/wiki/bungeecord-plugin-development/)

### [BungeeCord官方论坛插件开发讨论板块](https://www.spigotmc.org/forums/bungeecord-plugin-development.23/)

## Sponge插件

### [官方网站](https://www.spongepowered.org/)

### [官方论坛](https://forums.spongepowered.org/)

### [官方教程(多国语言，含简体中文)](https://docs.spongepowered.org)

### [官方JavaDoc](https://jd.spongepowered.org/7.2.0/)

### 简体中文资源
- [Minecraft 服务端权限上下文系统及其应用](https://blog.ustc-zzzz.net/minecraft-server-permission-context/)

## 数据包
### 文档与教程
- [Minecraft 原版模组入门教程](https://zhangshenxing.github.io/VanillaModTutorial/)
- [数据包 - Minecraft Wiki](https://zh.minecraft.wiki/w/%E6%95%B0%E6%8D%AE%E5%8C%85)

### 工具
- [数据包生成器](https://misode.github.io/)
- [大憨批 —— VSCode 数据包函数编辑插件](https://marketplace.visualstudio.com/items?itemName=SPGoding.datapack-language-server)
- [MCreator](https://mcreator.net/)

## Java版启动器
### 文档与教程
- [编写启动器 - Minecraft Wiki](https://zh.minecraft.wiki/w/%E6%95%99%E7%A8%8B/%E7%BC%96%E5%86%99%E5%90%AF%E5%8A%A8%E5%99%A8)
- [xphost008的启动器开发教程](https://xphost008.github.io/lmaml)
- [JMCCC使用教程](https://github.com/yushijinhun/jmccc.tutorial/blob/master/tutorial-2.4.md)
 - [KMCCC使用教程](https://archives.mcbbs.co/read.php?tid=492606)

### 类库
- [【C#】KMCCC](https://github.com/MineStudio/KMCCC)
- [【Java】JMCCC](https://github.com/to2mbn/JMCCC)
- [【Java】HMCL](https://github.com/huanghongxun/HMCL)
- [【易语言】Module-Launcher](https://github.com/Hill23333/modulelauncher-archive)
- [【C#】Square](https://github.com/baibao132/SquareMinecraftLauncherCore)
- [【Python】minecraft-launcher-lib](https://minecraft-launcher-lib.readthedocs.io/en/latest/index.html)

## 基岩版服务端

### [官方服务端](https://www.minecraft.net/en-us/download/server/bedrock)

### LeviLamina (原LiteLoaderBDS)
- [官方主页](https://lamina.levimc.org/zh/)
- [官方仓库](https://github.com/LiteLDev/LeviLamina)
- [LegacyScriptEngine - 在LeviLamina上运行LLSE插件](https://lse.levimc.org/)
- [旧版官方仓库](https://github.com/LiteLDev/LiteLoaderBDSv2)

### Endstone
- [官方文档](https://endstone.dev/latest/)
- [官方仓库](https://github.com/EndstoneMC/endstone)

### PowerNukkitX
- [官方主页](http://www.powernukkitx.cn/)
- [官方文档](https://www.powernukkitx.com/doc/index.html)
- [官方仓库](https://github.com/PowerNukkitX/PowerNukkitX)
- [wulia697的PowerNukkitX快速入门](https://github.com/wuliao697/PowerNukkitXTutorial)

### Cloudburst Nukkit
- [官方文档](https://cloudburstmc.org/wiki/nukkit)
- [官方仓库](https://github.com/CloudburstMC/Nukkit)

### Dragonfly
- [官方文档](https://github.com/df-mc/dragonfly/wiki)
- [官方仓库](https://github.com/df-mc/dragonfly)

### 其他资源
- [基岩版服务端软件 - Minecraft Servers Wiki](https://minecraftservers.fandom.com/wiki/Bedrock_Edition_server_software)
- [基岩版服务端软件 - Bedrock Wiki](https://wiki.bedrock.dev/servers/server-software.html)

## 基岩版Addons

### [我的世界基岩版创作者文档](https://docs.microsoft.com/en-us/minecraft/creator/)

### [我的世界基岩版脚本API参考文档](https://docs.microsoft.com/en-us/minecraft/creator/scriptapi/)

### [我的世界中文Wiki“附加包（Add-Ons）”页面](https://zh.minecraft.wiki/w/%E9%99%84%E5%8A%A0%E5%8C%85)

### [边做边学：从零开始制作一个矿石作物 Addon](https://fang.blog.miri.site/archives/980/)

### [【VSCode扩展】我的世界基岩版调试器（Minecraft Bedrock Debugger）](https://marketplace.visualstudio.com/items?itemName=mojang-studios.minecraft-debugger)

### [【非官方】我的世界基岩版开发百科](https://wiki.mcbe-dev.net/)

### [【非官方】Bedrock Wiki](https://wiki.bedrock.dev/)

### 其他资源
- [下载Minecraft官方资源包/行为包](https://aka.ms/resourcepacktemplate)
- [Minecraft官方网络协议文档](https://github.com/Mojang/bedrock-protocol-docs)
- [基岩版着色器材质文件概述](https://github.com/NovaMods/nova-renderer/wiki/Bedrock-Shaders-Simple-Material-File-Walkthrough)
- [【非官方】我的世界基岩版文档](https://bedrock.dev/zh)
- [【非官方】Minecraft基岩版开发文档](https://mcbe-dev.net/)
- [【非官方】下载全版本Minecraft官方资源包/行为包](https://bedrock.dev/packs)
- [【非官方】MCBEID表](https://ca.projectxero.top/idlist/)

## 基岩版模组

### Horizon
- [官方主页](https://icmods.mineprogramming.org/)
- [官方文档](https://wiki.mineprogramming.org/)

### Amethyst
- [官方文档](https://amethystapi.github.io/Amethyst-Docs/)
- [官方仓库](https://github.com/FrederoxDev/Amethyst/)

## 网易基岩版
- [网易我的世界开发者官网](https://mc.163.com/dev/index.html)
- [网易我的世界开发指南](https://mc.163.com/dev/guide.html)（[旧版本](https://mc.163.com/mcstudio/mc-dev/)）

## 着色器包

### [我的世界图形学社区文档](https://docs.minegraph.cn/home)

### 简体中文资源
- [高清修复OptiFine \| 官方帮助文档翻译](http://sqwatermark.com/resguide/optifinedoc/)
- [《学习OpenGL》中文翻译](https://learnopengl-cn.github.io/)
- [GAMES101-现代计算机图形学入门-闫令琪](https://www.bilibili.com/video/BV1X7411F744)

### 其他语言资源
- [saada2006的我的世界着色器教程](https://saada2006.github.io/minecraft-shader-tutorials/)（[源代码](https://github.com/saada2006/MinecraftShaderProgramming)）
- [OpenGL官方规范文档和参考文档](https://registry.khronos.org/OpenGL/index_gl.php)
- [shaderLABS着色器包交流Discord社区](https://discordapp.com/invite/F4BtNAc)

## 过时资源
<details>
<summary>点击展开折叠内容</summary>

## LiteLoader模组

### [官方网站](http://www.liteloader.com/)

### [zzzz的LiteMod开发引导(简体中文)](https://archives.mcbbs.co/read.php?tid=659755)

### [官方源码仓库](http://develop.liteloader.com/public)

## Nukkit插件
Java开发的Minecraft基岩版服务端。
### [Nukkit插件中文开发教程](https://archives.mcbbs.co/read.php?tid=552265)

### [Nukkit官方论坛插件开发讨论板块](https://forums.nukkit.io/forums/plugin-development.7/)

## PocketMine插件

### [PocketMine插件开发中文教程](https://archives.mcbbs.co/read.php?tid=410243)

### 简体中文资源
- [新API的部分事物的讲解](https://archives.mcbbs.co/read.php?tid=288333)

## 基岩版服务端

### bdsx
- [官方文档](https://github.com/bdsx/bdsx/wiki)
- [官方仓库](https://github.com/bdsx/bdsx)

</details>
<!--过时开发资料-->

## 版权声明
本作品作者为我的世界开发者中文指南所有贡献者。

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。

转载请附上本作品链接： https://github.com/Mouse0w0/MinecraftDeveloperGuide

## 统计信息

### Stargazers over time
[![Stargazers over time](https://starchart.cc/mouse0w0/MinecraftDeveloperGuide.svg)](https://starchart.cc/mouse0w0/MinecraftDeveloperGuide)

