[#]: collector: (bestony)
[#]: translator: (JonnieWayy)
[#]: reviewer: ( )
[#]: publisher: ( )
[#]: url: ( )
[#]: subject: (Command Line Heroes: Season 2: Ready to Commit)
[#]: via: (https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit)
[#]: author: (RedHat https://www.redhat.com/en/command-line-heroes)

代码英雄：第2季：准备提交
======
**00:03** - _Nolan Lawson_

在我刚开始做软件开发的时候，我基本上只做些让自己开心的小项目，像小应用程序、命令行小工具之类的。  

**00:12** - _Lindsey Tulloch_

我只是真不知道作出贡献那么容易。而且你不需要解决P=MP问题，你的投入依然很有价值。  

**00:21** - _Kanika Muraka_

当地社区使我有了足够的信心去做出贡献。  

**00:28** - _Saron Yitbarek_

当我还完全是个编程新手的时候，我和我的朋友Dan一起发起了我的第一次开源 pull request (PR)，这也是我的第一次开源贡献。  

**00:42** - _Saron Yitbarek_

我听过很多有关为开源做贡献的故事，关于它有多么神奇，但又多么可怕。我很清楚，并非所有社区都和善，也不是所有维护者都很友好。  

**00:57** - _Saron Yitbarek_

这个项目本身对新手来说相当不错。我们只是添加了一个 JavaScript 库，让人们可以在线浏览网站。这只是一个很好的范围很广、自成体系的项目。幸运的是，如果这玩意儿不起作用，我基本上确信它不会烧毁整个网站。  

**01:18** - _Saron Yitbarek_

然而，我对这个 PR 非常紧张。我和 Dan 阅读了这个库的文档，埋头于写我们的代码。我仍记得当我们最终完成的时候，只是互相看着彼此，好像在说：“就这样吗？”我们发起了 PR。 PR 被审查并合并，我想我至今还是对这一切的机制感到惊讶，我也不知道。  

**01:43** - _Saron Yitbarek_

这并不是什么只有他们能做到的某些神秘或神奇的大事。我意识到我确实也可以作出贡献。这是我们在这一集中想要传递的一点知识——为开源做出贡献并不是魔术。它并不可怕。我们将一起解决这个问题。  

**02:05** - _Lindsey Tulloch_

我突破性地意识到这实际上是完全开放的，我也可以做。  

**02:15** - _Saron Yitbarek_

在这一场的开始中，你听到了像你一样的代码英雄（ Command Line Heroes ）。这些人经历着同样的恐惧，加入了开源行列。他们分别是 Nolan Lawson、 Lindsey Tulloch、 Kanika Muraka，他们都是英雄。  

**02:34** - _Saron Yitbarek_

您正在收听的是Red Hat的原创播客节目代码英雄（ Command Line Heroes ）。我是你们的主持人 Saron Yitbarek。  

**02:47** - _Saron Yitbarek_

这是一个关于两个想在广阔的开源世界中做得更好的代码英雄（ Command Line Heroes ）的故事。他们其中一个是贡献者，另一个是维护者。他们都不是真实存在的人物，而是两个用来代表所有与我们分享过故事的贡献者和维护者的虚构人物。希望您也可以在他们的旅途中看到你自己。  

**03:16** - _Saron Yitbarek_

首先来见一见我们的朋友——贡献者。她是个新手，就像我们曾经那样。她不确定基本的工作流是什么，但是她看到了需求，并且认为她可以添加能够提供帮助的功能。我们虚构的贡献者热衷于解决这个问题，但是该怎么做呢？  

**03:44** - _Corinne Warnshuis_

你一直在培养新技能，而且你不必在孩提时代拆开电脑才能知道成年后如何写代码。  

**03:52** - _Saron Yitbarek_

那是 Corinne Warnshuis，一个名叫 Girl Develop It 的了不起组织的执行董事。它的目的是帮助那些可能在提问时觉得不是很舒适或在聚会上不完全受欢迎的女性。  

**04:07** - _Saron Yitbarek_

Girl Develop It 意识到做出贡献并不是对所有人而言都一样的——文化也很关键。作为社区，我们的一部分职责就是要在过程中建立一点同情心以及健康的多样性。  

**04:22** - _Corinne Warnshuis_

我们看到存在有许多加入开源的壁垒，但我们喜欢称它们为“没有充分理由（ no good reasons ）”。有三个“没有充分理由”将女性专门排斥在技术之外。它们是：刻板印象（ stereotypes ）、可访问性（ accessibility ） 和环境（ environment ）。  

**04:40** - _Saron Yitbarek_

这里值得记住的是，促进多元化不仅具有良好的道德意义，同时也具有很好的商业意义。  

**04:48** - _Corinne Warnshuis_

作为一个行业，技术可能拥有着改变当今世界的最大潜力。你确确实实希望来自各行各业的人们为将要重塑世界的工具、服务和其他事物做出贡献。我认为各种背景的人们一起开发软件并为开源项目做出贡献真的非常重要。  

**05:13** - _Saron Yitbarek_

事实是，我们起初并非拥有同样的优势和经验。下一代伟大的码农可能看上去并不会像硅谷的平庸之辈（ Silicon Valley cliché ）一样。  

**05:23** - _Corinne Warnshuis_

面对面指导对人们而言历来是非常昂贵而又难以获取到的。再者，我认为从 2014 年至今，情况有所改善。我认为除了 Girl Develop It 之外的组织（比如 Outreachy 和 CodeNewbie ），正通过提供安全网，或是提供一个供人提问并让人感到更舒适的空间来做到这一点。  

**05:49** - _Corinne Warnshuis_

为其中一些点子和问题提供一个安全而友好的测试平台是一个不错的起点。  

**06:02** - _Saron Yitbarek_

说到新手，回到我们正在追踪的那个贡献者。倘若你不是来自于主流背景，那么第一次提交可能会极具份量。感觉就好像你得证明你自己。一旦我们将加入的壁垒降得足够低，我们在准备做出贡献时实际需要考虑的是什么呢？  

**06:23** - _Vincent Batts_

对某些项目感到兴奋很酷，但你想要解决的用例是什么呢？  

**06:31** - _Saron Yitbarek_

Vincent Batts在Red Hat工作，主要从事容器架构方面的工作。他鼓励新的贡献者们尝试并特意从事这项工作。找到你与项目合而为一有意义的利基。  

**06:45** - _Vincent Batts_

我认为一个可贡献的项目通常来自于互惠关系。它满足了你的需要，而且过程中你发现了满足它需求的方式。即使它是一个由人构成的社区，它也已进而成了一种关系。  

**07:01** - _Saron Yitbarek_

比方说：  

**07:02** - _Vincent Batts_

由于朋友的推荐，我最终致力于开发一个 Slackware Linux 盒子。这足以让我去做我一直想做的事情。我帮着将其打包到了主流 Slackware Linux 社区，并最终成为了这个项目的贡献者和维护者。这并不是因为我寻求成为 Slackware Linux 社区的贡献者，而是因为我实际上试图解决的用例正好最适合另一个项目。  

**07:33** - _Vincent Batts_

我认为很多人都会遇到这种情况。他们为量身定制的用例编写数据库，并且发现这个数据库在 Golang 下运行良好。他们写了这样一个高性能的数据库，使得他们能够对 Golang 做出后修复或优化方面的贡献，来帮助他们的数据库运行得更快。  

**07:54** - _Saron Yitbarek_

你可以找到你自己的小众市场，并实现一定程度的有机增长。关键在于，从某处开始。你不必等待学位或绝对的自信心。  

**08:08** - _Vincent Batts_

如果你需要直接编写代码或文档，或是成为一个后端数据库 Web 服务器的系统管理员，这些社区中的大多数都是基于志愿者构成的。你参与了诸如 Debian、 Fedora 或其他一些类似的项目，这些社区都建立起了文档页面。那些项目必须在某处的 Web 服务器上运行，一些人，甚至是一个没有薪酬的正在积累经验的社区成员负责去检查 Web 服务器是否停机或出了什么问题。  

**08:43** - _Saron Yitbarek_

Vincent 强调了开源的平等主义本质。无论你来自哪里，只要你愿意，都可以真正开始做出贡献。如果你想的话，可以给自己起个名字。  

**08:57** - _Vincent Batts_

一旦被合并，你的名字就会附在某个项目上。你可以公开发布在某处作出的改进，这是相当有意义的事情。  

**09:11** - _Vincent Batts_

我曾与电视修理工和教师的出色代表共事过，并不是从事日常的技术工作。他们在社区中做出了很多贡献。另一方面，我也曾和一些有时能有30年开发经验的开发者合作过，但他们从来没有像那样公开贡献过代码。  

**09:40** - _Saron Yitbarek_

我们的贡献者最近怎么样？嗯，她找到了她的利基。她克服了她的恐惧，并最终发起了她的第一个 PR。现在她可以休息一下，并战战兢兢地等待维护者作出回复。  

**09:56** - _Vincent Batts_

向上游做贡献有点像第一次上台做才艺表演。你会感到紧张，走上舞台后手心冒汗。你做了一件事，然后它好像就变成了你的成就。你将彻底改变，不再一样。  

**10:17** - _Saron Yitbarek_

彻底改变？或许吧。事实上，维护者有四种可能的回应：沉默，这很有趣，也可能是完全拒绝，或是完全接受，或是湿软的中间立场——要求修改。  

**10:37** - _Saron Yitbarek_

提交 PR 的几天后，我们虚构的贡献者终于收到了来自维护者的回复。瞧，是要求修改。作为一个新手，她将这视为一场小型灾难。她还不知道要求修改是个实际上怎样的成就。她甚至还对维护者的简略语气感到气愤，听上去就像维护者没空搭理她一样。  

**11:03** - _Saron Yitbarek_

这里存在着一堵墙，新的贡献者不知道墙的另一边正在发生什么。  

**11:12** - _Saron Yitbarek_

我们来认识一位维护者。他正在维护的项目并不是他的全职工作。这是一个周末项目，他时常熬夜到凌晨，给工单排优先级，并且提醒人们发起 PR 时更新文档，然后你就明白了。他相当忙碌，有时甚至出现了一些维护倦怠。  

**11:38** - _Saron Yitbarek_

现实生活中的维护者 Nolan Lawson 写了一篇很棒的有关倦怠的文章，最近引起了很多关注。  

**11:51** - _Nolan Lawson_

老实说，我认为那篇博文有一部分实在寻求帮助。这是我表示自己偶然发现了这个开源的东西。起初确实很有趣，但现在却没那么有趣了。我不确定该如何恢复兴致。  

**12:05** - _Saron Yitbarek_

Nolan 有一份日常工作，但和大多数维护者一样，他在开源项目中投入了大量的下班时间，因为这家伙真的很在意这个。讽刺的是，他的部分痛苦来自于他清楚贡献者也很在意这个事实。  

**12:23** - _Nolan Lawson_

真正使我精疲力竭的实际上只是如潮水般涌来的好心人。你真的想帮他们，真的真的很想。他们所做的只是问一个问题，他们所做的就是——他们在你项目中发现了阻碍他们的合法 bug，或者他们实际上不愿意下载代码然后弄清其构建方式并提供 bug 修复。他们只是希望你审查他们贡献的代码。  

**12:43** - _Saron Yitbarek_

像 Nolan 这样的维护者正不断地审查 PR 库，弄清每个提交将如何发挥作用。他们促使贡献者尽可能做到最好，遵守限制，以对更大的项目目标最有意义的方式做出贡献。  

**13:06** - _Saron Yitbarek_

我的观点是，那些维护者可能并不是新的贡献者需要担忧的问题。他们正努力地想去做到一切。他们甚至会花时间标注一些东西给初学者使用（很多维护者都这样），以便新手有机会施展自己。  

**13:27** - _Saron Yitbarek_

最终，所有PR和提交的范围都变得异常庞大。我们要如何确保这种情况不会发生呢？我们该如何为维护者创造有意义的环境呢？  

**13:41** - _Saron Yitbarek_

一种解决方案是像 Fedora 这样有这强大社区的开源项目。 Fedora 项目负责人 Mattew Miller 解释了项目吸引维护者和贡献者的地方。  

**13:55** - _Matthew Miller_

许多 Fedora 项目不光是开发，而是开发过程中所相关的一切。总体来说， IT、 CS（ Computer Science，计算机科学）事实上都是如此。开源可能并没有足够的这类围绕开源的支持性的角色。  

**14:11** - _Saron Yitbarek_

那种支持实际上看起来是怎样的呢？  

**14:14** - _Matthew Miller_

我们拿来举例的带薪角色之一是 Fedora 计划经理，他帮着让计划按部就班进行，并且监管着人们来保证文书工作被完成。让人有酬劳地来做这份工作事实上可以帮着压制官僚主义，因为他们可以把时间花在使项目成为人的事情，而不只是一堆杂乱的文件。  

**14:34** - _Matthew Miller_

我认为像这样的企业参与可以赋予某些角色你无法用志愿者保证的稳定性。  

**14:43** - _Saron Yitbarek_

这有点让我想起了自由职业者使用的工作空间。那里有一个共享的接待区、共享的 wifi 和共享的咖啡。经理在管理它，你可以自由地做你自己的事情。  

**14:55** - _Saron Yitbarek_

Matthew 告诉了我们另一个 Fedora 修复项目。他们避免让你在项目中途休息一下时感觉一切都崩溃了。  

**15:04** - _Matthew Miller_

我们所关注的一件事是确保领袖角色的自然结局，所谓的签约并不一定是终身的委任。你可以重新注册，在一年后不会被踢出去。如果六个月后你想离开，你可以优雅地这样做而不必觉得会让人失望。我们已在努力确保人们可以方便地离开。  

**15:27** - _Saron Yitbarek_

Matthew 认为关键在于找到不费力的方法来支持开源社区。  

**15:35** - _Matthew Miller_

它几乎就像一个家庭，而不是像工作场所之类的东西。做出贡献很有意义，因为你不仅在为自己或是某些薪酬或最终产品工作，而是由于共事的是你的朋友，你们一起工作来做出的比个人努力能做到的更大的东西。  

**15:56** - _Saron Yitbarek_

无论是由于 Fedora 还是其他方面的功劳，一个开源贡献得以持续的世界，现在都值得为之奋斗。  

**16:10** - _Saron Yitbarek_

同时，回到了办公桌旁，我们正在追踪的新贡献者刚完成了维护者要求的修改。她还没意识到，她即将拥有第一个被接受的 PR。  

**16:24** - _Saron Yitbarek_

当我们谈论诸如倦怠之类的长期问题时，很容易忽视那些早期步骤。每天都有很多新的贡献者加入进来。这实际上就是为什么我们需要在所有这些开源魔术发生的地方建立一个可持续的人道场所。  

**16:49** - _Saron Yitbarek_

最终，我们的贡献者和维护者共同努力，推动事情向前发展。故事的最后一部分——记住所有的来往都依赖于 GitHub 和 GitLab 之类的开发平台，这些平台使得我们可以聚集到一起。  

**17:09** - _Saron Yitbarek_

我想深入探讨一下这些社区是如何使我们的工作成为可能的。我和 Shannon Crabill 谈过这个问题。 Shannon 白天是个电子邮件开发者，但到了晚上，她正在学习前端开发。她也是一个了解社区价值的人。  

**17:28** - _Saron Yitbarek_

去年她参加了一个长达一个月名为 Hacktoberfest 的开源活动，该活动旨在使得更多的人为开源做出贡献。当时， Shannon 完全是一个开源新手。  

**17:44** - _Shannon Crabill_

回想起十月那时候，我感觉我没有太多工作要做，而且可能还有其他甚至更多的新手没找到需要做的东西。也许如果我提出一些相对容易的方法，他们就可以找到一定的可以尝试和学习的地方，并且习惯使用 Git 和 GitHub。  

**18:04** - _Shannon Crabill_

我认为最困难的部分在于习惯其工作原理并付诸实践。如何 push 到 repo？如何共享项目？如何处理 PR 和类似的东西？我让人们做出了贡献，这令人惊讶，但也确实很棒。  

**18:21** - _Saron Yitbarek_

真的很恐怖吗？我觉得如果你是个新手，即使有 repo，也要走出自己的小世界，把自己放在那里。现在，你实际上已经在使人们做出贡献，你必须和他们交谈，审查他们的代码并发表意见。这听上去是有点吓人。  

**18:42** - _Shannon Crabill_

我认为最初的反应是，“哦我的天哪，这太酷了”，还有，“天哪，我让自己陷入了什么？”我意识到我已经把自己的代码合并进了自己的代码，我合并了自己的 PR 并将其推送到站点上，以及其他所有类似的事情。我从没处理过别人的。我认为我之前尚未发起过 PR，并在那之前合并它，所以我不得不把这弄清楚。总的来说，合并的复杂性仍然是我要努力解决的问题。  

**19:09** - _Shannon Crabill_

这是旋风一样的感觉，“这很酷。我不知道该怎么做。”每个人都很友好，并且我只是努力保持非常友好和真诚，即使只是，“嘿，我不知所措。我看到了每个人的 PR。今晚我不会找他们，但我明天会的。”人们对这似乎反应良好。  

**19:26** - _Saron Yitbarek_

是的。当你维护一个项目时（尤其是作为一个新的开发者时），我一直想知道的是，是不是这意味着你必须是在这个 repo 工作的最聪明的人？你实际上在评分，评判并审查其他人的代码。你是否遇到过自己懂得不如提交 PR 的人那么多？你是如何处理的？  

**19:55** - _Shannon Crabill_

好问题。我认为这样的想法，“噢，我需要成为有史以来最聪明最好的开发者”，可能会成为障碍。我觉得自己很幸运，我没有在起初时这样想，所以我能像这样说，“让我们一起去看看会发生什么吧。”  

**20:12** - _Shannon Crabill_

你无需成为一个有 20 年经验的高级开发人员。你只需要有一个主意，并且知道如何使用相应软件，然后愿意去学习自己不知道的东西。  

**20:22** - _Shannon Crabill_

肯定有一两个 PR 为我的项目添加了一些很酷的功能，说实话，如果它们崩溃了，我真不知道该如何修复。我可能会看着代码然后想道，“是的，它崩溃了。”我不知道该怎么做才能从头构建它们。  

**20:34** - _Shannon Crabill_

我认为这很酷。如果只有我一个人在做贡献，我可能做了一些整洁的工作，但没法像其他人带着经验所作的工作那么酷。  

**20:45** - _Saron Yitbarek_

作为一个维护者，在使项目更易于访问，更加友好，更加易于贡献的过程中，你学到了些什么经验呢？  

**20:55** - _Shannon Crabill_

当然。确实有件我认为很有帮助，并且我希望我起初就做的事，那就是尽可能的建立模板，以及文档、文档、文档。  

**21:07** - _Shannon Crabill_

我确实在我的 README 文件里加了很多东西，并且我认为开始时有一个 README 文件确实是很重要的一步。甚至只是链接到，“嘿，请查看我们的贡献准则。”我认为制作了一个PR模板、一个工单模板，“单击这里查看当前工单”，从而人们不会多次提交同样的内容。  

**21:31** - _Shannon Crabill_

让项目尽可能简单，或尽可能对用户友好，我认为这是你作为维护者可以迈出的一大步。  

**21:38** - _Saron Yitbarek_

绝对是这样， README 文件，我经常看到它们，经常听说他们有多么多么重要。我觉得在 README 文件里还可以做很多事情。归根结底，它是一种空白文档，告诉人们去阅读它。你应该在文档里做什么呢？你该如何构建它来使得它真正与希望做出贡献的人产生关联呢？  

**22:00** - _Shannon Crabill_

我在我的 README 文件里放了很多 gif。  

**22:03** - _Saron Yitbarek_

很好。  

**22:05** - _Shannon Crabill_

我有 gif，我也有链接。  

**22:07** - _Saron Yitbarek_

我开始听说的是 Shannon 很快就认识到了这种关系的重要性。她立马就认识到，如果有人投资，这项工作就会闪光，甚至会度过很美好的时光。  

**22:20** - _Shannon Crabill_

有人在开源项目上做得很好，我也认为这很有趣，而且有个有趣的项目，“嘿，我制作了这些很酷的蝙蝠，每次你单击的时候都会在页面上随机生成。”  

**22:33** - _Saron Yitbarek_

我也喜欢人们有很多不同的事情可以做。如果你真的很喜欢艺术性的东西，你可以做蝙蝠生成功能。如果你想清理，你也可以做。如果你想说，“我会坚持使用文档。我将花时间为我其他的贡献者们把环境变得更加干净”，那你也可以选择做这个。  

**22:56** - _Shannon Crabill_

是的。我试图说明的是，无论你想贡献的是什么，对我来说都可以。如果你发现了一个拼写错误并且想要纠正它，很好。如果你发现某个链接损坏并且想要修复它，也很好。如果你只是想帮着注释这份代码，使得它更易于阅读和理解，那也将很有帮助。  

**23:12** - _Saron Yitbarek_

我认为你在社区中获得了如此积极的经历真的很棒，因为我听说过很多实际上并不是这样的故事。人们在网络上并不十分友好，也不太热情善良，尤其是对我们一些可能会问出比预期更简单问题的新手。  

**23:33** - _Saron Yitbarek_

你认为是什么使得你的社区比起其他社区更加友好呢？  

**23:41** - _Shannon Crabill_

只是因为这是一件很随意的事。如果你想做出贡献，你可以，这很酷。如果你不想，那也很酷。我认为开源绝对是一件令人恐惧的大事，你需要具备所有这些经验，并且了解所有这些复杂的语言或是前后端以及介于这二者之间的一切，才能够做出贡献。  

**24:03** - _Saron Yitbarek_

绝对是这样。 Hacktoberfest 怎么样了？它怎样改变了你现在对开源的想法？  

**24:11** - _Shannon Crabill_

它肯定让我的看法变得更好了。就像我说的，我有很棒的经历，而且我希望每一个以某种方式参与我项目的人也能有很好的经历。这毫无疑问促使我想去尝试更多类似的事情，即使它们没有进一步的发展。现在这看起来更容易实现了。  

**24:32** - _Saron Yitbarek_

音乐响起来。  

**24:34** - _Saron Yitbarek_

这儿有个信息，来自数百家公司的数千人，以及一些根本没在公司工作的人，为 Linux 内核做出过贡献。这意味着基本上运行着互联网的 Linux 是由一群日常英雄在维护的。如果你渴望为开源作出第一次贡献，或许你会想了解有关 Fedora 社区的更多信息，我们有大量的资料正等着来帮助你。请查阅 redhat.com/commandlineheroes 以获得更多信息。  

**25:20** - _Saron Yitbarek_

快速提醒一下，这一季我们将构建我们自己的开源代码英雄（ Command Line Heroes ）游戏。欢迎你以对你来说合理的方式来做出贡献。快来了解如何成为其中一员吧。我们希望你可以通过 redhat.com/commandlineheroes 和我们一起开发这款游戏。  

**25:42** - _Saron Yitbarek_

下一集，我们将讨论残酷的达尔文式（ Darwinian ）错误过程以及开源开发中失败的美丽之处——它如何困扰我们，指导我们，并使我们变得更好。  

**25:57** - _Saron Yitbarek_

代码英雄（ Command Line Heroes ）是 Red Hat 的原创播客。你可以在 Apple Podcast、 Google Podcast 或是其他你喜欢的途径免费收听。我是 Saron Yitbarek，直到下一次，继续写代码吧。  

--------------------------------------------------------------------------------

via: https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit

作者：[Red Hat][a]
选题：[bestony][b]
译者：[JonnieWayy](https://github.com/JonnieWayy)
校对：[acyanbird](https://github.com/acyanbird)

本文由 [LCRH](https://github.com/LCTT/LCRH) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出  

[a]: https://www.redhat.com/en/command-line-heroes  
[b]: https://github.com/bestony  
