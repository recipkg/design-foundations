# 设计来源与适用边界

以下为 2026-10-28 查阅的公开一手资料；本配方以自己的文字综合工作原则，不复制这些系统的资产或宣称代表它们。各系统针对不同平台和产品，选择时应依据目标用户及产品约束。链接是来源记录，不代替配方里的可执行要求。

| 来源 | 本配方采用的方向 | 限制 |
| --- | --- | --- |
| [Apple Human Interface Guidelines：布局](https://developer.apple.com/design/human-interface-guidelines/layout) | 层级、对齐、阅读方向、适应布局。 | Apple 平台的具体材料与样式不自动适用于其他产品。 |
| [Apple：动效](https://developer.apple.com/design/human-interface-guidelines/motion) | 有目的的反馈、可选/可中断动效。 | 动效不是唯一的信息载体。 |
| [Microsoft Fluent 2：设计原则](https://fluent2.microsoft.design/design-principles) | 适应平台、支持专注、多样用户与产品识别。 | 品牌专属设计不应照搬。 |
| [Android：自适应布局](https://developer.android.com/design/ui/mobile/guides/layout-and-content/adapt-layout) | 随窗口与内容重新组织布局，而不是只按设备名称等比缩放。 | Android 对尺寸和平台行为的细节需按目标端适配。 |
| [IBM Carbon：可访问性](https://www.carbondesignsystem.com/building-blocks/foundations/accessibility/overview) | 考虑不同能力与输入方式，组合自动和人工验证。 | 组件测试不能自动证明整个产品可访问。 |
| [GOV.UK：错误信息](https://design-system.service.gov.uk/components/error-message/) | 关联具体字段、保留已填内容、说明如何修正。 | 其特定政府服务文案和组件不是全场景视觉模板。 |
| [W3C WCAG 2.2](https://www.w3.org/TR/WCAG22/) | 可测试的 Web 可访问性基线与例外。 | 完整合规需要逐项评估全部适用准则，不等于本配方内样例检查。 |

Google Material 3 和 Atlassian Design 也值得作为后续来源。Material 页面在本次文本抓取中需要 JavaScript，本版没有把其具体细节当成已核对事实。未对任何设计体系做全面优劣排名，也没有进行真实用户研究。
