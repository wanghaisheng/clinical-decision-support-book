# CDS Starter Kit 简介
## CDS的意义和价值
HIMSS中对CDS的定义：利用相关有用的临床知识和患者信息来提高健康保健决策和行为的过程，提高医疗服务质量。
更多参考资料请参考[3]、[4]、[5]

## 5种常见的CDS类型

| *类型* | *目标* | *说明* | *如何使用* |
| -- | -- | -- | -- |
| Alert &reminder |诊疗过程中提供一些警示信息 | 通常是一些弹出框、特殊布局的提醒列表、字体/颜色的设置变化等。具体设计根据提供的信息类型和重要程度相关。如药物过敏程度是弹出框，通用药物vs名牌药物 则只是字体的变化[倾向于一些成熟的知识和内容] | 主要用在处方和时间敏感性保健如年度预防保健筛查  倾向于一些成熟的知识和内容 |
| Order sets | 按照临床目的确定的一组医嘱。医嘱套餐避免了针对某种情况重复指定单个检验、用药等等 提高效率 降低错误 | 套餐医嘱和其他医嘱没什么区别[倾向于最佳实践] | 使得医嘱过程更加高效、标准化 |
| Infobutton | 提供EHR中出现的术语/词汇参考信息的外链。这种与alert的区别在于 医生是主动式获取 而非被动式推送 | 一般是在关键词旁边有一个小按钮或图标[相关的信息] 如![](material/infor.png) | 只要需要更多信息就可以用到.如在病情名称、药物名称的旁边 以提供更多信息 |
| Data display | 下医嘱或chart审查时做参考、指导或在恰当时提供病人个案信息。与某个用户动作触发的alert不同，这是由信息触发的 | 针对特殊疾病的健康信息的数据展示[相关的个案数据] 如糖尿病flowsheet或者撰写新处方时过敏状态的展示。也可能是dashboard的形式或者是科室的监测系统 如ED监测 | 不是通过提供一个alert或者是简化下医嘱的过程，而是提供能够指导医师做出更可靠选择的信息来辅助决策 |
| Documentation template文档模板 | 用以采集信息的结构化的电子表单。如果它们用作支持通用文档目的、支持后续工作流中的其他工具或者支持诸如质控等临床目的 文档模板也可以看作一种CDS | 就是有很多字段 可以键入信息的电子表单[通用的各种病历模板]。可以是自由文本 抑或是下拉菜单形式 | 任意数据采集中都可以使用 |

## CDS与meaningful use的关系

如果广泛使用，CDS能提高医疗服务的质量。HIMSS对CDS的定义更加宽泛，而MU中则具体得多：CDS是一种HIT功能，基于EHR，在恰当的时间为涉及临床诊疗的医务人员提供事先整理和过滤好的一般信息和针对个体的信息，以此来提高医疗水平。
CMS和ONC所启动的EHR 的meaningful use的刺激计划是实现这个目标很重要的一步。新成立的区域的Extension center旨在帮助实施和有效使用EHR。在MU中，安装通过认证的EHR，同时上报数据，以证明自己能够有效使用EHR，合格的医疗机构就可以拿到一笔奖励。2011-2012年上报的MU准则已经确定了，下一阶段也就是2013-2015年的准则即将设定。
MU2011准则中要求实现药物-药物和药物-过敏交互和对以及实现一个CDS alert 规则，能够追踪该rule的符合性。
## 参考资料

1. **出自ACDS项目**
2. [原文](material/del-3-7-starter-kit-intro.pdf)
3. Bates DW, Gawande AA. Improving safety with information technology. N Engl J Med. 2003 Jun 19;348(25):2526-34.— This article by David Bates and Atul Gawande lays out the many ways in which information technology, including clinical decision support, can improve the quality of care.
4. Bates DW, Kuperman GJ, Wang S, Gandhi T, Kittler A, Volk L, Spurr C, Khorasani R, Tanasijevic M, Middleton B. Ten commandments for effective clinical decision support: making the practice of evidence-based medicine a reality. J Am Med Inform Assoc. 2003 Nov-Dec;10(6):523-30. Epub 2003 Aug 4.— This study suggest the ways in which CDS can be useful for the practice of evidence-based medicine. Furthermore, the ten commandments lay out key considerations for those who plan to implement CDS systems.
5. Agency for Healthcare Research & Quality (AHRQ), Clinical Decision Support Website – This website includes a library of  resources that address pre-implementation planning, implementation of CDS, and post-implementation use.  A list of implementation tools and resources, as well as stories from past CDS implementations, are available
