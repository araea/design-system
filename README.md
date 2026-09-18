# 设计系统

统一我所有项目的设计规范

适用于所有项目：视觉取值、交互原则、文案规则。项目按自己的媒介落地，规范只给默认口径。

> M3E for expression. HIG for experience. Design Tokens for consistency. Platform conventions for adaptation.

## 文档

四份文档是同一套设计系统的四层。

| 文档 | 管什么 |
| --- | --- |
| [设计系统](docs/design-system.md) | 主张、分工、原则、决策优先级。哲学、视觉语言、体验原则、令牌分类、平台适配 |
| [视觉系统](docs/visual-system.md) | 色彩推导、对比度、字阶、形状、高度、组件、让位 |
| [交互系统](docs/interaction.md) | 八条原则的译法、交互模式、节奏、自适应、信息架构 |
| [内容系统](docs/content.md) | 声音、语气、标点、状态符号、术语、卡片文案 |

冲突时按[设计系统的决策优先级](docs/design-system.md#决策优先级)排。

## 用法

- 规范只有这一份。项目仓库不放规范副本。
- 视觉实现取令牌。版式层不另写数值。
- 可机械验证的条目没有让位余地，例如术语、符号、标点、命名、开关。
- 让位的理由写在代码注释里。

## 参考

| 来源 | 用在 |
| --- | --- |
| [Material 3 Expressive](https://m3.material.io/) | 色彩角色、字阶、形状、高度的令牌 |
| [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/design-principles) | 九条体验原则、八条取舍原则 |
| [Nielsen Norman Group](https://www.nngroup.com/articles/ten-usability-heuristics/) | 可用性启发式。取错误预防、认得出优于记得住 |
| [WCAG 2.2](https://www.w3.org/TR/WCAG22/) | 对比度阈值、颜色不作唯一通道、减弱动态效果 |

## 许可

MIT OR Apache-2.0
