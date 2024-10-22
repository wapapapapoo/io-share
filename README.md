# IOCLUB 茶话会归档

用来归档茶话会下资料，最好使用 md 编写，放在对应时间如 241013 文件夹下。

> 中文文档编写推荐使用 [Auto Correct](https://github.com/huacnlee/autocorrect) 插件

## PPT 编写建议

下列文章列举了一些 PPT 演讲/写作技巧

### 从第二张幻灯片上开始演示

原文链接：<https://tidyfirst.substack.com/p/start-presentations-on-the-second>

> 首次发布于 2013 年 3 月。这是我所知道的最有效的吸引观众注意力的技巧。同时，它也很容易执行——写下你想写的内容，然后交换前两张幻灯片/段落/章节。

技术演示需要背景，但背景并不吸引人。那一个极客演讲者应该怎么办？

我最近一直在指导技术演讲者，几乎所有人都会提到几个概念。我想把它们写下来，这样我就不必一直解释。一个是使用具体的细节和数据。我稍后会写这个。这篇文章解释了为什么要在第二张幻灯片上开始你的演示。

我从劳伦斯·布洛克的杰作《为了乐趣和利润而讲谎言》中“偷”来了这个技巧，那本书是关于写作小说的。
他建议以“自然”的方式撰写故事，第一章介绍英雄，第二章开始行动，然后交换这两章。现在第一章以一把枪指着英雄的头部开始，到最后，他正站在悬崖边缘，准备跳入满是鳄鱼的河流。就在紧张气氛达到顶点时，我们被介绍了这个角色，但现在我们有理由想要了解他。

技术演示需要设定一些背景，然后提出要解决的问题。
当演讲者按照这个顺序进行时，结果演示开始时包含一些听众已经知道的信息，而其他听众则没有任何动机去尝试理解。
这就像我们的冒险故事，我们对英雄的头发颜色不感兴趣，至少在他快要变成鳄鱼小吃之前不感兴趣。

例如，现在请你考虑一个关于 JIT (即时编译优化虚拟机) 的演示。背景信息介绍了 JIT 编译、性能调优的基础知识，以及当前机器的架构。
但令人震惊的是，按照通常的方式应用这些信息，比如通过优化热点，往往会导致整体性能下降，而看似无害的变化却能带来显著的效果改善。

通过对章节进行交换，现在幻灯片 1 将展示

- 热点代码的性能概况
- 一个看似提供改进的代码更改
- 以及一段数据表明优化不仅没有效果，反而使系统变慢

现在我们可以进行关于 JIT、优化和架构方面的幻灯片展示。已经了解背景的听众愿意耐心听完，以找到谜题的解决方案。尚未了解背景的听众则对内容产生了足够的兴趣，能够集中注意力。

程序员有一种巴甫洛夫式的工程反应。给他们一个问题，他们就会开始尝试解决它。通过确保第一口能让他们的唾液分泌，给他们一个与您的演示共同工程的机会。
然后你可以解释问题的其余部分和你出色的解决方案，知道他们和你在一起。

### PowerPoint 的 10/20/30 规则

原文链接：<https://guykawasaki.com/the_102030_rule/>

我患有一种叫做美尼尔病 (Ménière’s disease) 的疾病——别担心，你不会因为阅读我的博客而感染它。美尼尔病的症状包括听力丧失、耳鸣（持续的铃声）和眩晕。关于其原因有许多医学理论：饮食中的盐、咖啡因或酒精过多，压力过大，以及过敏。因此，我努力控制所有这些因素。

然而，我有另一个理论。作为一名风险投资家，我必须听数百位企业家推销他们的公司。这些提案大多数都是废话比如：六十张关于“专利申请中”、“先发优势”、“我们只需要让中国 1% 的人购买我们的产品”的创业公司幻灯片。这些推销糟糕透了，我的听力都在下降，耳边不断响起嗡嗡声，时不时地世界开始旋转。

为了防止风险投资界也开始流行美尼尔病，我正在推广 **PowerPoint 的 10/20/30 规则**。它非常简单：一个 PowerPoint 演示文稿应该有**十张幻灯片**，**持续时间不超过二十分钟**，且**字体不小于三十磅**。虽然我在风险投资行业，但这个规则适用于任何达成共识的演示：例如，筹集资金、达成销售、建立合作伙伴关系等。

- 10 张幻灯片。10 是 PowerPoint 演示文稿中最佳的幻灯片数量，因为一个正常人无法在会议中理解超过十个概念——而风险投资家非常正常。

  > （你和风险投资家的唯一区别是他在用别人的钱赌博并获得报酬）。如果你必须使用超过十张幻灯片来解释你的业务，那么你可能根本没有业务。风险投资家关心的十个主题是：

  - 问题
  - 你的解决方案
  - 商业模式
  - 底层魔法/技术
  - 市场营销与销售
  - 竞争
  - 团队
  - 预测和里程碑
  - 状态和时间线
  - 总结与行动呼吁

- 20 分钟。你应该在二十分钟内展示你的十张幻灯片。

  没错，你有一个小时的时间段，但你使用的是一台 Windows 笔记本电脑，所以连接投影仪将花费四十分钟。即使设置过程完全顺利，人们也会迟到，并且因为某些原因不得不提前离开。

  在一个完美的世界里，你会用二十分钟进行陈述，剩下四十分钟用于讨论。

- 30 号字体。我看到的大多数演示文稿中的文本都是 10 号字体。尽可能多的文本被挤进幻灯片中，然后演讲者逐字朗读。

  然而，一旦观众发现你在读文本，他们会比你说得更快地提前阅读。结果是你和观众不同步。

  人们使用小字体的原因有两个：首先，他们对自己的材料了解不够；其次，他们认为更多的文字更具说服力。完全是胡说八道。请强迫自己使用不小于三十磅的字体。

  我保证这会让你的演示更好，因为它要求你找到最重要的要点，并知道如何很好地解释它们。

  如果“30 号”太过教条，我给你提供一个算法：找出你听众中年龄最大的人的年龄，然后除以二。这就是你的最佳字体大小。

请遵循 PowerPoint 的 10/20/30 法则。如果没有其他原因，下次当你听众中有人抱怨听力下降、耳鸣或眩晕时，你就会知道是什么导致了这个问题。

> 最后一件事：要了解更多关于精彩演示的理念，请查看我朋友 Garr Reynolds 创建的网站 Presentation Zen。