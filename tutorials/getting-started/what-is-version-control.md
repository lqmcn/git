![什么是版本控制](https://www.atlassian.com/git/images/tutorials/getting-started/what-is-version-control/hero.svg "什么是版本控制配图")

#什么是版本控制

版本控制系统的软件工具，帮助软件开发团队管理随时间的变化对源代码的一个类别。版本控制软件可以跟踪每一个修改的源代码的一种特殊的数据库。如果做错了，开发者可以时光倒流，并比较早期版本的代码，以帮助解决错误，同时尽量减少中断所有团队成员。

对于几乎所有的软件项目，源代码就像是王冠上的宝石 - 一个宝贵的资产，其价值必须得到保护。对于大多数软件团队的源代码是有关，开发商已经收集并通过认真努力改进问题领域的宝贵知识和理解的仓库。版本控制保护源代码来自灾难和人为错误和意想不到的后果休闲的退化。

在团队中工作的软件开发人员不断编写新的源代码，并改变现有的源代码。一个项目，应用程序或软件组件的代码通常组织在一个文件夹结构或“文件树”。在球队一个开发人员可以在一个新的功能一起工作，而另一名开发人员修复了更改代码无关的错误，每个开发者可以让自己的修改文件树的几部分组成。

版本控制可以帮助团队解决这类问题，跟踪每个贡献者每一个人的变化，并帮助阻止并发工作的相互矛盾的。在软件的一个组成部分所做的更改可以与其他开发人员同时工作作出不兼容。这个问题应该被发现，也不会妨碍球队的其他工作有条不紊地解决。此外，在所有的软件开发，任何改变可以引入对自己和新的软件新的错误不能被信任，直到它的测试。因此，测试和开发进行在一起，直到一个新的版本已经准备就绪。

良好的版本控制软件支持开发人员首选的工作流而不强加工作的一个特定的方式。理想的情况下它也可以在任何平台上，而不是主宰操作系统或工具链，开发人员必须使用的。伟大的版本控制系统方便修改的平稳和持续流向代码，而不是文件锁定的令人沮丧和笨拙的机制 - 在阻塞其他的进步为代价给绿灯一位开发商。

不使用任何形式的版本控制软件团队经常遇到这样不知道问题已经做出的更改可供用户或工作两个不相干的片之间不兼容的更改则必须费尽周折解开，返工的创建。如果你是谁从未使用版本控制开发人员，您可能已添加版本文件，或许是像后缀“最终”或“最新”，然后不得不在以后使用新的最终版本处理。也许你已经注释掉的代码块，因为你想不删除代码，以禁用某些功能，担心有可能是使用了后来。版本控制是一个出路的这些问题。

版本控制软件是现代软件团队的专业实践的每一天的重要组成部分。谁习惯于在他们的团队有能力的版本控制系统独立软件开发者通常认识到令人难以置信的价值版本控制也给他们即使在小型个人项目。一旦习惯了版本控制系统的功能强大的优点，许多开发商不会考虑即使对于非软件项目没有它的工作。

###版本控制的好处

不使用版本控制软件开发是有风险的，例如没有备份。版本控制也可以使开发人员能够更快地移动，它允许软件开发团队的团队扩展到包括更多的开发维护的效率和灵活性。

版本控制系统（VCS）在过去的几十年中看到了很大的改进，有些是比别人做得更好。 VCS有时被称为SCM（源代码管理）工具或RCS（版本控制系统）。其中一个目前使用的最流行的版本控制系统被称为Git的。 Git是一个分布式VCS，被称为DVCS一个类别，稍后更多。就像当今许多最流行的VCS系统，Git是自由和开放源码。不管他们叫什么，或使用哪种系统，你应该从版本控制预期主要优点如下。

1.每一个文件的完整的长期变化历史。这意味着许多人多年来所取得的每一个变化。变化包括文件的创建和删除以及修改其内容。不同的VCS工具它们处理的如何重新命名和文件的移动有所不同。这段历史还应该包括作者，日期和书面笔记上的每个变化的目的。具有完整的历史能够追溯到以前的版本在错误的根本原因分析，以帮助和需要解决在旧版本的软件问题时，它是至关重要的。如果软件正在积极开发中，几乎都可以被认为是软件的“旧版本”。

2.分支与合并。其团队成员的工作同时是一个没有脑子，但即使是个人对自己的工作可以从对变化的独立流工作能力中受益。在VCS工具创建一个“分支”工作保持相互独立的多个数据流，同时还提供了设施合并工作重新走到一起，使开发者能够验证每个分支的变化不冲突。许多软件团队采用分支各功能或分支也许每个版本，或两者的做法。有许多不同的工作流，团队可以从当他们决定如何利用分支和VCS合并设施选择。

3.可追溯性。能够追踪到软件的每次变化，将其连接到项目管理和bug跟踪软件，如JIRA，并能标注与描述变化的目的和意图的消息每次变化可以帮助不仅根本原因分析和其他取证。有在您的指尖，当你正在阅读的代码，代码的注释历史，试图了解它在做什么以及为什么它如此设计可以使开发人员能够做出皆符合预期长期的设计正确，和谐的变化该系统。这可能与遗留代码有效的工作尤为重要，是让开发人员估计任何准确今后的工作至关重要。

虽然可以开发软件，而无需使用任何版本控制，这样做科目的项目，没有专业团队会建议接受巨大的风险。所以，问题不在于是否使用版本控制，但该版本控制系统中使用。

有很多选择，但在这里我们要重点只有一个，Git的。

原文：[What is version control](https://www.atlassian.com/git/tutorials/what-is-version-control/benefits-of-version-control "What is version control")