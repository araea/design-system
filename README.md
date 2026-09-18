# 设计系统

我自己的设计系统，用于统一我开发的所有项目。

它是一份跨项目的约定：视觉取值、交互原则与文案规则收在一处，任何项目拿来即用，不需要在每个仓库里重新定一套。系统给默认口径，项目按自己的媒介落地。

> M3E for expression. HIG for experience. Design Tokens for consistency. Platform conventions for adaptation.

## 文档

四份文档是同一套设计系统的四层。

| 文档 | 管什么 |
| --- | --- |
| [设计系统](docs/design-system.md) | 总纲：主张、核心分工、设计原则、决策优先级，以及哲学、视觉语言、体验原则、十类令牌的分工、平台适配 |
| [视觉系统](docs/visual-system.md) | 取值：色彩推导、对比度、字阶、形状、高度、组件基元、让位边界 |
| [交互系统](docs/interaction.md) | 行为：HIG 八条原则的译法、引用与并发、节奏、自适应、信息架构 |
| [内容系统](docs/content.md) | 文字：声音、语气、标点、状态符号、术语与卡片文案的分层 |

冲突时按[总纲的决策优先级](docs/design-system.md#决策优先级)排。

## 用法

- **一份来源。** 规范只有这一份，项目仓库里不放副本。两份同样的东西放两个地方，改动迟早只落在一处。
- **取值走令牌。** 视觉实现一律取令牌，不在版式里另写一个相似的数。同一种数值在两处出现就是缺陷。
- **受约束的一致。** 可机械验证的条目（术语、符号、标点、命名）没有让位余地；钉不住的写在交互系统里。
- **让位要声明。** 与内容、与外部实现、与平台惯例冲突时，让位可以，但理由写在代码注释里，看一眼就知道不是漏改。

系统不机械复制 Material，也不机械模仿 Apple。从 M3E 拿表现力与视觉系统化，从 HIG 拿清晰、克制、层级与自然交互。

## 参考

| 来源 | 用在 |
| --- | --- |
| [Material 3 Expressive](https://m3.material.io/) | 色彩角色、字阶、形状、高度的令牌 |
| [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/design-principles) | 九条体验原则与八条取舍原则 |
| [Nielsen Norman Group](https://www.nngroup.com/articles/ten-usability-heuristics/) | 可用性启发式，主要取「错误预防」与「认得出优于记得住」 |
| [WCAG 2.2](https://www.w3.org/TR/WCAG22/) | 对比度阈值、颜色不作唯一通道、减弱动态效果 |

## 许可

MIT OR Apache-2.0
